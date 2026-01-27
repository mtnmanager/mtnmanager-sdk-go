# SnowMetrics

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Overnight** | **int32** | Snowfall during the overnight window (midnight to 9 AM local timezone). | 
**Last24h** | **int32** | Snowfall in the last 24 hours. | 
**Last48h** | **int32** | Snowfall in the last 48 hours. | 
**Last7days** | **int32** | Snowfall in the last 7 days. | 
**SeasonTotal** | **int32** | Total snowfall for the current season. | 

## Methods

### NewSnowMetrics

`func NewSnowMetrics(overnight int32, last24h int32, last48h int32, last7days int32, seasonTotal int32, ) *SnowMetrics`

NewSnowMetrics instantiates a new SnowMetrics object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSnowMetricsWithDefaults

`func NewSnowMetricsWithDefaults() *SnowMetrics`

NewSnowMetricsWithDefaults instantiates a new SnowMetrics object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOvernight

`func (o *SnowMetrics) GetOvernight() int32`

GetOvernight returns the Overnight field if non-nil, zero value otherwise.

### GetOvernightOk

`func (o *SnowMetrics) GetOvernightOk() (*int32, bool)`

GetOvernightOk returns a tuple with the Overnight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOvernight

`func (o *SnowMetrics) SetOvernight(v int32)`

SetOvernight sets Overnight field to given value.


### GetLast24h

`func (o *SnowMetrics) GetLast24h() int32`

GetLast24h returns the Last24h field if non-nil, zero value otherwise.

### GetLast24hOk

`func (o *SnowMetrics) GetLast24hOk() (*int32, bool)`

GetLast24hOk returns a tuple with the Last24h field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLast24h

`func (o *SnowMetrics) SetLast24h(v int32)`

SetLast24h sets Last24h field to given value.


### GetLast48h

`func (o *SnowMetrics) GetLast48h() int32`

GetLast48h returns the Last48h field if non-nil, zero value otherwise.

### GetLast48hOk

`func (o *SnowMetrics) GetLast48hOk() (*int32, bool)`

GetLast48hOk returns a tuple with the Last48h field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLast48h

`func (o *SnowMetrics) SetLast48h(v int32)`

SetLast48h sets Last48h field to given value.


### GetLast7days

`func (o *SnowMetrics) GetLast7days() int32`

GetLast7days returns the Last7days field if non-nil, zero value otherwise.

### GetLast7daysOk

`func (o *SnowMetrics) GetLast7daysOk() (*int32, bool)`

GetLast7daysOk returns a tuple with the Last7days field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLast7days

`func (o *SnowMetrics) SetLast7days(v int32)`

SetLast7days sets Last7days field to given value.


### GetSeasonTotal

`func (o *SnowMetrics) GetSeasonTotal() int32`

GetSeasonTotal returns the SeasonTotal field if non-nil, zero value otherwise.

### GetSeasonTotalOk

`func (o *SnowMetrics) GetSeasonTotalOk() (*int32, bool)`

GetSeasonTotalOk returns a tuple with the SeasonTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeasonTotal

`func (o *SnowMetrics) SetSeasonTotal(v int32)`

SetSeasonTotal sets SeasonTotal field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


