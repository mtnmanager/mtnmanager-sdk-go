# HourlyForecastMetric

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Temperature** | **int32** | Temperature in Celsius | 
**FeelsLike** | Pointer to **NullableInt32** | Feels like temperature in Celsius | [optional] 
**Snowfall** | Pointer to **NullableInt32** | Snowfall amount expected this hour in centimeters | [optional] 
**Precipitation** | Pointer to **NullableInt32** | Precipitation amount expected this hour in millimeters | [optional] 
**WindSpeed** | **int32** | Wind speed in km/h | 
**WindGust** | Pointer to **NullableInt32** | Wind gust in km/h | [optional] 

## Methods

### NewHourlyForecastMetric

`func NewHourlyForecastMetric(temperature int32, windSpeed int32, ) *HourlyForecastMetric`

NewHourlyForecastMetric instantiates a new HourlyForecastMetric object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHourlyForecastMetricWithDefaults

`func NewHourlyForecastMetricWithDefaults() *HourlyForecastMetric`

NewHourlyForecastMetricWithDefaults instantiates a new HourlyForecastMetric object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTemperature

`func (o *HourlyForecastMetric) GetTemperature() int32`

GetTemperature returns the Temperature field if non-nil, zero value otherwise.

### GetTemperatureOk

`func (o *HourlyForecastMetric) GetTemperatureOk() (*int32, bool)`

GetTemperatureOk returns a tuple with the Temperature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperature

`func (o *HourlyForecastMetric) SetTemperature(v int32)`

SetTemperature sets Temperature field to given value.


### GetFeelsLike

`func (o *HourlyForecastMetric) GetFeelsLike() int32`

GetFeelsLike returns the FeelsLike field if non-nil, zero value otherwise.

### GetFeelsLikeOk

`func (o *HourlyForecastMetric) GetFeelsLikeOk() (*int32, bool)`

GetFeelsLikeOk returns a tuple with the FeelsLike field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeelsLike

`func (o *HourlyForecastMetric) SetFeelsLike(v int32)`

SetFeelsLike sets FeelsLike field to given value.

### HasFeelsLike

`func (o *HourlyForecastMetric) HasFeelsLike() bool`

HasFeelsLike returns a boolean if a field has been set.

### SetFeelsLikeNil

`func (o *HourlyForecastMetric) SetFeelsLikeNil(b bool)`

 SetFeelsLikeNil sets the value for FeelsLike to be an explicit nil

### UnsetFeelsLike
`func (o *HourlyForecastMetric) UnsetFeelsLike()`

UnsetFeelsLike ensures that no value is present for FeelsLike, not even an explicit nil
### GetSnowfall

`func (o *HourlyForecastMetric) GetSnowfall() int32`

GetSnowfall returns the Snowfall field if non-nil, zero value otherwise.

### GetSnowfallOk

`func (o *HourlyForecastMetric) GetSnowfallOk() (*int32, bool)`

GetSnowfallOk returns a tuple with the Snowfall field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnowfall

`func (o *HourlyForecastMetric) SetSnowfall(v int32)`

SetSnowfall sets Snowfall field to given value.

### HasSnowfall

`func (o *HourlyForecastMetric) HasSnowfall() bool`

HasSnowfall returns a boolean if a field has been set.

### SetSnowfallNil

`func (o *HourlyForecastMetric) SetSnowfallNil(b bool)`

 SetSnowfallNil sets the value for Snowfall to be an explicit nil

### UnsetSnowfall
`func (o *HourlyForecastMetric) UnsetSnowfall()`

UnsetSnowfall ensures that no value is present for Snowfall, not even an explicit nil
### GetPrecipitation

`func (o *HourlyForecastMetric) GetPrecipitation() int32`

GetPrecipitation returns the Precipitation field if non-nil, zero value otherwise.

### GetPrecipitationOk

`func (o *HourlyForecastMetric) GetPrecipitationOk() (*int32, bool)`

GetPrecipitationOk returns a tuple with the Precipitation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecipitation

`func (o *HourlyForecastMetric) SetPrecipitation(v int32)`

SetPrecipitation sets Precipitation field to given value.

### HasPrecipitation

`func (o *HourlyForecastMetric) HasPrecipitation() bool`

HasPrecipitation returns a boolean if a field has been set.

### SetPrecipitationNil

`func (o *HourlyForecastMetric) SetPrecipitationNil(b bool)`

 SetPrecipitationNil sets the value for Precipitation to be an explicit nil

### UnsetPrecipitation
`func (o *HourlyForecastMetric) UnsetPrecipitation()`

UnsetPrecipitation ensures that no value is present for Precipitation, not even an explicit nil
### GetWindSpeed

`func (o *HourlyForecastMetric) GetWindSpeed() int32`

GetWindSpeed returns the WindSpeed field if non-nil, zero value otherwise.

### GetWindSpeedOk

`func (o *HourlyForecastMetric) GetWindSpeedOk() (*int32, bool)`

GetWindSpeedOk returns a tuple with the WindSpeed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindSpeed

`func (o *HourlyForecastMetric) SetWindSpeed(v int32)`

SetWindSpeed sets WindSpeed field to given value.


### GetWindGust

`func (o *HourlyForecastMetric) GetWindGust() int32`

GetWindGust returns the WindGust field if non-nil, zero value otherwise.

### GetWindGustOk

`func (o *HourlyForecastMetric) GetWindGustOk() (*int32, bool)`

GetWindGustOk returns a tuple with the WindGust field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindGust

`func (o *HourlyForecastMetric) SetWindGust(v int32)`

SetWindGust sets WindGust field to given value.

### HasWindGust

`func (o *HourlyForecastMetric) HasWindGust() bool`

HasWindGust returns a boolean if a field has been set.

### SetWindGustNil

`func (o *HourlyForecastMetric) SetWindGustNil(b bool)`

 SetWindGustNil sets the value for WindGust to be an explicit nil

### UnsetWindGust
`func (o *HourlyForecastMetric) UnsetWindGust()`

UnsetWindGust ensures that no value is present for WindGust, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


