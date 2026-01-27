# DailyForecast

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | **string** | Date of forecast (YYYY-MM-DD format) | 
**Imperial** | [**DailyForecastImperial**](DailyForecastImperial.md) | Measurements in imperial units | 
**Metric** | [**DailyForecastMetric**](DailyForecastMetric.md) | Measurements in metric units | 
**Condition** | **string** | Human-readable condition | 
**ConditionCode** | [**WeatherConditionCode**](WeatherConditionCode.md) | Condition code | 
**PrecipitationProbability** | Pointer to **NullableInt32** | Probability of precipitation (0-100%) | [optional] 
**Sunrise** | **time.Time** | Sunrise time | 
**Sunset** | **time.Time** | Sunset time | 

## Methods

### NewDailyForecast

`func NewDailyForecast(date string, imperial DailyForecastImperial, metric DailyForecastMetric, condition string, conditionCode WeatherConditionCode, sunrise time.Time, sunset time.Time, ) *DailyForecast`

NewDailyForecast instantiates a new DailyForecast object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDailyForecastWithDefaults

`func NewDailyForecastWithDefaults() *DailyForecast`

NewDailyForecastWithDefaults instantiates a new DailyForecast object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *DailyForecast) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *DailyForecast) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *DailyForecast) SetDate(v string)`

SetDate sets Date field to given value.


### GetImperial

`func (o *DailyForecast) GetImperial() DailyForecastImperial`

GetImperial returns the Imperial field if non-nil, zero value otherwise.

### GetImperialOk

`func (o *DailyForecast) GetImperialOk() (*DailyForecastImperial, bool)`

GetImperialOk returns a tuple with the Imperial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImperial

`func (o *DailyForecast) SetImperial(v DailyForecastImperial)`

SetImperial sets Imperial field to given value.


### GetMetric

`func (o *DailyForecast) GetMetric() DailyForecastMetric`

GetMetric returns the Metric field if non-nil, zero value otherwise.

### GetMetricOk

`func (o *DailyForecast) GetMetricOk() (*DailyForecastMetric, bool)`

GetMetricOk returns a tuple with the Metric field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetric

`func (o *DailyForecast) SetMetric(v DailyForecastMetric)`

SetMetric sets Metric field to given value.


### GetCondition

`func (o *DailyForecast) GetCondition() string`

GetCondition returns the Condition field if non-nil, zero value otherwise.

### GetConditionOk

`func (o *DailyForecast) GetConditionOk() (*string, bool)`

GetConditionOk returns a tuple with the Condition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCondition

`func (o *DailyForecast) SetCondition(v string)`

SetCondition sets Condition field to given value.


### GetConditionCode

`func (o *DailyForecast) GetConditionCode() WeatherConditionCode`

GetConditionCode returns the ConditionCode field if non-nil, zero value otherwise.

### GetConditionCodeOk

`func (o *DailyForecast) GetConditionCodeOk() (*WeatherConditionCode, bool)`

GetConditionCodeOk returns a tuple with the ConditionCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConditionCode

`func (o *DailyForecast) SetConditionCode(v WeatherConditionCode)`

SetConditionCode sets ConditionCode field to given value.


### GetPrecipitationProbability

`func (o *DailyForecast) GetPrecipitationProbability() int32`

GetPrecipitationProbability returns the PrecipitationProbability field if non-nil, zero value otherwise.

### GetPrecipitationProbabilityOk

`func (o *DailyForecast) GetPrecipitationProbabilityOk() (*int32, bool)`

GetPrecipitationProbabilityOk returns a tuple with the PrecipitationProbability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrecipitationProbability

`func (o *DailyForecast) SetPrecipitationProbability(v int32)`

SetPrecipitationProbability sets PrecipitationProbability field to given value.

### HasPrecipitationProbability

`func (o *DailyForecast) HasPrecipitationProbability() bool`

HasPrecipitationProbability returns a boolean if a field has been set.

### SetPrecipitationProbabilityNil

`func (o *DailyForecast) SetPrecipitationProbabilityNil(b bool)`

 SetPrecipitationProbabilityNil sets the value for PrecipitationProbability to be an explicit nil

### UnsetPrecipitationProbability
`func (o *DailyForecast) UnsetPrecipitationProbability()`

UnsetPrecipitationProbability ensures that no value is present for PrecipitationProbability, not even an explicit nil
### GetSunrise

`func (o *DailyForecast) GetSunrise() time.Time`

GetSunrise returns the Sunrise field if non-nil, zero value otherwise.

### GetSunriseOk

`func (o *DailyForecast) GetSunriseOk() (*time.Time, bool)`

GetSunriseOk returns a tuple with the Sunrise field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSunrise

`func (o *DailyForecast) SetSunrise(v time.Time)`

SetSunrise sets Sunrise field to given value.


### GetSunset

`func (o *DailyForecast) GetSunset() time.Time`

GetSunset returns the Sunset field if non-nil, zero value otherwise.

### GetSunsetOk

`func (o *DailyForecast) GetSunsetOk() (*time.Time, bool)`

GetSunsetOk returns a tuple with the Sunset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSunset

`func (o *DailyForecast) SetSunset(v time.Time)`

SetSunset sets Sunset field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


