# CurrentWeatherImperial

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Temperature** | **int32** | Temperature in Fahrenheit | 
**FeelsLike** | **int32** | Feels like temperature in Fahrenheit | 
**Snowfall** | Pointer to **NullableInt32** | Snowfall in inches | [optional] 
**Precipitation** | Pointer to **NullableInt32** | Precipitation in inches | [optional] 
**WindSpeed** | **int32** | Wind speed in mph | 
**WindGust** | Pointer to **NullableInt32** | Wind gust in mph | [optional] 

## Methods

### NewCurrentWeatherImperial

`func NewCurrentWeatherImperial(temperature int32, feelsLike int32, windSpeed int32, ) *CurrentWeatherImperial`

NewCurrentWeatherImperial instantiates a new CurrentWeatherImperial object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCurrentWeatherImperialWithDefaults

`func NewCurrentWeatherImperialWithDefaults() *CurrentWeatherImperial`

NewCurrentWeatherImperialWithDefaults instantiates a new CurrentWeatherImperial object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTemperature

`func (o *CurrentWeatherImperial) GetTemperature() int32`

GetTemperature returns the Temperature field if non-nil, zero value otherwise.

### GetTemperatureOk

`func (o *CurrentWeatherImperial) GetTemperatureOk() (*int32, bool)`

GetTemperatureOk returns a tuple with the Temperature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperature

`func (o *CurrentWeatherImperial) SetTemperature(v int32)`

SetTemperature sets Temperature field to given value.


### GetFeelsLike

`func (o *CurrentWeatherImperial) GetFeelsLike() int32`

GetFeelsLike returns the FeelsLike field if non-nil, zero value otherwise.

### GetFeelsLikeOk

`func (o *CurrentWeatherImperial) GetFeelsLikeOk() (*int32, bool)`

GetFeelsLikeOk returns a tuple with the FeelsLike field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeelsLike

`func (o *CurrentWeatherImperial) SetFeelsLike(v int32)`

SetFeelsLike sets FeelsLike field to given value.


### GetSnowfall

`func (o *CurrentWeatherImperial) GetSnowfall() int32`

GetSnowfall returns the Snowfall field if non-nil, zero value otherwise.

### GetSnowfallOk

`func (o *CurrentWeatherImperial) GetSnowfallOk() (*int32, bool)`

GetSnowfallOk returns a tuple with the Snowfall field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnowfall

`func (o *CurrentWeatherImperial) SetSnowfall(v int32)`

SetSnowfall sets Snowfall field to given value.

### HasSnowfall

`func (o *CurrentWeatherImperial) HasSnowfall() bool`

HasSnowfall returns a boolean if a field has been set.

### SetSnowfallNil

`func (o *CurrentWeatherImperial) SetSnowfallNil(b bool)`

 SetSnowfallNil sets the value for Snowfall to be an explicit nil

### UnsetSnowfall
`func (o *CurrentWeatherImperial) UnsetSnowfall()`

UnsetSnowfall ensures that no value is present for Snowfall, not even an explicit nil
### GetPrecipitation

`func (o *CurrentWeatherImperial) GetPrecipitation() int32`

GetPrecipitation returns the Precipitation field if non-nil, zero value otherwise.

### GetPrecipitationOk

`func (o *CurrentWeatherImperial) GetPrecipitationOk() (*int32, bool)`

GetPrecipitationOk returns a tuple with the Precipitation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecipitation

`func (o *CurrentWeatherImperial) SetPrecipitation(v int32)`

SetPrecipitation sets Precipitation field to given value.

### HasPrecipitation

`func (o *CurrentWeatherImperial) HasPrecipitation() bool`

HasPrecipitation returns a boolean if a field has been set.

### SetPrecipitationNil

`func (o *CurrentWeatherImperial) SetPrecipitationNil(b bool)`

 SetPrecipitationNil sets the value for Precipitation to be an explicit nil

### UnsetPrecipitation
`func (o *CurrentWeatherImperial) UnsetPrecipitation()`

UnsetPrecipitation ensures that no value is present for Precipitation, not even an explicit nil
### GetWindSpeed

`func (o *CurrentWeatherImperial) GetWindSpeed() int32`

GetWindSpeed returns the WindSpeed field if non-nil, zero value otherwise.

### GetWindSpeedOk

`func (o *CurrentWeatherImperial) GetWindSpeedOk() (*int32, bool)`

GetWindSpeedOk returns a tuple with the WindSpeed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindSpeed

`func (o *CurrentWeatherImperial) SetWindSpeed(v int32)`

SetWindSpeed sets WindSpeed field to given value.


### GetWindGust

`func (o *CurrentWeatherImperial) GetWindGust() int32`

GetWindGust returns the WindGust field if non-nil, zero value otherwise.

### GetWindGustOk

`func (o *CurrentWeatherImperial) GetWindGustOk() (*int32, bool)`

GetWindGustOk returns a tuple with the WindGust field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindGust

`func (o *CurrentWeatherImperial) SetWindGust(v int32)`

SetWindGust sets WindGust field to given value.

### HasWindGust

`func (o *CurrentWeatherImperial) HasWindGust() bool`

HasWindGust returns a boolean if a field has been set.

### SetWindGustNil

`func (o *CurrentWeatherImperial) SetWindGustNil(b bool)`

 SetWindGustNil sets the value for WindGust to be an explicit nil

### UnsetWindGust
`func (o *CurrentWeatherImperial) UnsetWindGust()`

UnsetWindGust ensures that no value is present for WindGust, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


