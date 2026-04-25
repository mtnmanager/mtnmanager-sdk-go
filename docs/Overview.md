# Overview

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | [**ResortStatus**](ResortStatus.md) | Current operational status of the resort (open or closed).  This is calculated based on the current time relative to today&#39;s scheduled hours. | 
**OpensAt** | Pointer to **NullableString** | Today&#39;s scheduled opening time in 24-hour format (HH:MM).  &#x60;null&#x60; if the resort is not scheduled to open today. | [optional] 
**ClosesAt** | Pointer to **NullableString** | Today&#39;s scheduled closing time in 24-hour format (HH:MM).  &#x60;null&#x60; if the resort is not scheduled to open today. | [optional] 
**Season** | [**SeasonType**](SeasonType.md) | Current operating season (winter, summer, or closed/off-season). | 
**News** | [**OverviewNews**](OverviewNews.md) | Written news — daily update, announcements, etc. | 
**Runs** | [**OverviewRuns**](OverviewRuns.md) | Run statistics: counts, acres, and last-updated timestamp. | 
**Lifts** | [**OverviewLifts**](OverviewLifts.md) | Lift statistics: counts and last-updated timestamp. | 
**SummerTrails** | [**OverviewSummerTrails**](OverviewSummerTrails.md) | Summer trail statistics: counts and last-updated timestamp. | 
**TerrainParks** | [**OverviewTerrainParks**](OverviewTerrainParks.md) | Terrain park statistics: counts and last-updated timestamp. | 

## Methods

### NewOverview

`func NewOverview(status ResortStatus, season SeasonType, news OverviewNews, runs OverviewRuns, lifts OverviewLifts, summerTrails OverviewSummerTrails, terrainParks OverviewTerrainParks, ) *Overview`

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

`func (o *Overview) GetNews() OverviewNews`

GetNews returns the News field if non-nil, zero value otherwise.

### GetNewsOk

`func (o *Overview) GetNewsOk() (*OverviewNews, bool)`

GetNewsOk returns a tuple with the News field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNews

`func (o *Overview) SetNews(v OverviewNews)`

SetNews sets News field to given value.


### GetRuns

`func (o *Overview) GetRuns() OverviewRuns`

GetRuns returns the Runs field if non-nil, zero value otherwise.

### GetRunsOk

`func (o *Overview) GetRunsOk() (*OverviewRuns, bool)`

GetRunsOk returns a tuple with the Runs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuns

`func (o *Overview) SetRuns(v OverviewRuns)`

SetRuns sets Runs field to given value.


### GetLifts

`func (o *Overview) GetLifts() OverviewLifts`

GetLifts returns the Lifts field if non-nil, zero value otherwise.

### GetLiftsOk

`func (o *Overview) GetLiftsOk() (*OverviewLifts, bool)`

GetLiftsOk returns a tuple with the Lifts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLifts

`func (o *Overview) SetLifts(v OverviewLifts)`

SetLifts sets Lifts field to given value.


### GetSummerTrails

`func (o *Overview) GetSummerTrails() OverviewSummerTrails`

GetSummerTrails returns the SummerTrails field if non-nil, zero value otherwise.

### GetSummerTrailsOk

`func (o *Overview) GetSummerTrailsOk() (*OverviewSummerTrails, bool)`

GetSummerTrailsOk returns a tuple with the SummerTrails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummerTrails

`func (o *Overview) SetSummerTrails(v OverviewSummerTrails)`

SetSummerTrails sets SummerTrails field to given value.


### GetTerrainParks

`func (o *Overview) GetTerrainParks() OverviewTerrainParks`

GetTerrainParks returns the TerrainParks field if non-nil, zero value otherwise.

### GetTerrainParksOk

`func (o *Overview) GetTerrainParksOk() (*OverviewTerrainParks, bool)`

GetTerrainParksOk returns a tuple with the TerrainParks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerrainParks

`func (o *Overview) SetTerrainParks(v OverviewTerrainParks)`

SetTerrainParks sets TerrainParks field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


