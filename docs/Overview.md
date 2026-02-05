# Overview

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | [**ResortStatus**](ResortStatus.md) | Current operational status of the resort (open or closed).  This is calculated based on the current time relative to today&#39;s scheduled hours. | 
**OpensAt** | Pointer to **NullableString** | Today&#39;s scheduled opening time in 24-hour format (HH:MM).  &#x60;null&#x60; if the resort is not scheduled to open today. | [optional] 
**ClosesAt** | Pointer to **NullableString** | Today&#39;s scheduled closing time in 24-hour format (HH:MM).  &#x60;null&#x60; if the resort is not scheduled to open today. | [optional] 
**Season** | [**SeasonType**](SeasonType.md) | Current operating season (winter, summer, or closed/off-season). | 
**News** | **string** | Written news — daily update, announcements, etc. (Markdown source). | 
**NewsHtml** | **string** | Written news — daily update, announcements, etc. (rendered as HTML from Markdown). | 
**NewsUpdatedAt** | **time.Time** | When the written news was last updated. | 
**OpenRuns** | Pointer to **NullableInt64** | Number of runs currently open.  Not included if the runs status feature is disabled. | [optional] 
**GroomedRuns** | Pointer to **NullableInt64** | Number of runs groomed within the last 24 hours.  Not included if the runs grooming feature is disabled. | [optional] 
**TotalRuns** | **int64** | Total number of runs at the resort. | 
**OpenAcres** | Pointer to **NullableInt64** | Total acres of open runs.  Not included if acres are not tracked or run status feature is disabled. | [optional] 
**TotalAcres** | Pointer to **NullableInt64** | Total acres of all runs.  Not included if acres are not tracked. | [optional] 
**RunsUpdatedAt** | **time.Time** | When the most recent update to run status was made. | 
**OpenLifts** | Pointer to **NullableInt64** | Number of lifts currently open.  Not included if the lifts status feature is disabled. | [optional] 
**TotalLifts** | **int64** | Total number of lifts at the resort. | 
**LiftsUpdatedAt** | **time.Time** | When the most recent update to lift status was made. | 
**OpenSummerTrails** | Pointer to **NullableInt64** | Number of summer trails currently open.  Not included if the summer trails status feature is disabled. | [optional] 
**TotalSummerTrails** | **int64** | Total number of summer trails at the resort. | 
**SummerTrailsUpdatedAt** | **time.Time** | When the most recent update to summer trail status was made. | 
**OpenTerrainParks** | Pointer to **NullableInt64** | Number of terrain parks currently open.  Not included if the terrain parks status feature is disabled. | [optional] 
**TotalTerrainParks** | **int64** | Total number of terrain parks at the resort. | 
**TerrainParksUpdatedAt** | **time.Time** | When the most recent update to terrain park status was made. | 

## Methods

### NewOverview

`func NewOverview(status ResortStatus, season SeasonType, news string, newsHtml string, newsUpdatedAt time.Time, totalRuns int64, runsUpdatedAt time.Time, totalLifts int64, liftsUpdatedAt time.Time, totalSummerTrails int64, summerTrailsUpdatedAt time.Time, totalTerrainParks int64, terrainParksUpdatedAt time.Time, ) *Overview`

NewOverview instantiates a new Overview object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOverviewWithDefaults

`func NewOverviewWithDefaults() *Overview`

NewOverviewWithDefaults instantiates a new Overview object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *Overview) GetStatus() ResortStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Overview) GetStatusOk() (*ResortStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Overview) SetStatus(v ResortStatus)`

SetStatus sets Status field to given value.


### GetOpensAt

`func (o *Overview) GetOpensAt() string`

GetOpensAt returns the OpensAt field if non-nil, zero value otherwise.

### GetOpensAtOk

`func (o *Overview) GetOpensAtOk() (*string, bool)`

GetOpensAtOk returns a tuple with the OpensAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpensAt

`func (o *Overview) SetOpensAt(v string)`

SetOpensAt sets OpensAt field to given value.

### HasOpensAt

`func (o *Overview) HasOpensAt() bool`

HasOpensAt returns a boolean if a field has been set.

### SetOpensAtNil

`func (o *Overview) SetOpensAtNil(b bool)`

 SetOpensAtNil sets the value for OpensAt to be an explicit nil

### UnsetOpensAt
`func (o *Overview) UnsetOpensAt()`

UnsetOpensAt ensures that no value is present for OpensAt, not even an explicit nil
### GetClosesAt

`func (o *Overview) GetClosesAt() string`

GetClosesAt returns the ClosesAt field if non-nil, zero value otherwise.

### GetClosesAtOk

`func (o *Overview) GetClosesAtOk() (*string, bool)`

GetClosesAtOk returns a tuple with the ClosesAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClosesAt

`func (o *Overview) SetClosesAt(v string)`

SetClosesAt sets ClosesAt field to given value.

### HasClosesAt

`func (o *Overview) HasClosesAt() bool`

HasClosesAt returns a boolean if a field has been set.

### SetClosesAtNil

`func (o *Overview) SetClosesAtNil(b bool)`

 SetClosesAtNil sets the value for ClosesAt to be an explicit nil

### UnsetClosesAt
`func (o *Overview) UnsetClosesAt()`

UnsetClosesAt ensures that no value is present for ClosesAt, not even an explicit nil
### GetSeason

`func (o *Overview) GetSeason() SeasonType`

GetSeason returns the Season field if non-nil, zero value otherwise.

### GetSeasonOk

`func (o *Overview) GetSeasonOk() (*SeasonType, bool)`

GetSeasonOk returns a tuple with the Season field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeason

`func (o *Overview) SetSeason(v SeasonType)`

SetSeason sets Season field to given value.


### GetNews

`func (o *Overview) GetNews() string`

GetNews returns the News field if non-nil, zero value otherwise.

### GetNewsOk

`func (o *Overview) GetNewsOk() (*string, bool)`

GetNewsOk returns a tuple with the News field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNews

`func (o *Overview) SetNews(v string)`

SetNews sets News field to given value.


### GetNewsHtml

`func (o *Overview) GetNewsHtml() string`

GetNewsHtml returns the NewsHtml field if non-nil, zero value otherwise.

### GetNewsHtmlOk

`func (o *Overview) GetNewsHtmlOk() (*string, bool)`

GetNewsHtmlOk returns a tuple with the NewsHtml field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewsHtml

`func (o *Overview) SetNewsHtml(v string)`

SetNewsHtml sets NewsHtml field to given value.


### GetNewsUpdatedAt

`func (o *Overview) GetNewsUpdatedAt() time.Time`

GetNewsUpdatedAt returns the NewsUpdatedAt field if non-nil, zero value otherwise.

### GetNewsUpdatedAtOk

`func (o *Overview) GetNewsUpdatedAtOk() (*time.Time, bool)`

GetNewsUpdatedAtOk returns a tuple with the NewsUpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewsUpdatedAt

`func (o *Overview) SetNewsUpdatedAt(v time.Time)`

SetNewsUpdatedAt sets NewsUpdatedAt field to given value.


### GetOpenRuns

`func (o *Overview) GetOpenRuns() int64`

GetOpenRuns returns the OpenRuns field if non-nil, zero value otherwise.

### GetOpenRunsOk

`func (o *Overview) GetOpenRunsOk() (*int64, bool)`

GetOpenRunsOk returns a tuple with the OpenRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenRuns

`func (o *Overview) SetOpenRuns(v int64)`

SetOpenRuns sets OpenRuns field to given value.

### HasOpenRuns

`func (o *Overview) HasOpenRuns() bool`

HasOpenRuns returns a boolean if a field has been set.

### SetOpenRunsNil

`func (o *Overview) SetOpenRunsNil(b bool)`

 SetOpenRunsNil sets the value for OpenRuns to be an explicit nil

### UnsetOpenRuns
`func (o *Overview) UnsetOpenRuns()`

UnsetOpenRuns ensures that no value is present for OpenRuns, not even an explicit nil
### GetGroomedRuns

`func (o *Overview) GetGroomedRuns() int64`

GetGroomedRuns returns the GroomedRuns field if non-nil, zero value otherwise.

### GetGroomedRunsOk

`func (o *Overview) GetGroomedRunsOk() (*int64, bool)`

GetGroomedRunsOk returns a tuple with the GroomedRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroomedRuns

`func (o *Overview) SetGroomedRuns(v int64)`

SetGroomedRuns sets GroomedRuns field to given value.

### HasGroomedRuns

`func (o *Overview) HasGroomedRuns() bool`

HasGroomedRuns returns a boolean if a field has been set.

### SetGroomedRunsNil

`func (o *Overview) SetGroomedRunsNil(b bool)`

 SetGroomedRunsNil sets the value for GroomedRuns to be an explicit nil

### UnsetGroomedRuns
`func (o *Overview) UnsetGroomedRuns()`

UnsetGroomedRuns ensures that no value is present for GroomedRuns, not even an explicit nil
### GetTotalRuns

`func (o *Overview) GetTotalRuns() int64`

GetTotalRuns returns the TotalRuns field if non-nil, zero value otherwise.

### GetTotalRunsOk

`func (o *Overview) GetTotalRunsOk() (*int64, bool)`

GetTotalRunsOk returns a tuple with the TotalRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalRuns

`func (o *Overview) SetTotalRuns(v int64)`

SetTotalRuns sets TotalRuns field to given value.


### GetOpenAcres

`func (o *Overview) GetOpenAcres() int64`

GetOpenAcres returns the OpenAcres field if non-nil, zero value otherwise.

### GetOpenAcresOk

`func (o *Overview) GetOpenAcresOk() (*int64, bool)`

GetOpenAcresOk returns a tuple with the OpenAcres field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenAcres

`func (o *Overview) SetOpenAcres(v int64)`

SetOpenAcres sets OpenAcres field to given value.

### HasOpenAcres

`func (o *Overview) HasOpenAcres() bool`

HasOpenAcres returns a boolean if a field has been set.

### SetOpenAcresNil

`func (o *Overview) SetOpenAcresNil(b bool)`

 SetOpenAcresNil sets the value for OpenAcres to be an explicit nil

### UnsetOpenAcres
`func (o *Overview) UnsetOpenAcres()`

UnsetOpenAcres ensures that no value is present for OpenAcres, not even an explicit nil
### GetTotalAcres

`func (o *Overview) GetTotalAcres() int64`

GetTotalAcres returns the TotalAcres field if non-nil, zero value otherwise.

### GetTotalAcresOk

`func (o *Overview) GetTotalAcresOk() (*int64, bool)`

GetTotalAcresOk returns a tuple with the TotalAcres field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAcres

`func (o *Overview) SetTotalAcres(v int64)`

SetTotalAcres sets TotalAcres field to given value.

### HasTotalAcres

`func (o *Overview) HasTotalAcres() bool`

HasTotalAcres returns a boolean if a field has been set.

### SetTotalAcresNil

`func (o *Overview) SetTotalAcresNil(b bool)`

 SetTotalAcresNil sets the value for TotalAcres to be an explicit nil

### UnsetTotalAcres
`func (o *Overview) UnsetTotalAcres()`

UnsetTotalAcres ensures that no value is present for TotalAcres, not even an explicit nil
### GetRunsUpdatedAt

`func (o *Overview) GetRunsUpdatedAt() time.Time`

GetRunsUpdatedAt returns the RunsUpdatedAt field if non-nil, zero value otherwise.

### GetRunsUpdatedAtOk

`func (o *Overview) GetRunsUpdatedAtOk() (*time.Time, bool)`

GetRunsUpdatedAtOk returns a tuple with the RunsUpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunsUpdatedAt

`func (o *Overview) SetRunsUpdatedAt(v time.Time)`

SetRunsUpdatedAt sets RunsUpdatedAt field to given value.


### GetOpenLifts

`func (o *Overview) GetOpenLifts() int64`

GetOpenLifts returns the OpenLifts field if non-nil, zero value otherwise.

### GetOpenLiftsOk

`func (o *Overview) GetOpenLiftsOk() (*int64, bool)`

GetOpenLiftsOk returns a tuple with the OpenLifts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenLifts

`func (o *Overview) SetOpenLifts(v int64)`

SetOpenLifts sets OpenLifts field to given value.

### HasOpenLifts

`func (o *Overview) HasOpenLifts() bool`

HasOpenLifts returns a boolean if a field has been set.

### SetOpenLiftsNil

`func (o *Overview) SetOpenLiftsNil(b bool)`

 SetOpenLiftsNil sets the value for OpenLifts to be an explicit nil

### UnsetOpenLifts
`func (o *Overview) UnsetOpenLifts()`

UnsetOpenLifts ensures that no value is present for OpenLifts, not even an explicit nil
### GetTotalLifts

`func (o *Overview) GetTotalLifts() int64`

GetTotalLifts returns the TotalLifts field if non-nil, zero value otherwise.

### GetTotalLiftsOk

`func (o *Overview) GetTotalLiftsOk() (*int64, bool)`

GetTotalLiftsOk returns a tuple with the TotalLifts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalLifts

`func (o *Overview) SetTotalLifts(v int64)`

SetTotalLifts sets TotalLifts field to given value.


### GetLiftsUpdatedAt

`func (o *Overview) GetLiftsUpdatedAt() time.Time`

GetLiftsUpdatedAt returns the LiftsUpdatedAt field if non-nil, zero value otherwise.

### GetLiftsUpdatedAtOk

`func (o *Overview) GetLiftsUpdatedAtOk() (*time.Time, bool)`

GetLiftsUpdatedAtOk returns a tuple with the LiftsUpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiftsUpdatedAt

`func (o *Overview) SetLiftsUpdatedAt(v time.Time)`

SetLiftsUpdatedAt sets LiftsUpdatedAt field to given value.


### GetOpenSummerTrails

`func (o *Overview) GetOpenSummerTrails() int64`

GetOpenSummerTrails returns the OpenSummerTrails field if non-nil, zero value otherwise.

### GetOpenSummerTrailsOk

`func (o *Overview) GetOpenSummerTrailsOk() (*int64, bool)`

GetOpenSummerTrailsOk returns a tuple with the OpenSummerTrails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenSummerTrails

`func (o *Overview) SetOpenSummerTrails(v int64)`

SetOpenSummerTrails sets OpenSummerTrails field to given value.

### HasOpenSummerTrails

`func (o *Overview) HasOpenSummerTrails() bool`

HasOpenSummerTrails returns a boolean if a field has been set.

### SetOpenSummerTrailsNil

`func (o *Overview) SetOpenSummerTrailsNil(b bool)`

 SetOpenSummerTrailsNil sets the value for OpenSummerTrails to be an explicit nil

### UnsetOpenSummerTrails
`func (o *Overview) UnsetOpenSummerTrails()`

UnsetOpenSummerTrails ensures that no value is present for OpenSummerTrails, not even an explicit nil
### GetTotalSummerTrails

`func (o *Overview) GetTotalSummerTrails() int64`

GetTotalSummerTrails returns the TotalSummerTrails field if non-nil, zero value otherwise.

### GetTotalSummerTrailsOk

`func (o *Overview) GetTotalSummerTrailsOk() (*int64, bool)`

GetTotalSummerTrailsOk returns a tuple with the TotalSummerTrails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSummerTrails

`func (o *Overview) SetTotalSummerTrails(v int64)`

SetTotalSummerTrails sets TotalSummerTrails field to given value.


### GetSummerTrailsUpdatedAt

`func (o *Overview) GetSummerTrailsUpdatedAt() time.Time`

GetSummerTrailsUpdatedAt returns the SummerTrailsUpdatedAt field if non-nil, zero value otherwise.

### GetSummerTrailsUpdatedAtOk

`func (o *Overview) GetSummerTrailsUpdatedAtOk() (*time.Time, bool)`

GetSummerTrailsUpdatedAtOk returns a tuple with the SummerTrailsUpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummerTrailsUpdatedAt

`func (o *Overview) SetSummerTrailsUpdatedAt(v time.Time)`

SetSummerTrailsUpdatedAt sets SummerTrailsUpdatedAt field to given value.


### GetOpenTerrainParks

`func (o *Overview) GetOpenTerrainParks() int64`

GetOpenTerrainParks returns the OpenTerrainParks field if non-nil, zero value otherwise.

### GetOpenTerrainParksOk

`func (o *Overview) GetOpenTerrainParksOk() (*int64, bool)`

GetOpenTerrainParksOk returns a tuple with the OpenTerrainParks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenTerrainParks

`func (o *Overview) SetOpenTerrainParks(v int64)`

SetOpenTerrainParks sets OpenTerrainParks field to given value.

### HasOpenTerrainParks

`func (o *Overview) HasOpenTerrainParks() bool`

HasOpenTerrainParks returns a boolean if a field has been set.

### SetOpenTerrainParksNil

`func (o *Overview) SetOpenTerrainParksNil(b bool)`

 SetOpenTerrainParksNil sets the value for OpenTerrainParks to be an explicit nil

### UnsetOpenTerrainParks
`func (o *Overview) UnsetOpenTerrainParks()`

UnsetOpenTerrainParks ensures that no value is present for OpenTerrainParks, not even an explicit nil
### GetTotalTerrainParks

`func (o *Overview) GetTotalTerrainParks() int64`

GetTotalTerrainParks returns the TotalTerrainParks field if non-nil, zero value otherwise.

### GetTotalTerrainParksOk

`func (o *Overview) GetTotalTerrainParksOk() (*int64, bool)`

GetTotalTerrainParksOk returns a tuple with the TotalTerrainParks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalTerrainParks

`func (o *Overview) SetTotalTerrainParks(v int64)`

SetTotalTerrainParks sets TotalTerrainParks field to given value.


### GetTerrainParksUpdatedAt

`func (o *Overview) GetTerrainParksUpdatedAt() time.Time`

GetTerrainParksUpdatedAt returns the TerrainParksUpdatedAt field if non-nil, zero value otherwise.

### GetTerrainParksUpdatedAtOk

`func (o *Overview) GetTerrainParksUpdatedAtOk() (*time.Time, bool)`

GetTerrainParksUpdatedAtOk returns a tuple with the TerrainParksUpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerrainParksUpdatedAt

`func (o *Overview) SetTerrainParksUpdatedAt(v time.Time)`

SetTerrainParksUpdatedAt sets TerrainParksUpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


