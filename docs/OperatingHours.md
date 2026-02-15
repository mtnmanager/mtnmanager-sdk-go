# OperatingHours

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Schedules** | [**[]Schedule**](Schedule.md) | Recurring operating schedules currently in effect or upcoming.  Excludes single-day overrides and past schedules. | 
**CalendarDays** | [**[]CalendarDay**](CalendarDay.md) | List of all days the resort is open (or a closure override).  Ordered chronologically, spanning from the earliest scheduled date  to the latest scheduled date in the currently defined operating hours. | 
**AmenitySchedules** | Pointer to [**[]AmenitySchedule**](AmenitySchedule.md) | Per-amenity operating schedules. Only included when amenity hours are configured. | [optional] 

## Methods

### NewOperatingHours

`func NewOperatingHours(schedules []Schedule, calendarDays []CalendarDay, ) *OperatingHours`

NewOperatingHours instantiates a new OperatingHours object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatingHoursWithDefaults

`func NewOperatingHoursWithDefaults() *OperatingHours`

NewOperatingHoursWithDefaults instantiates a new OperatingHours object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSchedules

`func (o *OperatingHours) GetSchedules() []Schedule`

GetSchedules returns the Schedules field if non-nil, zero value otherwise.

### GetSchedulesOk

`func (o *OperatingHours) GetSchedulesOk() (*[]Schedule, bool)`

GetSchedulesOk returns a tuple with the Schedules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedules

`func (o *OperatingHours) SetSchedules(v []Schedule)`

SetSchedules sets Schedules field to given value.


### GetCalendarDays

`func (o *OperatingHours) GetCalendarDays() []CalendarDay`

GetCalendarDays returns the CalendarDays field if non-nil, zero value otherwise.

### GetCalendarDaysOk

`func (o *OperatingHours) GetCalendarDaysOk() (*[]CalendarDay, bool)`

GetCalendarDaysOk returns a tuple with the CalendarDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCalendarDays

`func (o *OperatingHours) SetCalendarDays(v []CalendarDay)`

SetCalendarDays sets CalendarDays field to given value.


### GetAmenitySchedules

`func (o *OperatingHours) GetAmenitySchedules() []AmenitySchedule`

GetAmenitySchedules returns the AmenitySchedules field if non-nil, zero value otherwise.

### GetAmenitySchedulesOk

`func (o *OperatingHours) GetAmenitySchedulesOk() (*[]AmenitySchedule, bool)`

GetAmenitySchedulesOk returns a tuple with the AmenitySchedules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmenitySchedules

`func (o *OperatingHours) SetAmenitySchedules(v []AmenitySchedule)`

SetAmenitySchedules sets AmenitySchedules field to given value.

### HasAmenitySchedules

`func (o *OperatingHours) HasAmenitySchedules() bool`

HasAmenitySchedules returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


