# TrailMapElementOneOf1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** |  | 
**Uuid** | **string** |  | 
**Points** | **[]float64** |  | 
**Tension** | Pointer to **NullableFloat64** |  | [optional] 
**Run** | Pointer to [**NullableRun**](Run.md) |  | [optional] 

## Methods

### NewTrailMapElementOneOf1

`func NewTrailMapElementOneOf1(type_ string, uuid string, points []float64, ) *TrailMapElementOneOf1`

NewTrailMapElementOneOf1 instantiates a new TrailMapElementOneOf1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrailMapElementOneOf1WithDefaults

`func NewTrailMapElementOneOf1WithDefaults() *TrailMapElementOneOf1`

NewTrailMapElementOneOf1WithDefaults instantiates a new TrailMapElementOneOf1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *TrailMapElementOneOf1) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TrailMapElementOneOf1) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TrailMapElementOneOf1) SetType(v string)`

SetType sets Type field to given value.


### GetUuid

`func (o *TrailMapElementOneOf1) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *TrailMapElementOneOf1) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *TrailMapElementOneOf1) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetPoints

`func (o *TrailMapElementOneOf1) GetPoints() []float64`

GetPoints returns the Points field if non-nil, zero value otherwise.

### GetPointsOk

`func (o *TrailMapElementOneOf1) GetPointsOk() (*[]float64, bool)`

GetPointsOk returns a tuple with the Points field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoints

`func (o *TrailMapElementOneOf1) SetPoints(v []float64)`

SetPoints sets Points field to given value.


### GetTension

`func (o *TrailMapElementOneOf1) GetTension() float64`

GetTension returns the Tension field if non-nil, zero value otherwise.

### GetTensionOk

`func (o *TrailMapElementOneOf1) GetTensionOk() (*float64, bool)`

GetTensionOk returns a tuple with the Tension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTension

`func (o *TrailMapElementOneOf1) SetTension(v float64)`

SetTension sets Tension field to given value.

### HasTension

`func (o *TrailMapElementOneOf1) HasTension() bool`

HasTension returns a boolean if a field has been set.

### SetTensionNil

`func (o *TrailMapElementOneOf1) SetTensionNil(b bool)`

 SetTensionNil sets the value for Tension to be an explicit nil

### UnsetTension
`func (o *TrailMapElementOneOf1) UnsetTension()`

UnsetTension ensures that no value is present for Tension, not even an explicit nil
### GetRun

`func (o *TrailMapElementOneOf1) GetRun() Run`

GetRun returns the Run field if non-nil, zero value otherwise.

### GetRunOk

`func (o *TrailMapElementOneOf1) GetRunOk() (*Run, bool)`

GetRunOk returns a tuple with the Run field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRun

`func (o *TrailMapElementOneOf1) SetRun(v Run)`

SetRun sets Run field to given value.

### HasRun

`func (o *TrailMapElementOneOf1) HasRun() bool`

HasRun returns a boolean if a field has been set.

### SetRunNil

`func (o *TrailMapElementOneOf1) SetRunNil(b bool)`

 SetRunNil sets the value for Run to be an explicit nil

### UnsetRun
`func (o *TrailMapElementOneOf1) UnsetRun()`

UnsetRun ensures that no value is present for Run, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


