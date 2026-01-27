# SummerTrail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | Unique identifier for the trail. | 
**Name** | **string** | Display name of the trail. | 
**Slug** | **string** | URL-friendly name of the trail. | 
**Number** | Pointer to **NullableInt32** | Optional trail number. | [optional] 
**TrailType** | [**[]SummerTrailType**](SummerTrailType.md) | Type of trail activity (e.g. hiking, mountain_biking). Can have multiple. | 
**Difficulty** | Pointer to [**NullableSummerTrailDifficulty**](SummerTrailDifficulty.md) |  | [optional] 
**Status** | [**SummerTrailStatus**](SummerTrailStatus.md) | Current operational status (open, closed, or unknown). | 
**ConditionNotes** | **string** | Notes about current conditions on this trail. | 
**AreaUuid** | Pointer to **NullableString** | UUID of the area this trail belongs to, if assigned. | [optional] 
**AreaName** | Pointer to **NullableString** | Name of the area this trail belongs to, if assigned. | [optional] 
**AreaDisplayOrder** | Pointer to **NullableInt32** | Display order of the area this trail belongs to, if assigned, for sorting purposes. | [optional] 
**UpdatedAt** | **time.Time** | When this trail&#39;s information was last updated. | 

## Methods

### NewSummerTrail

`func NewSummerTrail(uuid string, name string, slug string, trailType []SummerTrailType, status SummerTrailStatus, conditionNotes string, updatedAt time.Time, ) *SummerTrail`

NewSummerTrail instantiates a new SummerTrail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSummerTrailWithDefaults

`func NewSummerTrailWithDefaults() *SummerTrail`

NewSummerTrailWithDefaults instantiates a new SummerTrail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *SummerTrail) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *SummerTrail) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *SummerTrail) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *SummerTrail) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SummerTrail) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SummerTrail) SetName(v string)`

SetName sets Name field to given value.


### GetSlug

`func (o *SummerTrail) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *SummerTrail) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *SummerTrail) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetNumber

`func (o *SummerTrail) GetNumber() int32`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *SummerTrail) GetNumberOk() (*int32, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *SummerTrail) SetNumber(v int32)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *SummerTrail) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### SetNumberNil

`func (o *SummerTrail) SetNumberNil(b bool)`

 SetNumberNil sets the value for Number to be an explicit nil

### UnsetNumber
`func (o *SummerTrail) UnsetNumber()`

UnsetNumber ensures that no value is present for Number, not even an explicit nil
### GetTrailType

`func (o *SummerTrail) GetTrailType() []SummerTrailType`

GetTrailType returns the TrailType field if non-nil, zero value otherwise.

### GetTrailTypeOk

`func (o *SummerTrail) GetTrailTypeOk() (*[]SummerTrailType, bool)`

GetTrailTypeOk returns a tuple with the TrailType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrailType

`func (o *SummerTrail) SetTrailType(v []SummerTrailType)`

SetTrailType sets TrailType field to given value.


### GetDifficulty

`func (o *SummerTrail) GetDifficulty() SummerTrailDifficulty`

GetDifficulty returns the Difficulty field if non-nil, zero value otherwise.

### GetDifficultyOk

`func (o *SummerTrail) GetDifficultyOk() (*SummerTrailDifficulty, bool)`

GetDifficultyOk returns a tuple with the Difficulty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDifficulty

`func (o *SummerTrail) SetDifficulty(v SummerTrailDifficulty)`

SetDifficulty sets Difficulty field to given value.

### HasDifficulty

`func (o *SummerTrail) HasDifficulty() bool`

HasDifficulty returns a boolean if a field has been set.

### SetDifficultyNil

`func (o *SummerTrail) SetDifficultyNil(b bool)`

 SetDifficultyNil sets the value for Difficulty to be an explicit nil

### UnsetDifficulty
`func (o *SummerTrail) UnsetDifficulty()`

UnsetDifficulty ensures that no value is present for Difficulty, not even an explicit nil
### GetStatus

`func (o *SummerTrail) GetStatus() SummerTrailStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SummerTrail) GetStatusOk() (*SummerTrailStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SummerTrail) SetStatus(v SummerTrailStatus)`

SetStatus sets Status field to given value.


### GetConditionNotes

`func (o *SummerTrail) GetConditionNotes() string`

GetConditionNotes returns the ConditionNotes field if non-nil, zero value otherwise.

### GetConditionNotesOk

`func (o *SummerTrail) GetConditionNotesOk() (*string, bool)`

GetConditionNotesOk returns a tuple with the ConditionNotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConditionNotes

`func (o *SummerTrail) SetConditionNotes(v string)`

SetConditionNotes sets ConditionNotes field to given value.


### GetAreaUuid

`func (o *SummerTrail) GetAreaUuid() string`

GetAreaUuid returns the AreaUuid field if non-nil, zero value otherwise.

### GetAreaUuidOk

`func (o *SummerTrail) GetAreaUuidOk() (*string, bool)`

GetAreaUuidOk returns a tuple with the AreaUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaUuid

`func (o *SummerTrail) SetAreaUuid(v string)`

SetAreaUuid sets AreaUuid field to given value.

### HasAreaUuid

`func (o *SummerTrail) HasAreaUuid() bool`

HasAreaUuid returns a boolean if a field has been set.

### SetAreaUuidNil

`func (o *SummerTrail) SetAreaUuidNil(b bool)`

 SetAreaUuidNil sets the value for AreaUuid to be an explicit nil

### UnsetAreaUuid
`func (o *SummerTrail) UnsetAreaUuid()`

UnsetAreaUuid ensures that no value is present for AreaUuid, not even an explicit nil
### GetAreaName

`func (o *SummerTrail) GetAreaName() string`

GetAreaName returns the AreaName field if non-nil, zero value otherwise.

### GetAreaNameOk

`func (o *SummerTrail) GetAreaNameOk() (*string, bool)`

GetAreaNameOk returns a tuple with the AreaName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaName

`func (o *SummerTrail) SetAreaName(v string)`

SetAreaName sets AreaName field to given value.

### HasAreaName

`func (o *SummerTrail) HasAreaName() bool`

HasAreaName returns a boolean if a field has been set.

### SetAreaNameNil

`func (o *SummerTrail) SetAreaNameNil(b bool)`

 SetAreaNameNil sets the value for AreaName to be an explicit nil

### UnsetAreaName
`func (o *SummerTrail) UnsetAreaName()`

UnsetAreaName ensures that no value is present for AreaName, not even an explicit nil
### GetAreaDisplayOrder

`func (o *SummerTrail) GetAreaDisplayOrder() int32`

GetAreaDisplayOrder returns the AreaDisplayOrder field if non-nil, zero value otherwise.

### GetAreaDisplayOrderOk

`func (o *SummerTrail) GetAreaDisplayOrderOk() (*int32, bool)`

GetAreaDisplayOrderOk returns a tuple with the AreaDisplayOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaDisplayOrder

`func (o *SummerTrail) SetAreaDisplayOrder(v int32)`

SetAreaDisplayOrder sets AreaDisplayOrder field to given value.

### HasAreaDisplayOrder

`func (o *SummerTrail) HasAreaDisplayOrder() bool`

HasAreaDisplayOrder returns a boolean if a field has been set.

### SetAreaDisplayOrderNil

`func (o *SummerTrail) SetAreaDisplayOrderNil(b bool)`

 SetAreaDisplayOrderNil sets the value for AreaDisplayOrder to be an explicit nil

### UnsetAreaDisplayOrder
`func (o *SummerTrail) UnsetAreaDisplayOrder()`

UnsetAreaDisplayOrder ensures that no value is present for AreaDisplayOrder, not even an explicit nil
### GetUpdatedAt

`func (o *SummerTrail) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *SummerTrail) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *SummerTrail) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


