# Weather

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AreaUuid** | Pointer to **NullableString** | The area this weather belongs to, or omitted for resort-wide weather. | [optional] 
**AreaName** | Pointer to **NullableString** | The area&#39;s name, or omitted for resort-wide weather. | [optional] 
**AreaDisplayOrder** | Pointer to **NullableInt32** | The area&#39;s display order, or omitted for resort-wide weather. | [optional] 
**Current** | [**CurrentWeather**](CurrentWeather.md) | Current weather conditions | 
**HourlyForecast** | [**[]HourlyForecast**](HourlyForecast.md) | Hourly forecast for next 24 hours (including current hour) | 
**DailyForecast** | [**[]DailyForecast**](DailyForecast.md) | Daily forecast for next 7 days (including today) | 
**Attribution** | **string** | Data source attribution | 
**UpdatedAt** | **time.Time** | When this data was last updated | 

## Methods

### NewWeather

`func NewWeather(current CurrentWeather, hourlyForecast []HourlyForecast, dailyForecast []DailyForecast, attribution string, updatedAt time.Time, ) *Weather`

NewWeather instantiates a new Weather object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWeatherWithDefaults

`func NewWeatherWithDefaults() *Weather`

NewWeatherWithDefaults instantiates a new Weather object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAreaUuid

`func (o *Weather) GetAreaUuid() string`

GetAreaUuid returns the AreaUuid field if non-nil, zero value otherwise.

### GetAreaUuidOk

`func (o *Weather) GetAreaUuidOk() (*string, bool)`

GetAreaUuidOk returns a tuple with the AreaUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaUuid

`func (o *Weather) SetAreaUuid(v string)`

SetAreaUuid sets AreaUuid field to given value.

### HasAreaUuid

`func (o *Weather) HasAreaUuid() bool`

HasAreaUuid returns a boolean if a field has been set.

### SetAreaUuidNil

`func (o *Weather) SetAreaUuidNil(b bool)`

 SetAreaUuidNil sets the value for AreaUuid to be an explicit nil

### UnsetAreaUuid
`func (o *Weather) UnsetAreaUuid()`

UnsetAreaUuid ensures that no value is present for AreaUuid, not even an explicit nil
### GetAreaName

`func (o *Weather) GetAreaName() string`

GetAreaName returns the AreaName field if non-nil, zero value otherwise.

### GetAreaNameOk

`func (o *Weather) GetAreaNameOk() (*string, bool)`

GetAreaNameOk returns a tuple with the AreaName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaName

`func (o *Weather) SetAreaName(v string)`

SetAreaName sets AreaName field to given value.

### HasAreaName

`func (o *Weather) HasAreaName() bool`

HasAreaName returns a boolean if a field has been set.

### SetAreaNameNil

`func (o *Weather) SetAreaNameNil(b bool)`

 SetAreaNameNil sets the value for AreaName to be an explicit nil

### UnsetAreaName
`func (o *Weather) UnsetAreaName()`

UnsetAreaName ensures that no value is present for AreaName, not even an explicit nil
### GetAreaDisplayOrder

`func (o *Weather) GetAreaDisplayOrder() int32`

GetAreaDisplayOrder returns the AreaDisplayOrder field if non-nil, zero value otherwise.

### GetAreaDisplayOrderOk

`func (o *Weather) GetAreaDisplayOrderOk() (*int32, bool)`

GetAreaDisplayOrderOk returns a tuple with the AreaDisplayOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaDisplayOrder

`func (o *Weather) SetAreaDisplayOrder(v int32)`

SetAreaDisplayOrder sets AreaDisplayOrder field to given value.

### HasAreaDisplayOrder

`func (o *Weather) HasAreaDisplayOrder() bool`

HasAreaDisplayOrder returns a boolean if a field has been set.

### SetAreaDisplayOrderNil

`func (o *Weather) SetAreaDisplayOrderNil(b bool)`

 SetAreaDisplayOrderNil sets the value for AreaDisplayOrder to be an explicit nil

### UnsetAreaDisplayOrder
`func (o *Weather) UnsetAreaDisplayOrder()`

UnsetAreaDisplayOrder ensures that no value is present for AreaDisplayOrder, not even an explicit nil
### GetCurrent

`func (o *Weather) GetCurrent() CurrentWeather`

GetCurrent returns the Current field if non-nil, zero value otherwise.

### GetCurrentOk

`func (o *Weather) GetCurrentOk() (*CurrentWeather, bool)`

GetCurrentOk returns a tuple with the Current field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrent

`func (o *Weather) SetCurrent(v CurrentWeather)`

SetCurrent sets Current field to given value.


### GetHourlyForecast

`func (o *Weather) GetHourlyForecast() []HourlyForecast`

GetHourlyForecast returns the HourlyForecast field if non-nil, zero value otherwise.

### GetHourlyForecastOk

`func (o *Weather) GetHourlyForecastOk() (*[]HourlyForecast, bool)`

GetHourlyForecastOk returns a tuple with the HourlyForecast field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHourlyForecast

`func (o *Weather) SetHourlyForecast(v []HourlyForecast)`

SetHourlyForecast sets HourlyForecast field to given value.


### GetDailyForecast

`func (o *Weather) GetDailyForecast() []DailyForecast`

GetDailyForecast returns the DailyForecast field if non-nil, zero value otherwise.

### GetDailyForecastOk

`func (o *Weather) GetDailyForecastOk() (*[]DailyForecast, bool)`

GetDailyForecastOk returns a tuple with the DailyForecast field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyForecast

`func (o *Weather) SetDailyForecast(v []DailyForecast)`

SetDailyForecast sets DailyForecast field to given value.


### GetAttribution

`func (o *Weather) GetAttribution() string`

GetAttribution returns the Attribution field if non-nil, zero value otherwise.

### GetAttributionOk

`func (o *Weather) GetAttributionOk() (*string, bool)`

GetAttributionOk returns a tuple with the Attribution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttribution

`func (o *Weather) SetAttribution(v string)`

SetAttribution sets Attribution field to given value.


### GetUpdatedAt

`func (o *Weather) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Weather) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Weather) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


