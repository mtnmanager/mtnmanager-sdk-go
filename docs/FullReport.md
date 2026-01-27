# FullReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Resort** | [**ResortInfo**](ResortInfo.md) |  | 
**Status** | [**Overview**](Overview.md) |  | 
**Snow** | [**[]SnowReport**](SnowReport.md) | Provides current snow conditions including base depth, surface conditions,  and snowfall totals in both metric and imperial units.   May contain multiple, representing different reporting areas. | 
**Lifts** | [**[]Lift**](Lift.md) | List of all lifts at the resort with their current operational status,  type, and optional wait time information. | 
**Runs** | [**[]Run**](Run.md) | List of all runs at the resort with their current status,  grooming information, and difficulty rating. | 
**TerrainParks** | [**[]TerrainPark**](TerrainPark.md) | List of all terrain parks at the resort with their current status,  condition notes, and list of features (jumps, boxes, rails, etc.) within them. | 
**SummerTrails** | [**[]SummerTrail**](SummerTrail.md) | List of all summer trails at the resort with their current status,  type (e.g. hiking, mountain biking), and optional difficulty rating. | 
**Hours** | [**OperatingHours**](OperatingHours.md) |  | 
**Weather** | Pointer to [**NullableWeather**](Weather.md) |  | [optional] 

## Methods

### NewFullReport

`func NewFullReport(resort ResortInfo, status Overview, snow []SnowReport, lifts []Lift, runs []Run, terrainParks []TerrainPark, summerTrails []SummerTrail, hours OperatingHours, ) *FullReport`

NewFullReport instantiates a new FullReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFullReportWithDefaults

`func NewFullReportWithDefaults() *FullReport`

NewFullReportWithDefaults instantiates a new FullReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResort

`func (o *FullReport) GetResort() ResortInfo`

GetResort returns the Resort field if non-nil, zero value otherwise.

### GetResortOk

`func (o *FullReport) GetResortOk() (*ResortInfo, bool)`

GetResortOk returns a tuple with the Resort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResort

`func (o *FullReport) SetResort(v ResortInfo)`

SetResort sets Resort field to given value.


### GetStatus

`func (o *FullReport) GetStatus() Overview`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *FullReport) GetStatusOk() (*Overview, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *FullReport) SetStatus(v Overview)`

SetStatus sets Status field to given value.


### GetSnow

`func (o *FullReport) GetSnow() []SnowReport`

GetSnow returns the Snow field if non-nil, zero value otherwise.

### GetSnowOk

`func (o *FullReport) GetSnowOk() (*[]SnowReport, bool)`

GetSnowOk returns a tuple with the Snow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnow

`func (o *FullReport) SetSnow(v []SnowReport)`

SetSnow sets Snow field to given value.


### GetLifts

`func (o *FullReport) GetLifts() []Lift`

GetLifts returns the Lifts field if non-nil, zero value otherwise.

### GetLiftsOk

`func (o *FullReport) GetLiftsOk() (*[]Lift, bool)`

GetLiftsOk returns a tuple with the Lifts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLifts

`func (o *FullReport) SetLifts(v []Lift)`

SetLifts sets Lifts field to given value.


### GetRuns

`func (o *FullReport) GetRuns() []Run`

GetRuns returns the Runs field if non-nil, zero value otherwise.

### GetRunsOk

`func (o *FullReport) GetRunsOk() (*[]Run, bool)`

GetRunsOk returns a tuple with the Runs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuns

`func (o *FullReport) SetRuns(v []Run)`

SetRuns sets Runs field to given value.


### GetTerrainParks

`func (o *FullReport) GetTerrainParks() []TerrainPark`

GetTerrainParks returns the TerrainParks field if non-nil, zero value otherwise.

### GetTerrainParksOk

`func (o *FullReport) GetTerrainParksOk() (*[]TerrainPark, bool)`

GetTerrainParksOk returns a tuple with the TerrainParks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerrainParks

`func (o *FullReport) SetTerrainParks(v []TerrainPark)`

SetTerrainParks sets TerrainParks field to given value.


### GetSummerTrails

`func (o *FullReport) GetSummerTrails() []SummerTrail`

GetSummerTrails returns the SummerTrails field if non-nil, zero value otherwise.

### GetSummerTrailsOk

`func (o *FullReport) GetSummerTrailsOk() (*[]SummerTrail, bool)`

GetSummerTrailsOk returns a tuple with the SummerTrails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummerTrails

`func (o *FullReport) SetSummerTrails(v []SummerTrail)`

SetSummerTrails sets SummerTrails field to given value.


### GetHours

`func (o *FullReport) GetHours() OperatingHours`

GetHours returns the Hours field if non-nil, zero value otherwise.

### GetHoursOk

`func (o *FullReport) GetHoursOk() (*OperatingHours, bool)`

GetHoursOk returns a tuple with the Hours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHours

`func (o *FullReport) SetHours(v OperatingHours)`

SetHours sets Hours field to given value.


### GetWeather

`func (o *FullReport) GetWeather() Weather`

GetWeather returns the Weather field if non-nil, zero value otherwise.

### GetWeatherOk

`func (o *FullReport) GetWeatherOk() (*Weather, bool)`

GetWeatherOk returns a tuple with the Weather field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeather

`func (o *FullReport) SetWeather(v Weather)`

SetWeather sets Weather field to given value.

### HasWeather

`func (o *FullReport) HasWeather() bool`

HasWeather returns a boolean if a field has been set.

### SetWeatherNil

`func (o *FullReport) SetWeatherNil(b bool)`

 SetWeatherNil sets the value for Weather to be an explicit nil

### UnsetWeather
`func (o *FullReport) UnsetWeather()`

UnsetWeather ensures that no value is present for Weather, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


