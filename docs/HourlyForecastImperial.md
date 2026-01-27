# HourlyForecastImperial

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Temperature** | **int32** | Temperature in Fahrenheit | 
**FeelsLike** | Pointer to **NullableInt32** | Feels like temperature in Fahrenheit | [optional] 
**Snowfall** | Pointer to **NullableInt32** | Snowfall amount expected this hour in inches | [optional] 
**Precipitation** | Pointer to **NullableInt32** | Precipitation amount expected this hour in inches | [optional] 
**WindSpeed** | **int32** | Wind speed in mph | 
**WindGust** | Pointer to **NullableInt32** | Wind gust in mph | [optional] 

## Methods

### NewHourlyForecastImperial

`func NewHourlyForecastImperial(temperature int32, windSpeed int32, ) *HourlyForecastImperial`

NewHourlyForecastImperial instantiates a new HourlyForecastImperial object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHourlyForecastImperialWithDefaults

`func NewHourlyForecastImperialWithDefaults() *HourlyForecastImperial`

NewHourlyForecastImperialWithDefaults instantiates a new HourlyForecastImperial object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTemperature

`func (o *HourlyForecastImperial) GetTemperature() int32`

GetTemperature returns the Temperature field if non-nil, zero value otherwise.

### GetTemperatureOk

`func (o *HourlyForecastImperial) GetTemperatureOk() (*int32, bool)`

GetTemperatureOk returns a tuple with the Temperature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperature

`func (o *HourlyForecastImperial) SetTemperature(v int32)`

SetTemperature sets Temperature field to given value.


### GetFeelsLike

`func (o *HourlyForecastImperial) GetFeelsLike() int32`

GetFeelsLike returns the FeelsLike field if non-nil, zero value otherwise.

### GetFeelsLikeOk

`func (o *HourlyForecastImperial) GetFeelsLikeOk() (*int32, bool)`

GetFeelsLikeOk returns a tuple with the FeelsLike field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeelsLike

`func (o *HourlyForecastImperial) SetFeelsLike(v int32)`

SetFeelsLike sets FeelsLike field to given value.

### HasFeelsLike

`func (o *HourlyForecastImperial) HasFeelsLike() bool`

HasFeelsLike returns a boolean if a field has been set.

### SetFeelsLikeNil

`func (o *HourlyForecastImperial) SetFeelsLikeNil(b bool)`

 SetFeelsLikeNil sets the value for FeelsLike to be an explicit nil

### UnsetFeelsLike
`func (o *HourlyForecastImperial) UnsetFeelsLike()`

UnsetFeelsLike ensures that no value is present for FeelsLike, not even an explicit nil
### GetSnowfall

`func (o *HourlyForecastImperial) GetSnowfall() int32`

GetSnowfall returns the Snowfall field if non-nil, zero value otherwise.

### GetSnowfallOk

`func (o *HourlyForecastImperial) GetSnowfallOk() (*int32, bool)`

GetSnowfallOk returns a tuple with the Snowfall field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnowfall

`func (o *HourlyForecastImperial) SetSnowfall(v int32)`

SetSnowfall sets Snowfall field to given value.

### HasSnowfall

`func (o *HourlyForecastImperial) HasSnowfall() bool`

HasSnowfall returns a boolean if a field has been set.

### SetSnowfallNil

`func (o *HourlyForecastImperial) SetSnowfallNil(b bool)`

 SetSnowfallNil sets the value for Snowfall to be an explicit nil

### UnsetSnowfall
`func (o *HourlyForecastImperial) UnsetSnowfall()`

UnsetSnowfall ensures that no value is present for Snowfall, not even an explicit nil
### GetPrecipitation

`func (o *HourlyForecastImperial) GetPrecipitation() int32`

GetPrecipitation returns the Precipitation field if non-nil, zero value otherwise.

### GetPrecipitationOk

`func (o *HourlyForecastImperial) GetPrecipitationOk() (*int32, bool)`

GetPrecipitationOk returns a tuple with the Precipitation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecipitation

`func (o *HourlyForecastImperial) SetPrecipitation(v int32)`

SetPrecipitation sets Precipitation field to given value.

### HasPrecipitation

`func (o *HourlyForecastImperial) HasPrecipitation() bool`

HasPrecipitation returns a boolean if a field has been set.

### SetPrecipitationNil

`func (o *HourlyForecastImperial) SetPrecipitationNil(b bool)`

 SetPrecipitationNil sets the value for Precipitation to be an explicit nil

### UnsetPrecipitation
`func (o *HourlyForecastImperial) UnsetPrecipitation()`

UnsetPrecipitation ensures that no value is present for Precipitation, not even an explicit nil
### GetWindSpeed

`func (o *HourlyForecastImperial) GetWindSpeed() int32`

GetWindSpeed returns the WindSpeed field if non-nil, zero value otherwise.

### GetWindSpeedOk

`func (o *HourlyForecastImperial) GetWindSpeedOk() (*int32, bool)`

GetWindSpeedOk returns a tuple with the WindSpeed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindSpeed

`func (o *HourlyForecastImperial) SetWindSpeed(v int32)`

SetWindSpeed sets WindSpeed field to given value.


### GetWindGust

`func (o *HourlyForecastImperial) GetWindGust() int32`

GetWindGust returns the WindGust field if non-nil, zero value otherwise.

### GetWindGustOk

`func (o *HourlyForecastImperial) GetWindGustOk() (*int32, bool)`

GetWindGustOk returns a tuple with the WindGust field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindGust

`func (o *HourlyForecastImperial) SetWindGust(v int32)`

SetWindGust sets WindGust field to given value.

### HasWindGust

`func (o *HourlyForecastImperial) HasWindGust() bool`

HasWindGust returns a boolean if a field has been set.

### SetWindGustNil

`func (o *HourlyForecastImperial) SetWindGustNil(b bool)`

 SetWindGustNil sets the value for WindGust to be an explicit nil

### UnsetWindGust
`func (o *HourlyForecastImperial) UnsetWindGust()`

UnsetWindGust ensures that no value is present for WindGust, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


