# TerrainPark

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | Unique identifier for the terrain park. | 
**Name** | **string** | Display name of the terrain park. | 
**Slug** | **string** | URL-friendly name of the terrain park. | 
**Number** | Pointer to **NullableInt32** | Optional terrain park number. | [optional] 
**Status** | [**TerrainParkStatus**](TerrainParkStatus.md) | Current operational status (open, closed, or unknown). | 
**ConditionNotes** | **string** | Notes about current conditions in this terrain park. | 
**AreaUuid** | Pointer to **NullableString** | UUID of the area this terrain park belongs to, if assigned. | [optional] 
**AreaName** | Pointer to **NullableString** | Name of the area this terrain park belongs to, if assigned. | [optional] 
**AreaDisplayOrder** | Pointer to **NullableInt32** | Display order of the area this terrain park belongs to, if assigned, for sorting purposes. | [optional] 
**Features** | [**[]TerrainParkFeature**](TerrainParkFeature.md) | Features within this terrain park (jumps, boxes, rails, etc.). | 
**UpdatedAt** | **time.Time** | When this terrain park or any of its features was last updated. | 

## Methods

### NewTerrainPark

`func NewTerrainPark(uuid string, name string, slug string, status TerrainParkStatus, conditionNotes string, features []TerrainParkFeature, updatedAt time.Time, ) *TerrainPark`

NewTerrainPark instantiates a new TerrainPark object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTerrainParkWithDefaults

`func NewTerrainParkWithDefaults() *TerrainPark`

NewTerrainParkWithDefaults instantiates a new TerrainPark object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *TerrainPark) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *TerrainPark) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *TerrainPark) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *TerrainPark) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TerrainPark) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TerrainPark) SetName(v string)`

SetName sets Name field to given value.


### GetSlug

`func (o *TerrainPark) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *TerrainPark) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *TerrainPark) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetNumber

`func (o *TerrainPark) GetNumber() int32`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *TerrainPark) GetNumberOk() (*int32, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *TerrainPark) SetNumber(v int32)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *TerrainPark) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### SetNumberNil

`func (o *TerrainPark) SetNumberNil(b bool)`

 SetNumberNil sets the value for Number to be an explicit nil

### UnsetNumber
`func (o *TerrainPark) UnsetNumber()`

UnsetNumber ensures that no value is present for Number, not even an explicit nil
### GetStatus

`func (o *TerrainPark) GetStatus() TerrainParkStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TerrainPark) GetStatusOk() (*TerrainParkStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TerrainPark) SetStatus(v TerrainParkStatus)`

SetStatus sets Status field to given value.


### GetConditionNotes

`func (o *TerrainPark) GetConditionNotes() string`

GetConditionNotes returns the ConditionNotes field if non-nil, zero value otherwise.

### GetConditionNotesOk

`func (o *TerrainPark) GetConditionNotesOk() (*string, bool)`

GetConditionNotesOk returns a tuple with the ConditionNotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConditionNotes

`func (o *TerrainPark) SetConditionNotes(v string)`

SetConditionNotes sets ConditionNotes field to given value.


### GetAreaUuid

`func (o *TerrainPark) GetAreaUuid() string`

GetAreaUuid returns the AreaUuid field if non-nil, zero value otherwise.

### GetAreaUuidOk

`func (o *TerrainPark) GetAreaUuidOk() (*string, bool)`

GetAreaUuidOk returns a tuple with the AreaUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaUuid

`func (o *TerrainPark) SetAreaUuid(v string)`

SetAreaUuid sets AreaUuid field to given value.

### HasAreaUuid

`func (o *TerrainPark) HasAreaUuid() bool`

HasAreaUuid returns a boolean if a field has been set.

### SetAreaUuidNil

`func (o *TerrainPark) SetAreaUuidNil(b bool)`

 SetAreaUuidNil sets the value for AreaUuid to be an explicit nil

### UnsetAreaUuid
`func (o *TerrainPark) UnsetAreaUuid()`

UnsetAreaUuid ensures that no value is present for AreaUuid, not even an explicit nil
### GetAreaName

`func (o *TerrainPark) GetAreaName() string`

GetAreaName returns the AreaName field if non-nil, zero value otherwise.

### GetAreaNameOk

`func (o *TerrainPark) GetAreaNameOk() (*string, bool)`

GetAreaNameOk returns a tuple with the AreaName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaName

`func (o *TerrainPark) SetAreaName(v string)`

SetAreaName sets AreaName field to given value.

### HasAreaName

`func (o *TerrainPark) HasAreaName() bool`

HasAreaName returns a boolean if a field has been set.

### SetAreaNameNil

`func (o *TerrainPark) SetAreaNameNil(b bool)`

 SetAreaNameNil sets the value for AreaName to be an explicit nil

### UnsetAreaName
`func (o *TerrainPark) UnsetAreaName()`

UnsetAreaName ensures that no value is present for AreaName, not even an explicit nil
### GetAreaDisplayOrder

`func (o *TerrainPark) GetAreaDisplayOrder() int32`

GetAreaDisplayOrder returns the AreaDisplayOrder field if non-nil, zero value otherwise.

### GetAreaDisplayOrderOk

`func (o *TerrainPark) GetAreaDisplayOrderOk() (*int32, bool)`

GetAreaDisplayOrderOk returns a tuple with the AreaDisplayOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaDisplayOrder

`func (o *TerrainPark) SetAreaDisplayOrder(v int32)`

SetAreaDisplayOrder sets AreaDisplayOrder field to given value.

### HasAreaDisplayOrder

`func (o *TerrainPark) HasAreaDisplayOrder() bool`

HasAreaDisplayOrder returns a boolean if a field has been set.

### SetAreaDisplayOrderNil

`func (o *TerrainPark) SetAreaDisplayOrderNil(b bool)`

 SetAreaDisplayOrderNil sets the value for AreaDisplayOrder to be an explicit nil

### UnsetAreaDisplayOrder
`func (o *TerrainPark) UnsetAreaDisplayOrder()`

UnsetAreaDisplayOrder ensures that no value is present for AreaDisplayOrder, not even an explicit nil
### GetFeatures

`func (o *TerrainPark) GetFeatures() []TerrainParkFeature`

GetFeatures returns the Features field if non-nil, zero value otherwise.

### GetFeaturesOk

`func (o *TerrainPark) GetFeaturesOk() (*[]TerrainParkFeature, bool)`

GetFeaturesOk returns a tuple with the Features field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatures

`func (o *TerrainPark) SetFeatures(v []TerrainParkFeature)`

SetFeatures sets Features field to given value.


### GetUpdatedAt

`func (o *TerrainPark) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *TerrainPark) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *TerrainPark) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


