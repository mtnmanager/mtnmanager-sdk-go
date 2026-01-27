# Run

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | Unique identifier for the run. | 
**Name** | **string** | Display name of the run. | 
**Slug** | **string** | URL-friendly name of the run. | 
**Number** | Pointer to **NullableInt32** | Optional run number. | [optional] 
**Difficulty** | [**RunDifficulty**](RunDifficulty.md) | Difficulty rating of the run. | 
**Status** | [**RunStatus**](RunStatus.md) | Current operational status (open, closed, or unknown). | 
**LastGroomed** | Pointer to **NullableTime** | When the run was last groomed.  &#x60;null&#x60; if never groomed, or if the runs grooming feature is disabled. | [optional] 
**GroomedToday** | **bool** | Whether the run was groomed within the last 24 hours. | 
**ConditionNotes** | **string** | Notes about current conditions on this run. | 
**AreaUuid** | Pointer to **NullableString** | UUID of the area this run belongs to, if assigned. | [optional] 
**AreaName** | Pointer to **NullableString** | Name of the area this run belongs to, if assigned. | [optional] 
**AreaDisplayOrder** | Pointer to **NullableInt32** | Display order of the area this run belongs to, if assigned, for sorting purposes. | [optional] 
**UpdatedAt** | **time.Time** | When this run&#39;s information was last updated. | 

## Methods

### NewRun

`func NewRun(uuid string, name string, slug string, difficulty RunDifficulty, status RunStatus, groomedToday bool, conditionNotes string, updatedAt time.Time, ) *Run`

NewRun instantiates a new Run object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRunWithDefaults

`func NewRunWithDefaults() *Run`

NewRunWithDefaults instantiates a new Run object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *Run) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *Run) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *Run) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *Run) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Run) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Run) SetName(v string)`

SetName sets Name field to given value.


### GetSlug

`func (o *Run) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *Run) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *Run) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetNumber

`func (o *Run) GetNumber() int32`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *Run) GetNumberOk() (*int32, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *Run) SetNumber(v int32)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *Run) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### SetNumberNil

`func (o *Run) SetNumberNil(b bool)`

 SetNumberNil sets the value for Number to be an explicit nil

### UnsetNumber
`func (o *Run) UnsetNumber()`

UnsetNumber ensures that no value is present for Number, not even an explicit nil
### GetDifficulty

`func (o *Run) GetDifficulty() RunDifficulty`

GetDifficulty returns the Difficulty field if non-nil, zero value otherwise.

### GetDifficultyOk

`func (o *Run) GetDifficultyOk() (*RunDifficulty, bool)`

GetDifficultyOk returns a tuple with the Difficulty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDifficulty

`func (o *Run) SetDifficulty(v RunDifficulty)`

SetDifficulty sets Difficulty field to given value.


### GetStatus

`func (o *Run) GetStatus() RunStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Run) GetStatusOk() (*RunStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Run) SetStatus(v RunStatus)`

SetStatus sets Status field to given value.


### GetLastGroomed

`func (o *Run) GetLastGroomed() time.Time`

GetLastGroomed returns the LastGroomed field if non-nil, zero value otherwise.

### GetLastGroomedOk

`func (o *Run) GetLastGroomedOk() (*time.Time, bool)`

GetLastGroomedOk returns a tuple with the LastGroomed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastGroomed

`func (o *Run) SetLastGroomed(v time.Time)`

SetLastGroomed sets LastGroomed field to given value.

### HasLastGroomed

`func (o *Run) HasLastGroomed() bool`

HasLastGroomed returns a boolean if a field has been set.

### SetLastGroomedNil

`func (o *Run) SetLastGroomedNil(b bool)`

 SetLastGroomedNil sets the value for LastGroomed to be an explicit nil

### UnsetLastGroomed
`func (o *Run) UnsetLastGroomed()`

UnsetLastGroomed ensures that no value is present for LastGroomed, not even an explicit nil
### GetGroomedToday

`func (o *Run) GetGroomedToday() bool`

GetGroomedToday returns the GroomedToday field if non-nil, zero value otherwise.

### GetGroomedTodayOk

`func (o *Run) GetGroomedTodayOk() (*bool, bool)`

GetGroomedTodayOk returns a tuple with the GroomedToday field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroomedToday

`func (o *Run) SetGroomedToday(v bool)`

SetGroomedToday sets GroomedToday field to given value.


### GetConditionNotes

`func (o *Run) GetConditionNotes() string`

GetConditionNotes returns the ConditionNotes field if non-nil, zero value otherwise.

### GetConditionNotesOk

`func (o *Run) GetConditionNotesOk() (*string, bool)`

GetConditionNotesOk returns a tuple with the ConditionNotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConditionNotes

`func (o *Run) SetConditionNotes(v string)`

SetConditionNotes sets ConditionNotes field to given value.


### GetAreaUuid

`func (o *Run) GetAreaUuid() string`

GetAreaUuid returns the AreaUuid field if non-nil, zero value otherwise.

### GetAreaUuidOk

`func (o *Run) GetAreaUuidOk() (*string, bool)`

GetAreaUuidOk returns a tuple with the AreaUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaUuid

`func (o *Run) SetAreaUuid(v string)`

SetAreaUuid sets AreaUuid field to given value.

### HasAreaUuid

`func (o *Run) HasAreaUuid() bool`

HasAreaUuid returns a boolean if a field has been set.

### SetAreaUuidNil

`func (o *Run) SetAreaUuidNil(b bool)`

 SetAreaUuidNil sets the value for AreaUuid to be an explicit nil

### UnsetAreaUuid
`func (o *Run) UnsetAreaUuid()`

UnsetAreaUuid ensures that no value is present for AreaUuid, not even an explicit nil
### GetAreaName

`func (o *Run) GetAreaName() string`

GetAreaName returns the AreaName field if non-nil, zero value otherwise.

### GetAreaNameOk

`func (o *Run) GetAreaNameOk() (*string, bool)`

GetAreaNameOk returns a tuple with the AreaName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaName

`func (o *Run) SetAreaName(v string)`

SetAreaName sets AreaName field to given value.

### HasAreaName

`func (o *Run) HasAreaName() bool`

HasAreaName returns a boolean if a field has been set.

### SetAreaNameNil

`func (o *Run) SetAreaNameNil(b bool)`

 SetAreaNameNil sets the value for AreaName to be an explicit nil

### UnsetAreaName
`func (o *Run) UnsetAreaName()`

UnsetAreaName ensures that no value is present for AreaName, not even an explicit nil
### GetAreaDisplayOrder

`func (o *Run) GetAreaDisplayOrder() int32`

GetAreaDisplayOrder returns the AreaDisplayOrder field if non-nil, zero value otherwise.

### GetAreaDisplayOrderOk

`func (o *Run) GetAreaDisplayOrderOk() (*int32, bool)`

GetAreaDisplayOrderOk returns a tuple with the AreaDisplayOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAreaDisplayOrder

`func (o *Run) SetAreaDisplayOrder(v int32)`

SetAreaDisplayOrder sets AreaDisplayOrder field to given value.

### HasAreaDisplayOrder

`func (o *Run) HasAreaDisplayOrder() bool`

HasAreaDisplayOrder returns a boolean if a field has been set.

### SetAreaDisplayOrderNil

`func (o *Run) SetAreaDisplayOrderNil(b bool)`

 SetAreaDisplayOrderNil sets the value for AreaDisplayOrder to be an explicit nil

### UnsetAreaDisplayOrder
`func (o *Run) UnsetAreaDisplayOrder()`

UnsetAreaDisplayOrder ensures that no value is present for AreaDisplayOrder, not even an explicit nil
### GetUpdatedAt

`func (o *Run) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Run) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Run) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


