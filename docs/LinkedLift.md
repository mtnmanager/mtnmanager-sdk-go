# LinkedLift

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | Unique identifier for the lift. | 
**Name** | **string** | Display name of the lift. | 
**Slug** | **string** | URL-friendly name of the lift. | 
**Number** | Pointer to **NullableInt32** | Optional lift number. | [optional] 
**LiftType** | [**LiftType**](LiftType.md) | Type of lift. | 

## Methods

### NewLinkedLift

`func NewLinkedLift(uuid string, name string, slug string, liftType LiftType, ) *LinkedLift`

NewLinkedLift instantiates a new LinkedLift object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinkedLiftWithDefaults

`func NewLinkedLiftWithDefaults() *LinkedLift`

NewLinkedLiftWithDefaults instantiates a new LinkedLift object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *LinkedLift) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *LinkedLift) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *LinkedLift) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *LinkedLift) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *LinkedLift) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *LinkedLift) SetName(v string)`

SetName sets Name field to given value.


### GetSlug

`func (o *LinkedLift) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *LinkedLift) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *LinkedLift) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetNumber

`func (o *LinkedLift) GetNumber() int32`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *LinkedLift) GetNumberOk() (*int32, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *LinkedLift) SetNumber(v int32)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *LinkedLift) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### SetNumberNil

`func (o *LinkedLift) SetNumberNil(b bool)`

 SetNumberNil sets the value for Number to be an explicit nil

### UnsetNumber
`func (o *LinkedLift) UnsetNumber()`

UnsetNumber ensures that no value is present for Number, not even an explicit nil
### GetLiftType

`func (o *LinkedLift) GetLiftType() LiftType`

GetLiftType returns the LiftType field if non-nil, zero value otherwise.

### GetLiftTypeOk

`func (o *LinkedLift) GetLiftTypeOk() (*LiftType, bool)`

GetLiftTypeOk returns a tuple with the LiftType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiftType

`func (o *LinkedLift) SetLiftType(v LiftType)`

SetLiftType sets LiftType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


