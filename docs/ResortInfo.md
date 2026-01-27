# ResortInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | Unique identifier for the resort. | 
**Name** | **string** | Display name of the resort. | 
**Slug** | **string** | URL-friendly identifier for the resort, used in account subdomain. | 
**Timezone** | **string** | IANA timezone identifier for the resort&#39;s local time. | 
**UnitPreference** | [**UnitPreference**](UnitPreference.md) | Preferred unit system for measurements (metric or imperial). | 

## Methods

### NewResortInfo

`func NewResortInfo(uuid string, name string, slug string, timezone string, unitPreference UnitPreference, ) *ResortInfo`

NewResortInfo instantiates a new ResortInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResortInfoWithDefaults

`func NewResortInfoWithDefaults() *ResortInfo`

NewResortInfoWithDefaults instantiates a new ResortInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *ResortInfo) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *ResortInfo) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *ResortInfo) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *ResortInfo) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ResortInfo) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ResortInfo) SetName(v string)`

SetName sets Name field to given value.


### GetSlug

`func (o *ResortInfo) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *ResortInfo) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *ResortInfo) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetTimezone

`func (o *ResortInfo) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *ResortInfo) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *ResortInfo) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.


### GetUnitPreference

`func (o *ResortInfo) GetUnitPreference() UnitPreference`

GetUnitPreference returns the UnitPreference field if non-nil, zero value otherwise.

### GetUnitPreferenceOk

`func (o *ResortInfo) GetUnitPreferenceOk() (*UnitPreference, bool)`

GetUnitPreferenceOk returns a tuple with the UnitPreference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPreference

`func (o *ResortInfo) SetUnitPreference(v UnitPreference)`

SetUnitPreference sets UnitPreference field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


