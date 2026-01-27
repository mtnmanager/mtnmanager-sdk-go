# CurrentWeather

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Imperial** | [**CurrentWeatherImperial**](CurrentWeatherImperial.md) | Measurements in imperial units | 
**Metric** | [**CurrentWeatherMetric**](CurrentWeatherMetric.md) | Measurements in metric units | 
**Condition** | **string** | Human-readable weather condition | 
**ConditionCode** | [**WeatherConditionCode**](WeatherConditionCode.md) | Weather condition code | 
**WindDirection** | Pointer to **NullableInt32** | Wind direction in degrees (0-360) | [optional] 
**WindDirectionCardinal** | Pointer to **NullableString** | Wind direction as cardinal direction (N, NE, E, SE, S, SW, W, NW) | [optional] 
**Timestamp** | **time.Time** | Timestamp of observation | 

## Methods

### NewCurrentWeather

`func NewCurrentWeather(imperial CurrentWeatherImperial, metric CurrentWeatherMetric, condition string, conditionCode WeatherConditionCode, timestamp time.Time, ) *CurrentWeather`

NewCurrentWeather instantiates a new CurrentWeather object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCurrentWeatherWithDefaults

`func NewCurrentWeatherWithDefaults() *CurrentWeather`

NewCurrentWeatherWithDefaults instantiates a new CurrentWeather object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImperial

`func (o *CurrentWeather) GetImperial() CurrentWeatherImperial`

GetImperial returns the Imperial field if non-nil, zero value otherwise.

### GetImperialOk

`func (o *CurrentWeather) GetImperialOk() (*CurrentWeatherImperial, bool)`

GetImperialOk returns a tuple with the Imperial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImperial

`func (o *CurrentWeather) SetImperial(v CurrentWeatherImperial)`

SetImperial sets Imperial field to given value.


### GetMetric

`func (o *CurrentWeather) GetMetric() CurrentWeatherMetric`

GetMetric returns the Metric field if non-nil, zero value otherwise.

### GetMetricOk

`func (o *CurrentWeather) GetMetricOk() (*CurrentWeatherMetric, bool)`

GetMetricOk returns a tuple with the Metric field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetric

`func (o *CurrentWeather) SetMetric(v CurrentWeatherMetric)`

SetMetric sets Metric field to given value.


### GetCondition

`func (o *CurrentWeather) GetCondition() string`

GetCondition returns the Condition field if non-nil, zero value otherwise.

### GetConditionOk

`func (o *CurrentWeather) GetConditionOk() (*string, bool)`

GetConditionOk returns a tuple with the Condition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCondition

`func (o *CurrentWeather) SetCondition(v string)`

SetCondition sets Condition field to given value.


### GetConditionCode

`func (o *CurrentWeather) GetConditionCode() WeatherConditionCode`

GetConditionCode returns the ConditionCode field if non-nil, zero value otherwise.

### GetConditionCodeOk

`func (o *CurrentWeather) GetConditionCodeOk() (*WeatherConditionCode, bool)`

GetConditionCodeOk returns a tuple with the ConditionCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConditionCode

`func (o *CurrentWeather) SetConditionCode(v WeatherConditionCode)`

SetConditionCode sets ConditionCode field to given value.


### GetWindDirection

`func (o *CurrentWeather) GetWindDirection() int32`

GetWindDirection returns the WindDirection field if non-nil, zero value otherwise.

### GetWindDirectionOk

`func (o *CurrentWeather) GetWindDirectionOk() (*int32, bool)`

GetWindDirectionOk returns a tuple with the WindDirection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindDirection

`func (o *CurrentWeather) SetWindDirection(v int32)`

SetWindDirection sets WindDirection field to given value.

### HasWindDirection

`func (o *CurrentWeather) HasWindDirection() bool`

HasWindDirection returns a boolean if a field has been set.

### SetWindDirectionNil

`func (o *CurrentWeather) SetWindDirectionNil(b bool)`

 SetWindDirectionNil sets the value for WindDirection to be an explicit nil

### UnsetWindDirection
`func (o *CurrentWeather) UnsetWindDirection()`

UnsetWindDirection ensures that no value is present for WindDirection, not even an explicit nil
### GetWindDirectionCardinal

`func (o *CurrentWeather) GetWindDirectionCardinal() string`

GetWindDirectionCardinal returns the WindDirectionCardinal field if non-nil, zero value otherwise.

### GetWindDirectionCardinalOk

`func (o *CurrentWeather) GetWindDirectionCardinalOk() (*string, bool)`

GetWindDirectionCardinalOk returns a tuple with the WindDirectionCardinal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindDirectionCardinal

`func (o *CurrentWeather) SetWindDirectionCardinal(v string)`

SetWindDirectionCardinal sets WindDirectionCardinal field to given value.

### HasWindDirectionCardinal

`func (o *CurrentWeather) HasWindDirectionCardinal() bool`

HasWindDirectionCardinal returns a boolean if a field has been set.

### SetWindDirectionCardinalNil

`func (o *CurrentWeather) SetWindDirectionCardinalNil(b bool)`

 SetWindDirectionCardinalNil sets the value for WindDirectionCardinal to be an explicit nil

### UnsetWindDirectionCardinal
`func (o *CurrentWeather) UnsetWindDirectionCardinal()`

UnsetWindDirectionCardinal ensures that no value is present for WindDirectionCardinal, not even an explicit nil
### GetTimestamp

`func (o *CurrentWeather) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *CurrentWeather) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *CurrentWeather) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


