# TrailMapElementOneOf

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** |  | 
**Uuid** | **string** |  | 
**Points** | **[]float64** |  | 
**Tension** | Pointer to **NullableFloat64** |  | [optional] 
**Lift** | Pointer to [**NullableLift**](Lift.md) |  | [optional] 

## Methods

### NewTrailMapElementOneOf

`func NewTrailMapElementOneOf(type_ string, uuid string, points []float64, ) *TrailMapElementOneOf`

NewTrailMapElementOneOf instantiates a new TrailMapElementOneOf object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrailMapElementOneOfWithDefaults

`func NewTrailMapElementOneOfWithDefaults() *TrailMapElementOneOf`

NewTrailMapElementOneOfWithDefaults instantiates a new TrailMapElementOneOf object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *TrailMapElementOneOf) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TrailMapElementOneOf) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TrailMapElementOneOf) SetType(v string)`

SetType sets Type field to given value.


### GetUuid

`func (o *TrailMapElementOneOf) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *TrailMapElementOneOf) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *TrailMapElementOneOf) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetPoints

`func (o *TrailMapElementOneOf) GetPoints() []float64`

GetPoints returns the Points field if non-nil, zero value otherwise.

### GetPointsOk

`func (o *TrailMapElementOneOf) GetPointsOk() (*[]float64, bool)`

GetPointsOk returns a tuple with the Points field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoints

`func (o *TrailMapElementOneOf) SetPoints(v []float64)`

SetPoints sets Points field to given value.


### GetTension

`func (o *TrailMapElementOneOf) GetTension() float64`

GetTension returns the Tension field if non-nil, zero value otherwise.

### GetTensionOk

`func (o *TrailMapElementOneOf) GetTensionOk() (*float64, bool)`

GetTensionOk returns a tuple with the Tension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTension

`func (o *TrailMapElementOneOf) SetTension(v float64)`

SetTension sets Tension field to given value.

### HasTension

`func (o *TrailMapElementOneOf) HasTension() bool`

HasTension returns a boolean if a field has been set.

### SetTensionNil

`func (o *TrailMapElementOneOf) SetTensionNil(b bool)`

 SetTensionNil sets the value for Tension to be an explicit nil

### UnsetTension
`func (o *TrailMapElementOneOf) UnsetTension()`

UnsetTension ensures that no value is present for Tension, not even an explicit nil
### GetLift

`func (o *TrailMapElementOneOf) GetLift() Lift`

GetLift returns the Lift field if non-nil, zero value otherwise.

### GetLiftOk

`func (o *TrailMapElementOneOf) GetLiftOk() (*Lift, bool)`

GetLiftOk returns a tuple with the Lift field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLift

`func (o *TrailMapElementOneOf) SetLift(v Lift)`

SetLift sets Lift field to given value.

### HasLift

`func (o *TrailMapElementOneOf) HasLift() bool`

HasLift returns a boolean if a field has been set.

### SetLiftNil

`func (o *TrailMapElementOneOf) SetLiftNil(b bool)`

 SetLiftNil sets the value for Lift to be an explicit nil

### UnsetLift
`func (o *TrailMapElementOneOf) UnsetLift()`

UnsetLift ensures that no value is present for Lift, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


