# DailyForecastImperial

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TemperatureHigh** | **int32** | High temperature in Fahrenheit | 
**TemperatureLow** | **int32** | Low temperature in Fahrenheit | 
**SnowfallTotal** | Pointer to **NullableInt32** | Total snowfall expected in inches | [optional] 
**PrecipitationTotal** | Pointer to **NullableInt32** | Total precipitation expected in inches | [optional] 
**WindSpeedMax** | Pointer to **NullableInt32** | Maximum wind speed in mph | [optional] 
**WindGustMax** | Pointer to **NullableInt32** | Maximum wind gust in mph | [optional] 

## Methods

### NewDailyForecastImperial

`func NewDailyForecastImperial(temperatureHigh int32, temperatureLow int32, ) *DailyForecastImperial`

NewDailyForecastImperial instantiates a new DailyForecastImperial object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDailyForecastImperialWithDefaults

`func NewDailyForecastImperialWithDefaults() *DailyForecastImperial`

NewDailyForecastImperialWithDefaults instantiates a new DailyForecastImperial object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTemperatureHigh

`func (o *DailyForecastImperial) GetTemperatureHigh() int32`

GetTemperatureHigh returns the TemperatureHigh field if non-nil, zero value otherwise.

### GetTemperatureHighOk

`func (o *DailyForecastImperial) GetTemperatureHighOk() (*int32, bool)`

GetTemperatureHighOk returns a tuple with the TemperatureHigh field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperatureHigh

`func (o *DailyForecastImperial) SetTemperatureHigh(v int32)`

SetTemperatureHigh sets TemperatureHigh field to given value.


### GetTemperatureLow

`func (o *DailyForecastImperial) GetTemperatureLow() int32`

GetTemperatureLow returns the TemperatureLow field if non-nil, zero value otherwise.

### GetTemperatureLowOk

`func (o *DailyForecastImperial) GetTemperatureLowOk() (*int32, bool)`

GetTemperatureLowOk returns a tuple with the TemperatureLow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperatureLow

`func (o *DailyForecastImperial) SetTemperatureLow(v int32)`

SetTemperatureLow sets TemperatureLow field to given value.


### GetSnowfallTotal

`func (o *DailyForecastImperial) GetSnowfallTotal() int32`

GetSnowfallTotal returns the SnowfallTotal field if non-nil, zero value otherwise.

### GetSnowfallTotalOk

`func (o *DailyForecastImperial) GetSnowfallTotalOk() (*int32, bool)`

GetSnowfallTotalOk returns a tuple with the SnowfallTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnowfallTotal

`func (o *DailyForecastImperial) SetSnowfallTotal(v int32)`

SetSnowfallTotal sets SnowfallTotal field to given value.

### HasSnowfallTotal

`func (o *DailyForecastImperial) HasSnowfallTotal() bool`

HasSnowfallTotal returns a boolean if a field has been set.

### SetSnowfallTotalNil

`func (o *DailyForecastImperial) SetSnowfallTotalNil(b bool)`

 SetSnowfallTotalNil sets the value for SnowfallTotal to be an explicit nil

### UnsetSnowfallTotal
`func (o *DailyForecastImperial) UnsetSnowfallTotal()`

UnsetSnowfallTotal ensures that no value is present for SnowfallTotal, not even an explicit nil
### GetPrecipitationTotal

`func (o *DailyForecastImperial) GetPrecipitationTotal() int32`

GetPrecipitationTotal returns the PrecipitationTotal field if non-nil, zero value otherwise.

### GetPrecipitationTotalOk

`func (o *DailyForecastImperial) GetPrecipitationTotalOk() (*int32, bool)`

GetPrecipitationTotalOk returns a tuple with the PrecipitationTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecipitationTotal

`func (o *DailyForecastImperial) SetPrecipitationTotal(v int32)`

SetPrecipitationTotal sets PrecipitationTotal field to given value.

### HasPrecipitationTotal

`func (o *DailyForecastImperial) HasPrecipitationTotal() bool`

HasPrecipitationTotal returns a boolean if a field has been set.

### SetPrecipitationTotalNil

`func (o *DailyForecastImperial) SetPrecipitationTotalNil(b bool)`

 SetPrecipitationTotalNil sets the value for PrecipitationTotal to be an explicit nil

### UnsetPrecipitationTotal
`func (o *DailyForecastImperial) UnsetPrecipitationTotal()`

UnsetPrecipitationTotal ensures that no value is present for PrecipitationTotal, not even an explicit nil
### GetWindSpeedMax

`func (o *DailyForecastImperial) GetWindSpeedMax() int32`

GetWindSpeedMax returns the WindSpeedMax field if non-nil, zero value otherwise.

### GetWindSpeedMaxOk

`func (o *DailyForecastImperial) GetWindSpeedMaxOk() (*int32, bool)`

GetWindSpeedMaxOk returns a tuple with the WindSpeedMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindSpeedMax

`func (o *DailyForecastImperial) SetWindSpeedMax(v int32)`

SetWindSpeedMax sets WindSpeedMax field to given value.

### HasWindSpeedMax

`func (o *DailyForecastImperial) HasWindSpeedMax() bool`

HasWindSpeedMax returns a boolean if a field has been set.

### SetWindSpeedMaxNil

`func (o *DailyForecastImperial) SetWindSpeedMaxNil(b bool)`

 SetWindSpeedMaxNil sets the value for WindSpeedMax to be an explicit nil

### UnsetWindSpeedMax
`func (o *DailyForecastImperial) UnsetWindSpeedMax()`

UnsetWindSpeedMax ensures that no value is present for WindSpeedMax, not even an explicit nil
### GetWindGustMax

`func (o *DailyForecastImperial) GetWindGustMax() int32`

GetWindGustMax returns the WindGustMax field if non-nil, zero value otherwise.

### GetWindGustMaxOk

`func (o *DailyForecastImperial) GetWindGustMaxOk() (*int32, bool)`

GetWindGustMaxOk returns a tuple with the WindGustMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindGustMax

`func (o *DailyForecastImperial) SetWindGustMax(v int32)`

SetWindGustMax sets WindGustMax field to given value.

### HasWindGustMax

`func (o *DailyForecastImperial) HasWindGustMax() bool`

HasWindGustMax returns a boolean if a field has been set.

### SetWindGustMaxNil

`func (o *DailyForecastImperial) SetWindGustMaxNil(b bool)`

 SetWindGustMaxNil sets the value for WindGustMax to be an explicit nil

### UnsetWindGustMax
`func (o *DailyForecastImperial) UnsetWindGustMax()`

UnsetWindGustMax ensures that no value is present for WindGustMax, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


