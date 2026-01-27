# Weather

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
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


