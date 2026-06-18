# Amenity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | **string** | Description of the amenity. | 
**Uuid** | **string** | Unique identifier for the amenity. | 
**Name** | **string** | Display name of the amenity. | 
**Category** | [**AmenityCategory**](AmenityCategory.md) | Category classification (e.g. restaurant, lodge, ski_school). | 
**Website** | **string** | Website URL for the amenity, if available. | 
**HasOperatingHours** | **bool** | Whether this amenity reports operating hours. When false, clients should  not expect &#x60;opens_at&#x60;, &#x60;closes_at&#x60;, or &#x60;schedules&#x60; to ever be populated. | 
**OpensAt** | Pointer to **NullableString** | Today&#39;s scheduled opening time in 24-hour format (HH:MM), in resort&#39;s local timezone. | [optional] 
**ClosesAt** | Pointer to **NullableString** | Today&#39;s scheduled closing time in 24-hour format (HH:MM), in resort&#39;s local timezone. | [optional] 
**Schedules** | [**[]Schedule**](Schedule.md) | Recurring operating schedules for this amenity (e.g. \&quot;Saturday &amp; Sunday,  9:00 a.m. to 4:00 p.m.\&quot;), with both human-readable and structured fields. | 
**Images** | Pointer to [**[]EntityImage**](EntityImage.md) | Images attached to this amenity, ordered for display. Each includes a  ThumbHash for rendering a blurred placeholder while the image loads. | [optional] [default to {}]

## Methods

### NewAmenity

`func NewAmenity(description string, uuid string, name string, category AmenityCategory, website string, hasOperatingHours bool, schedules []Schedule, ) *Amenity`

NewAmenity instantiates a new Amenity object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAmenityWithDefaults

`func NewAmenityWithDefaults() *Amenity`

NewAmenityWithDefaults instantiates a new Amenity object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *Amenity) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Amenity) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Amenity) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetUuid

`func (o *Amenity) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *Amenity) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *Amenity) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *Amenity) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Amenity) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Amenity) SetName(v string)`

SetName sets Name field to given value.


### GetCategory

`func (o *Amenity) GetCategory() AmenityCategory`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *Amenity) GetCategoryOk() (*AmenityCategory, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *Amenity) SetCategory(v AmenityCategory)`

SetCategory sets Category field to given value.


### GetWebsite

`func (o *Amenity) GetWebsite() string`

GetWebsite returns the Website field if non-nil, zero value otherwise.

### GetWebsiteOk

`func (o *Amenity) GetWebsiteOk() (*string, bool)`

GetWebsiteOk returns a tuple with the Website field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsite

`func (o *Amenity) SetWebsite(v string)`

SetWebsite sets Website field to given value.


### GetHasOperatingHours

`func (o *Amenity) GetHasOperatingHours() bool`

GetHasOperatingHours returns the HasOperatingHours field if non-nil, zero value otherwise.

### GetHasOperatingHoursOk

`func (o *Amenity) GetHasOperatingHoursOk() (*bool, bool)`

GetHasOperatingHoursOk returns a tuple with the HasOperatingHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasOperatingHours

`func (o *Amenity) SetHasOperatingHours(v bool)`

SetHasOperatingHours sets HasOperatingHours field to given value.


### GetOpensAt

`func (o *Amenity) GetOpensAt() string`

GetOpensAt returns the OpensAt field if non-nil, zero value otherwise.

### GetOpensAtOk

`func (o *Amenity) GetOpensAtOk() (*string, bool)`

GetOpensAtOk returns a tuple with the OpensAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpensAt

`func (o *Amenity) SetOpensAt(v string)`

SetOpensAt sets OpensAt field to given value.

### HasOpensAt

`func (o *Amenity) HasOpensAt() bool`

HasOpensAt returns a boolean if a field has been set.

### SetOpensAtNil

`func (o *Amenity) SetOpensAtNil(b bool)`

 SetOpensAtNil sets the value for OpensAt to be an explicit nil

### UnsetOpensAt
`func (o *Amenity) UnsetOpensAt()`

UnsetOpensAt ensures that no value is present for OpensAt, not even an explicit nil
### GetClosesAt

`func (o *Amenity) GetClosesAt() string`

GetClosesAt returns the ClosesAt field if non-nil, zero value otherwise.

### GetClosesAtOk

`func (o *Amenity) GetClosesAtOk() (*string, bool)`

GetClosesAtOk returns a tuple with the ClosesAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClosesAt

`func (o *Amenity) SetClosesAt(v string)`

SetClosesAt sets ClosesAt field to given value.

### HasClosesAt

`func (o *Amenity) HasClosesAt() bool`

HasClosesAt returns a boolean if a field has been set.

### SetClosesAtNil

`func (o *Amenity) SetClosesAtNil(b bool)`

 SetClosesAtNil sets the value for ClosesAt to be an explicit nil

### UnsetClosesAt
`func (o *Amenity) UnsetClosesAt()`

UnsetClosesAt ensures that no value is present for ClosesAt, not even an explicit nil
### GetSchedules

`func (o *Amenity) GetSchedules() []Schedule`

GetSchedules returns the Schedules field if non-nil, zero value otherwise.

### GetSchedulesOk

`func (o *Amenity) GetSchedulesOk() (*[]Schedule, bool)`

GetSchedulesOk returns a tuple with the Schedules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedules

`func (o *Amenity) SetSchedules(v []Schedule)`

SetSchedules sets Schedules field to given value.


### GetImages

`func (o *Amenity) GetImages() []EntityImage`

GetImages returns the Images field if non-nil, zero value otherwise.

### GetImagesOk

`func (o *Amenity) GetImagesOk() (*[]EntityImage, bool)`

GetImagesOk returns a tuple with the Images field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImages

`func (o *Amenity) SetImages(v []EntityImage)`

SetImages sets Images field to given value.

### HasImages

`func (o *Amenity) HasImages() bool`

HasImages returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


