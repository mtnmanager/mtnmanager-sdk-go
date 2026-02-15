# AmenityCalendarEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | Amenity UUID. | 
**Name** | **string** | Amenity name. | 
**Category** | [**AmenityCategory**](AmenityCategory.md) | Amenity category. | 
**OpensAt** | Pointer to **NullableString** | Opening time in 24-hour format (HH:MM), in resort&#39;s local timezone.  &#x60;null&#x60; if this amenity is closed on this day. | [optional] 
**ClosesAt** | Pointer to **NullableString** | Closing time in 24-hour format (HH:MM), in resort&#39;s local timezone.  &#x60;null&#x60; if this amenity is closed on this day. | [optional] 

## Methods

### NewAmenityCalendarEntry

`func NewAmenityCalendarEntry(uuid string, name string, category AmenityCategory, ) *AmenityCalendarEntry`

NewAmenityCalendarEntry instantiates a new AmenityCalendarEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAmenityCalendarEntryWithDefaults

`func NewAmenityCalendarEntryWithDefaults() *AmenityCalendarEntry`

NewAmenityCalendarEntryWithDefaults instantiates a new AmenityCalendarEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *AmenityCalendarEntry) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *AmenityCalendarEntry) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *AmenityCalendarEntry) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *AmenityCalendarEntry) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AmenityCalendarEntry) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AmenityCalendarEntry) SetName(v string)`

SetName sets Name field to given value.


### GetCategory

`func (o *AmenityCalendarEntry) GetCategory() AmenityCategory`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *AmenityCalendarEntry) GetCategoryOk() (*AmenityCategory, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *AmenityCalendarEntry) SetCategory(v AmenityCategory)`

SetCategory sets Category field to given value.


### GetOpensAt

`func (o *AmenityCalendarEntry) GetOpensAt() string`

GetOpensAt returns the OpensAt field if non-nil, zero value otherwise.

### GetOpensAtOk

`func (o *AmenityCalendarEntry) GetOpensAtOk() (*string, bool)`

GetOpensAtOk returns a tuple with the OpensAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpensAt

`func (o *AmenityCalendarEntry) SetOpensAt(v string)`

SetOpensAt sets OpensAt field to given value.

### HasOpensAt

`func (o *AmenityCalendarEntry) HasOpensAt() bool`

HasOpensAt returns a boolean if a field has been set.

### SetOpensAtNil

`func (o *AmenityCalendarEntry) SetOpensAtNil(b bool)`

 SetOpensAtNil sets the value for OpensAt to be an explicit nil

### UnsetOpensAt
`func (o *AmenityCalendarEntry) UnsetOpensAt()`

UnsetOpensAt ensures that no value is present for OpensAt, not even an explicit nil
### GetClosesAt

`func (o *AmenityCalendarEntry) GetClosesAt() string`

GetClosesAt returns the ClosesAt field if non-nil, zero value otherwise.

### GetClosesAtOk

`func (o *AmenityCalendarEntry) GetClosesAtOk() (*string, bool)`

GetClosesAtOk returns a tuple with the ClosesAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClosesAt

`func (o *AmenityCalendarEntry) SetClosesAt(v string)`

SetClosesAt sets ClosesAt field to given value.

### HasClosesAt

`func (o *AmenityCalendarEntry) HasClosesAt() bool`

HasClosesAt returns a boolean if a field has been set.

### SetClosesAtNil

`func (o *AmenityCalendarEntry) SetClosesAtNil(b bool)`

 SetClosesAtNil sets the value for ClosesAt to be an explicit nil

### UnsetClosesAt
`func (o *AmenityCalendarEntry) UnsetClosesAt()`

UnsetClosesAt ensures that no value is present for ClosesAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


