# SeasonPeriod

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SeasonType** | [**SeasonType**](SeasonType.md) | The season&#39;s type (&#x60;winter&#x60; or &#x60;summer&#x60;; never &#x60;closed&#x60;). | 
**StartsOn** | **string** | The season&#39;s first day (YYYY-MM-DD), in the resort&#39;s local timezone. | 
**EndsOn** | **string** | The season&#39;s last day (YYYY-MM-DD), in the resort&#39;s local timezone. | 

## Methods

### NewSeasonPeriod

`func NewSeasonPeriod(seasonType SeasonType, startsOn string, endsOn string, ) *SeasonPeriod`

NewSeasonPeriod instantiates a new SeasonPeriod object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSeasonPeriodWithDefaults

`func NewSeasonPeriodWithDefaults() *SeasonPeriod`

NewSeasonPeriodWithDefaults instantiates a new SeasonPeriod object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSeasonType

`func (o *SeasonPeriod) GetSeasonType() SeasonType`

GetSeasonType returns the SeasonType field if non-nil, zero value otherwise.

### GetSeasonTypeOk

`func (o *SeasonPeriod) GetSeasonTypeOk() (*SeasonType, bool)`

GetSeasonTypeOk returns a tuple with the SeasonType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeasonType

`func (o *SeasonPeriod) SetSeasonType(v SeasonType)`

SetSeasonType sets SeasonType field to given value.


### GetStartsOn

`func (o *SeasonPeriod) GetStartsOn() string`

GetStartsOn returns the StartsOn field if non-nil, zero value otherwise.

### GetStartsOnOk

`func (o *SeasonPeriod) GetStartsOnOk() (*string, bool)`

GetStartsOnOk returns a tuple with the StartsOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartsOn

`func (o *SeasonPeriod) SetStartsOn(v string)`

SetStartsOn sets StartsOn field to given value.


### GetEndsOn

`func (o *SeasonPeriod) GetEndsOn() string`

GetEndsOn returns the EndsOn field if non-nil, zero value otherwise.

### GetEndsOnOk

`func (o *SeasonPeriod) GetEndsOnOk() (*string, bool)`

GetEndsOnOk returns a tuple with the EndsOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndsOn

`func (o *SeasonPeriod) SetEndsOn(v string)`

SetEndsOn sets EndsOn field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


