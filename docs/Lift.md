# Lift

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | Unique identifier for the lift. | 
**Name** | **string** | Display name of the lift. | 
**Slug** | **string** | URL-friendly name of the lift. | 
**Number** | Pointer to **NullableInt32** | Optional lift number. | [optional] 
**LiftType** | [**LiftType**](LiftType.md) | Type of lift (e.g. gondola, quad). | 
**HighSpeed** | **bool** | Whether this is a high-speed/detachable lift. | 
**Bubble** | **bool** | Whether the lift has a bubble/cover for weather protection. | 
**Heated** | **bool** | Whether the lift has heated seats. | 
**Status** | [**LiftStatus**](LiftStatus.md) | Current operational status (open, closed, on_hold, or unknown). | 
**WaitTimeMinutes** | Pointer to **NullableInt64** | Current estimated wait time in minutes, if available. | [optional] 
**AreaUuid** | Pointer to **NullableString** | UUID of the area this lift belongs to, if assigned. | [optional] 
**AreaName** | Pointer to **NullableString** | Name of the area this lift belongs to, if assigned. | [optional] 
**AreaDisplayOrder** | Pointer to **NullableInt32** | Display order of the area this lift belongs to, if assigned, for sorting purposes. | [optional] 
**UpdatedAt** | **time.Time** | When this lift&#39;s information was last updated. | 

## Methods

### NewLift

`func NewLift(uuid string, name string, slug string, liftType LiftType, highSpeed bool, bubble bool, heated bool, status LiftStatus, updatedAt time.Time, ) *Lift`

NewLift instantiates a new Lift object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLiftWithDefaults

`func NewLiftWithDefaults() *Lift`

NewLiftWithDefaults instantiates a new Lift object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *Lift) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *Lift) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *Lift) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *Lift) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Lift) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Lift) SetName(v string)`

SetName sets Name field to given value.


### GetSlug

`func (o *Lift) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *Lift) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *Lift) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetNumber

`func (o *Lift) GetNumber() int32`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *Lift) GetNumberOk() (*int32, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *Lift) SetNumber(v int32)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *Lift) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### SetNumberNil

`func (o *Lift) SetNumberNil(b bool)`

 SetNumberNil sets the value for Number to be an explicit nil

### UnsetNumber
`func (o *Lift) UnsetNumber()`

UnsetNumber ensures that no value is present for Number, not even an explicit nil
### GetLiftType

`func (o *Lift) GetLiftType() LiftType`

GetLiftType returns the LiftType field if non-nil, zero value otherwise.

### GetLiftTypeOk

`func (o *Lift) GetLiftTypeOk() (*LiftType, bool)`

GetLiftTypeOk returns a tuple with the LiftType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiftType

`func (o *Lift) SetLiftType(v LiftType)`

SetLiftType sets LiftType field to given value.


### GetHighSpeed

`func (o *Lift) GetHighSpeed() bool`

GetHighSpeed returns the HighSpeed field if non-nil, zero value otherwise.

### GetHighSpeedOk

`func (o *Lift) GetHighSpeedOk() (*bool, bool)`

GetHighSpeedOk returns a tuple with the HighSpeed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHighSpeed

`func (o *Lift) SetHighSpeed(v bool)`

SetHighSpeed sets HighSpeed field to given value.


### GetBubble

`func (o *Lift) GetBubble() bool`

GetBubble returns the Bubble field if non-nil, zero value otherwise.

### GetBubbleOk

`func (o *Lift) GetBubbleOk() (*bool, bool)`

GetBubbleOk returns a tuple with the Bubble field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBubble

`func (o *Lift) SetBubble(v bool)`

SetBubble sets Bubble field to given value.


### GetHeated

`func (o *Lift) GetHeated() bool`

GetHeated returns the Heated field if non-nil, zero value otherwise.

### GetHeatedOk

`func (o *Lift) GetHeatedOk() (*bool, bool)`

GetHeatedOk returns a tuple with the Heated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeated

`func (o *Lift) SetHeated(v bool)`

SetHeated sets Heated field to given value.


### GetStatus

`func (o *Lift) GetStatus() LiftStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Lift) GetStatusOk() (*LiftStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Lift) SetStatus(v LiftStatus)`

SetStatus sets Status field to given value.


### GetWaitTimeMinutes

`func (o *Lift) GetWaitTimeMinutes() int64`

GetWaitTimeMinutes returns the WaitTimeMinutes field if non-nil, zero value otherwise.

### GetWaitTimeMinutesOk

`func (o *Lift) GetWaitTimeMinutesOk() (*int64, bool)`

GetWaitTimeMinutesOk returns a tuple with the WaitTimeMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWaitTimeMinutes

`func (o *Lift) SetWaitTimeMinutes(v int64)`

SetWaitTimeMinutes sets WaitTimeMinutes field to given value.

### HasWaitTimeMinutes

`func (o *Lift) HasWaitTimeMinutes() bool`

HasWaitTimeMinutes returns a boolean if a field has been set.

### SetWaitTimeMinutesNil

`func (o *Lift) SetWaitTimeMinutesNil(b bool)`

 SetWaitTimeMinutesNil sets the value for WaitTimeMinutes to be an explicit nil

### UnsetWaitTimeMinutes
`func (o *Lift) UnsetWaitTimeMinutes()`

UnsetWaitTimeMinutes ensures that no value is present for WaitTimeMinutes, not even an explicit nil
### GetAreaUuid

`func (o *Lift) GetAreaUuid() string`

GetAreaUuid returns the AreaUuid field if non-nil, zero value otherwise.

### GetAreaUuidOk

`func (o *Lift) GetAreaUuidOk() (*string, bool)`

GetAreaUuidOk returns a tuple with the AreaUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaUuid

`func (o *Lift) SetAreaUuid(v string)`

SetAreaUuid sets AreaUuid field to given value.

### HasAreaUuid

`func (o *Lift) HasAreaUuid() bool`

HasAreaUuid returns a boolean if a field has been set.

### SetAreaUuidNil

`func (o *Lift) SetAreaUuidNil(b bool)`

 SetAreaUuidNil sets the value for AreaUuid to be an explicit nil

### UnsetAreaUuid
`func (o *Lift) UnsetAreaUuid()`

UnsetAreaUuid ensures that no value is present for AreaUuid, not even an explicit nil
### GetAreaName

`func (o *Lift) GetAreaName() string`

GetAreaName returns the AreaName field if non-nil, zero value otherwise.

### GetAreaNameOk

`func (o *Lift) GetAreaNameOk() (*string, bool)`

GetAreaNameOk returns a tuple with the AreaName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaName

`func (o *Lift) SetAreaName(v string)`

SetAreaName sets AreaName field to given value.

### HasAreaName

`func (o *Lift) HasAreaName() bool`

HasAreaName returns a boolean if a field has been set.

### SetAreaNameNil

`func (o *Lift) SetAreaNameNil(b bool)`

 SetAreaNameNil sets the value for AreaName to be an explicit nil

### UnsetAreaName
`func (o *Lift) UnsetAreaName()`

UnsetAreaName ensures that no value is present for AreaName, not even an explicit nil
### GetAreaDisplayOrder

`func (o *Lift) GetAreaDisplayOrder() int32`

GetAreaDisplayOrder returns the AreaDisplayOrder field if non-nil, zero value otherwise.

### GetAreaDisplayOrderOk

`func (o *Lift) GetAreaDisplayOrderOk() (*int32, bool)`

GetAreaDisplayOrderOk returns a tuple with the AreaDisplayOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaDisplayOrder

`func (o *Lift) SetAreaDisplayOrder(v int32)`

SetAreaDisplayOrder sets AreaDisplayOrder field to given value.

### HasAreaDisplayOrder

`func (o *Lift) HasAreaDisplayOrder() bool`

HasAreaDisplayOrder returns a boolean if a field has been set.

### SetAreaDisplayOrderNil

`func (o *Lift) SetAreaDisplayOrderNil(b bool)`

 SetAreaDisplayOrderNil sets the value for AreaDisplayOrder to be an explicit nil

### UnsetAreaDisplayOrder
`func (o *Lift) UnsetAreaDisplayOrder()`

UnsetAreaDisplayOrder ensures that no value is present for AreaDisplayOrder, not even an explicit nil
### GetUpdatedAt

`func (o *Lift) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Lift) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Lift) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


