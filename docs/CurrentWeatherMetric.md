# CurrentWeatherMetric

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Temperature** | **int32** | Temperature in Celsius | 
**FeelsLike** | **int32** | Feels like temperature in Celsius | 
**Snowfall** | Pointer to **NullableInt32** | Snowfall in centimeters | [optional] 
**Precipitation** | Pointer to **NullableInt32** | Precipitation in millimeters | [optional] 
**WindSpeed** | **int32** | Wind speed in km/h | 
**WindGust** | Pointer to **NullableInt32** | Wind gust in km/h | [optional] 

## Methods

### NewCurrentWeatherMetric

`func NewCurrentWeatherMetric(temperature int32, feelsLike int32, windSpeed int32, ) *CurrentWeatherMetric`

NewCurrentWeatherMetric instantiates a new CurrentWeatherMetric object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCurrentWeatherMetricWithDefaults

`func NewCurrentWeatherMetricWithDefaults() *CurrentWeatherMetric`

NewCurrentWeatherMetricWithDefaults instantiates a new CurrentWeatherMetric object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTemperature

`func (o *CurrentWeatherMetric) GetTemperature() int32`

GetTemperature returns the Temperature field if non-nil, zero value otherwise.

### GetTemperatureOk

`func (o *CurrentWeatherMetric) GetTemperatureOk() (*int32, bool)`

GetTemperatureOk returns a tuple with the Temperature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperature

`func (o *CurrentWeatherMetric) SetTemperature(v int32)`

SetTemperature sets Temperature field to given value.


### GetFeelsLike

`func (o *CurrentWeatherMetric) GetFeelsLike() int32`

GetFeelsLike returns the FeelsLike field if non-nil, zero value otherwise.

### GetFeelsLikeOk

`func (o *CurrentWeatherMetric) GetFeelsLikeOk() (*int32, bool)`

GetFeelsLikeOk returns a tuple with the FeelsLike field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeelsLike

`func (o *CurrentWeatherMetric) SetFeelsLike(v int32)`

SetFeelsLike sets FeelsLike field to given value.


### GetSnowfall

`func (o *CurrentWeatherMetric) GetSnowfall() int32`

GetSnowfall returns the Snowfall field if non-nil, zero value otherwise.

### GetSnowfallOk

`func (o *CurrentWeatherMetric) GetSnowfallOk() (*int32, bool)`

GetSnowfallOk returns a tuple with the Snowfall field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnowfall

`func (o *CurrentWeatherMetric) SetSnowfall(v int32)`

SetSnowfall sets Snowfall field to given value.

### HasSnowfall

`func (o *CurrentWeatherMetric) HasSnowfall() bool`

HasSnowfall returns a boolean if a field has been set.

### SetSnowfallNil

`func (o *CurrentWeatherMetric) SetSnowfallNil(b bool)`

 SetSnowfallNil sets the value for Snowfall to be an explicit nil

### UnsetSnowfall
`func (o *CurrentWeatherMetric) UnsetSnowfall()`

UnsetSnowfall ensures that no value is present for Snowfall, not even an explicit nil
### GetPrecipitation

`func (o *CurrentWeatherMetric) GetPrecipitation() int32`

GetPrecipitation returns the Precipitation field if non-nil, zero value otherwise.

### GetPrecipitationOk

`func (o *CurrentWeatherMetric) GetPrecipitationOk() (*int32, bool)`

GetPrecipitationOk returns a tuple with the Precipitation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecipitation

`func (o *CurrentWeatherMetric) SetPrecipitation(v int32)`

SetPrecipitation sets Precipitation field to given value.

### HasPrecipitation

`func (o *CurrentWeatherMetric) HasPrecipitation() bool`

HasPrecipitation returns a boolean if a field has been set.

### SetPrecipitationNil

`func (o *CurrentWeatherMetric) SetPrecipitationNil(b bool)`

 SetPrecipitationNil sets the value for Precipitation to be an explicit nil

### UnsetPrecipitation
`func (o *CurrentWeatherMetric) UnsetPrecipitation()`

UnsetPrecipitation ensures that no value is present for Precipitation, not even an explicit nil
### GetWindSpeed

`func (o *CurrentWeatherMetric) GetWindSpeed() int32`

GetWindSpeed returns the WindSpeed field if non-nil, zero value otherwise.

### GetWindSpeedOk

`func (o *CurrentWeatherMetric) GetWindSpeedOk() (*int32, bool)`

GetWindSpeedOk returns a tuple with the WindSpeed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindSpeed

`func (o *CurrentWeatherMetric) SetWindSpeed(v int32)`

SetWindSpeed sets WindSpeed field to given value.


### GetWindGust

`func (o *CurrentWeatherMetric) GetWindGust() int32`

GetWindGust returns the WindGust field if non-nil, zero value otherwise.

### GetWindGustOk

`func (o *CurrentWeatherMetric) GetWindGustOk() (*int32, bool)`

GetWindGustOk returns a tuple with the WindGust field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindGust

`func (o *CurrentWeatherMetric) SetWindGust(v int32)`

SetWindGust sets WindGust field to given value.

### HasWindGust

`func (o *CurrentWeatherMetric) HasWindGust() bool`

HasWindGust returns a boolean if a field has been set.

### SetWindGustNil

`func (o *CurrentWeatherMetric) SetWindGustNil(b bool)`

 SetWindGustNil sets the value for WindGust to be an explicit nil

### UnsetWindGust
`func (o *CurrentWeatherMetric) UnsetWindGust()`

UnsetWindGust ensures that no value is present for WindGust, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


