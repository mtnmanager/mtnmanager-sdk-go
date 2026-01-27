# DailyForecastMetric

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TemperatureHigh** | **int32** | High temperature in Celsius | 
**TemperatureLow** | **int32** | Low temperature in Celsius | 
**SnowfallTotal** | Pointer to **NullableInt32** | Total snowfall expected in centimeters | [optional] 
**PrecipitationTotal** | Pointer to **NullableInt32** | Total precipitation expected in millimeters | [optional] 
**WindSpeedMax** | Pointer to **NullableInt32** | Maximum wind speed in km/h | [optional] 
**WindGustMax** | Pointer to **NullableInt32** | Maximum wind gust in km/h | [optional] 

## Methods

### NewDailyForecastMetric

`func NewDailyForecastMetric(temperatureHigh int32, temperatureLow int32, ) *DailyForecastMetric`

NewDailyForecastMetric instantiates a new DailyForecastMetric object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDailyForecastMetricWithDefaults

`func NewDailyForecastMetricWithDefaults() *DailyForecastMetric`

NewDailyForecastMetricWithDefaults instantiates a new DailyForecastMetric object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTemperatureHigh

`func (o *DailyForecastMetric) GetTemperatureHigh() int32`

GetTemperatureHigh returns the TemperatureHigh field if non-nil, zero value otherwise.

### GetTemperatureHighOk

`func (o *DailyForecastMetric) GetTemperatureHighOk() (*int32, bool)`

GetTemperatureHighOk returns a tuple with the TemperatureHigh field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperatureHigh

`func (o *DailyForecastMetric) SetTemperatureHigh(v int32)`

SetTemperatureHigh sets TemperatureHigh field to given value.


### GetTemperatureLow

`func (o *DailyForecastMetric) GetTemperatureLow() int32`

GetTemperatureLow returns the TemperatureLow field if non-nil, zero value otherwise.

### GetTemperatureLowOk

`func (o *DailyForecastMetric) GetTemperatureLowOk() (*int32, bool)`

GetTemperatureLowOk returns a tuple with the TemperatureLow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperatureLow

`func (o *DailyForecastMetric) SetTemperatureLow(v int32)`

SetTemperatureLow sets TemperatureLow field to given value.


### GetSnowfallTotal

`func (o *DailyForecastMetric) GetSnowfallTotal() int32`

GetSnowfallTotal returns the SnowfallTotal field if non-nil, zero value otherwise.

### GetSnowfallTotalOk

`func (o *DailyForecastMetric) GetSnowfallTotalOk() (*int32, bool)`

GetSnowfallTotalOk returns a tuple with the SnowfallTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnowfallTotal

`func (o *DailyForecastMetric) SetSnowfallTotal(v int32)`

SetSnowfallTotal sets SnowfallTotal field to given value.

### HasSnowfallTotal

`func (o *DailyForecastMetric) HasSnowfallTotal() bool`

HasSnowfallTotal returns a boolean if a field has been set.

### SetSnowfallTotalNil

`func (o *DailyForecastMetric) SetSnowfallTotalNil(b bool)`

 SetSnowfallTotalNil sets the value for SnowfallTotal to be an explicit nil

### UnsetSnowfallTotal
`func (o *DailyForecastMetric) UnsetSnowfallTotal()`

UnsetSnowfallTotal ensures that no value is present for SnowfallTotal, not even an explicit nil
### GetPrecipitationTotal

`func (o *DailyForecastMetric) GetPrecipitationTotal() int32`

GetPrecipitationTotal returns the PrecipitationTotal field if non-nil, zero value otherwise.

### GetPrecipitationTotalOk

`func (o *DailyForecastMetric) GetPrecipitationTotalOk() (*int32, bool)`

GetPrecipitationTotalOk returns a tuple with the PrecipitationTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecipitationTotal

`func (o *DailyForecastMetric) SetPrecipitationTotal(v int32)`

SetPrecipitationTotal sets PrecipitationTotal field to given value.

### HasPrecipitationTotal

`func (o *DailyForecastMetric) HasPrecipitationTotal() bool`

HasPrecipitationTotal returns a boolean if a field has been set.

### SetPrecipitationTotalNil

`func (o *DailyForecastMetric) SetPrecipitationTotalNil(b bool)`

 SetPrecipitationTotalNil sets the value for PrecipitationTotal to be an explicit nil

### UnsetPrecipitationTotal
`func (o *DailyForecastMetric) UnsetPrecipitationTotal()`

UnsetPrecipitationTotal ensures that no value is present for PrecipitationTotal, not even an explicit nil
### GetWindSpeedMax

`func (o *DailyForecastMetric) GetWindSpeedMax() int32`

GetWindSpeedMax returns the WindSpeedMax field if non-nil, zero value otherwise.

### GetWindSpeedMaxOk

`func (o *DailyForecastMetric) GetWindSpeedMaxOk() (*int32, bool)`

GetWindSpeedMaxOk returns a tuple with the WindSpeedMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindSpeedMax

`func (o *DailyForecastMetric) SetWindSpeedMax(v int32)`

SetWindSpeedMax sets WindSpeedMax field to given value.

### HasWindSpeedMax

`func (o *DailyForecastMetric) HasWindSpeedMax() bool`

HasWindSpeedMax returns a boolean if a field has been set.

### SetWindSpeedMaxNil

`func (o *DailyForecastMetric) SetWindSpeedMaxNil(b bool)`

 SetWindSpeedMaxNil sets the value for WindSpeedMax to be an explicit nil

### UnsetWindSpeedMax
`func (o *DailyForecastMetric) UnsetWindSpeedMax()`

UnsetWindSpeedMax ensures that no value is present for WindSpeedMax, not even an explicit nil
### GetWindGustMax

`func (o *DailyForecastMetric) GetWindGustMax() int32`

GetWindGustMax returns the WindGustMax field if non-nil, zero value otherwise.

### GetWindGustMaxOk

`func (o *DailyForecastMetric) GetWindGustMaxOk() (*int32, bool)`

GetWindGustMaxOk returns a tuple with the WindGustMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindGustMax

`func (o *DailyForecastMetric) SetWindGustMax(v int32)`

SetWindGustMax sets WindGustMax field to given value.

### HasWindGustMax

`func (o *DailyForecastMetric) HasWindGustMax() bool`

HasWindGustMax returns a boolean if a field has been set.

### SetWindGustMaxNil

`func (o *DailyForecastMetric) SetWindGustMaxNil(b bool)`

 SetWindGustMaxNil sets the value for WindGustMax to be an explicit nil

### UnsetWindGustMax
`func (o *DailyForecastMetric) UnsetWindGustMax()`

UnsetWindGustMax ensures that no value is present for WindGustMax, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


