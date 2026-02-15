# AmenitySchedule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | Amenity UUID | 
**Name** | **string** | Amenity name | 
**Category** | [**AmenityCategory**](AmenityCategory.md) | Amenity category | 
**Schedules** | [**[]Schedule**](Schedule.md) | Operating schedules for this amenity | 

## Methods

### NewAmenitySchedule

`func NewAmenitySchedule(uuid string, name string, category AmenityCategory, schedules []Schedule, ) *AmenitySchedule`

NewAmenitySchedule instantiates a new AmenitySchedule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAmenityScheduleWithDefaults

`func NewAmenityScheduleWithDefaults() *AmenitySchedule`

NewAmenityScheduleWithDefaults instantiates a new AmenitySchedule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *AmenitySchedule) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *AmenitySchedule) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *AmenitySchedule) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *AmenitySchedule) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AmenitySchedule) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AmenitySchedule) SetName(v string)`

SetName sets Name field to given value.


### GetCategory

`func (o *AmenitySchedule) GetCategory() AmenityCategory`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *AmenitySchedule) GetCategoryOk() (*AmenityCategory, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *AmenitySchedule) SetCategory(v AmenityCategory)`

SetCategory sets Category field to given value.


### GetSchedules

`func (o *AmenitySchedule) GetSchedules() []Schedule`

GetSchedules returns the Schedules field if non-nil, zero value otherwise.

### GetSchedulesOk

`func (o *AmenitySchedule) GetSchedulesOk() (*[]Schedule, bool)`

GetSchedulesOk returns a tuple with the Schedules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedules

`func (o *AmenitySchedule) SetSchedules(v []Schedule)`

SetSchedules sets Schedules field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


