# HourlyForecast

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Timestamp** | **time.Time** | Forecast timestamp | 
**Imperial** | [**HourlyForecastImperial**](HourlyForecastImperial.md) | Measurements in imperial units | 
**Metric** | [**HourlyForecastMetric**](HourlyForecastMetric.md) | Measurements in metric units | 
**Condition** | **string** | Human-readable condition | 
**ConditionCode** | [**WeatherConditionCode**](WeatherConditionCode.md) | Weather condition code | 
**PrecipitationProbability** | Pointer to **NullableInt32** | Probability of precipitation (0-100%) | [optional] 

## Methods

### NewHourlyForecast

`func NewHourlyForecast(timestamp time.Time, imperial HourlyForecastImperial, metric HourlyForecastMetric, condition string, conditionCode WeatherConditionCode, ) *HourlyForecast`

NewHourlyForecast instantiates a new HourlyForecast object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHourlyForecastWithDefaults

`func NewHourlyForecastWithDefaults() *HourlyForecast`

NewHourlyForecastWithDefaults instantiates a new HourlyForecast object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTimestamp

`func (o *HourlyForecast) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *HourlyForecast) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *HourlyForecast) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.


### GetImperial

`func (o *HourlyForecast) GetImperial() HourlyForecastImperial`

GetImperial returns the Imperial field if non-nil, zero value otherwise.

### GetImperialOk

`func (o *HourlyForecast) GetImperialOk() (*HourlyForecastImperial, bool)`

GetImperialOk returns a tuple with the Imperial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImperial

`func (o *HourlyForecast) SetImperial(v HourlyForecastImperial)`

SetImperial sets Imperial field to given value.


### GetMetric

`func (o *HourlyForecast) GetMetric() HourlyForecastMetric`

GetMetric returns the Metric field if non-nil, zero value otherwise.

### GetMetricOk

`func (o *HourlyForecast) GetMetricOk() (*HourlyForecastMetric, bool)`

GetMetricOk returns a tuple with the Metric field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetric

`func (o *HourlyForecast) SetMetric(v HourlyForecastMetric)`

SetMetric sets Metric field to given value.


### GetCondition

`func (o *HourlyForecast) GetCondition() string`

GetCondition returns the Condition field if non-nil, zero value otherwise.

### GetConditionOk

`func (o *HourlyForecast) GetConditionOk() (*string, bool)`

GetConditionOk returns a tuple with the Condition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCondition

`func (o *HourlyForecast) SetCondition(v string)`

SetCondition sets Condition field to given value.


### GetConditionCode

`func (o *HourlyForecast) GetConditionCode() WeatherConditionCode`

GetConditionCode returns the ConditionCode field if non-nil, zero value otherwise.

### GetConditionCodeOk

`func (o *HourlyForecast) GetConditionCodeOk() (*WeatherConditionCode, bool)`

GetConditionCodeOk returns a tuple with the ConditionCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConditionCode

`func (o *HourlyForecast) SetConditionCode(v WeatherConditionCode)`

SetConditionCode sets ConditionCode field to given value.


### GetPrecipitationProbability

`func (o *HourlyForecast) GetPrecipitationProbability() int32`

GetPrecipitationProbability returns the PrecipitationProbability field if non-nil, zero value otherwise.

### GetPrecipitationProbabilityOk

`func (o *HourlyForecast) GetPrecipitationProbabilityOk() (*int32, bool)`

GetPrecipitationProbabilityOk returns a tuple with the PrecipitationProbability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecipitationProbability

`func (o *HourlyForecast) SetPrecipitationProbability(v int32)`

SetPrecipitationProbability sets PrecipitationProbability field to given value.

### HasPrecipitationProbability

`func (o *HourlyForecast) HasPrecipitationProbability() bool`

HasPrecipitationProbability returns a boolean if a field has been set.

### SetPrecipitationProbabilityNil

`func (o *HourlyForecast) SetPrecipitationProbabilityNil(b bool)`

 SetPrecipitationProbabilityNil sets the value for PrecipitationProbability to be an explicit nil

### UnsetPrecipitationProbability
`func (o *HourlyForecast) UnsetPrecipitationProbability()`

UnsetPrecipitationProbability ensures that no value is present for PrecipitationProbability, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


