# OverviewNews

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | Stable identifier of this news feed. | 
**Name** | Pointer to **NullableString** | The name the resort gave this news feed, for telling several apart.  May be &#x60;null&#x60; on the primary news feed. | [optional] 
**IsPrimary** | **bool** | Whether this is the resort&#39;s primary news feed. Exactly one news is. | 
**Raw** | **string** | Markdown source. Images the resort uploaded point at their public URLs,  so any Markdown renderer can display them. | 
**Html** | **string** | Rendered HTML (from Markdown) | 
**UpdatedAt** | **time.Time** | When the news was last updated. | 

## Methods

### NewOverviewNews

`func NewOverviewNews(uuid string, isPrimary bool, raw string, html string, updatedAt time.Time, ) *OverviewNews`

NewOverviewNews instantiates a new OverviewNews object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOverviewNewsWithDefaults

`func NewOverviewNewsWithDefaults() *OverviewNews`

NewOverviewNewsWithDefaults instantiates a new OverviewNews object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *OverviewNews) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *OverviewNews) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *OverviewNews) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *OverviewNews) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *OverviewNews) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *OverviewNews) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *OverviewNews) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *OverviewNews) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *OverviewNews) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetIsPrimary

`func (o *OverviewNews) GetIsPrimary() bool`

GetIsPrimary returns the IsPrimary field if non-nil, zero value otherwise.

### GetIsPrimaryOk

`func (o *OverviewNews) GetIsPrimaryOk() (*bool, bool)`

GetIsPrimaryOk returns a tuple with the IsPrimary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPrimary

`func (o *OverviewNews) SetIsPrimary(v bool)`

SetIsPrimary sets IsPrimary field to given value.


### GetRaw

`func (o *OverviewNews) GetRaw() string`

GetRaw returns the Raw field if non-nil, zero value otherwise.

### GetRawOk

`func (o *OverviewNews) GetRawOk() (*string, bool)`

GetRawOk returns a tuple with the Raw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRaw

`func (o *OverviewNews) SetRaw(v string)`

SetRaw sets Raw field to given value.


### GetHtml

`func (o *OverviewNews) GetHtml() string`

GetHtml returns the Html field if non-nil, zero value otherwise.

### GetHtmlOk

`func (o *OverviewNews) GetHtmlOk() (*string, bool)`

GetHtmlOk returns a tuple with the Html field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHtml

`func (o *OverviewNews) SetHtml(v string)`

SetHtml sets Html field to given value.


### GetUpdatedAt

`func (o *OverviewNews) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OverviewNews) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OverviewNews) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


