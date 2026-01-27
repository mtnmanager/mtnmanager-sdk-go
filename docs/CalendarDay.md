# CalendarDay

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | **string** | Calendar date (YYYY-MM-DD). | 
**DayOfWeek** | [**DayOfWeek**](DayOfWeek.md) | Day of the week. | 
**IsOpen** | **bool** | Whether the resort is open on this day. | 
**OpensAt** | Pointer to **NullableString** | Opening time in 24-hour format (HH:MM), in resort&#39;s local timezone.  &#x60;null&#x60; if closed on this day. | [optional] 
**ClosesAt** | Pointer to **NullableString** | Closing time in 24-hour format (HH:MM), in resort&#39;s local timezone.  &#x60;null&#x60; if closed on this day. | [optional] 
**ClosureReason** | Pointer to [**NullableClosureReason**](ClosureReason.md) |  | [optional] 
**SpecialEvent** | Pointer to **NullableString** | Special event for this day. | [optional] 

## Methods

### NewCalendarDay

`func NewCalendarDay(date string, dayOfWeek DayOfWeek, isOpen bool, ) *CalendarDay`

NewCalendarDay instantiates a new CalendarDay object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCalendarDayWithDefaults

`func NewCalendarDayWithDefaults() *CalendarDay`

NewCalendarDayWithDefaults instantiates a new CalendarDay object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *CalendarDay) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *CalendarDay) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *CalendarDay) SetDate(v string)`

SetDate sets Date field to given value.


### GetDayOfWeek

`func (o *CalendarDay) GetDayOfWeek() DayOfWeek`

GetDayOfWeek returns the DayOfWeek field if non-nil, zero value otherwise.

### GetDayOfWeekOk

`func (o *CalendarDay) GetDayOfWeekOk() (*DayOfWeek, bool)`

GetDayOfWeekOk returns a tuple with the DayOfWeek field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDayOfWeek

`func (o *CalendarDay) SetDayOfWeek(v DayOfWeek)`

SetDayOfWeek sets DayOfWeek field to given value.


### GetIsOpen

`func (o *CalendarDay) GetIsOpen() bool`

GetIsOpen returns the IsOpen field if non-nil, zero value otherwise.

### GetIsOpenOk

`func (o *CalendarDay) GetIsOpenOk() (*bool, bool)`

GetIsOpenOk returns a tuple with the IsOpen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOpen

`func (o *CalendarDay) SetIsOpen(v bool)`

SetIsOpen sets IsOpen field to given value.


### GetOpensAt

`func (o *CalendarDay) GetOpensAt() string`

GetOpensAt returns the OpensAt field if non-nil, zero value otherwise.

### GetOpensAtOk

`func (o *CalendarDay) GetOpensAtOk() (*string, bool)`

GetOpensAtOk returns a tuple with the OpensAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpensAt

`func (o *CalendarDay) SetOpensAt(v string)`

SetOpensAt sets OpensAt field to given value.

### HasOpensAt

`func (o *CalendarDay) HasOpensAt() bool`

HasOpensAt returns a boolean if a field has been set.

### SetOpensAtNil

`func (o *CalendarDay) SetOpensAtNil(b bool)`

 SetOpensAtNil sets the value for OpensAt to be an explicit nil

### UnsetOpensAt
`func (o *CalendarDay) UnsetOpensAt()`

UnsetOpensAt ensures that no value is present for OpensAt, not even an explicit nil
### GetClosesAt

`func (o *CalendarDay) GetClosesAt() string`

GetClosesAt returns the ClosesAt field if non-nil, zero value otherwise.

### GetClosesAtOk

`func (o *CalendarDay) GetClosesAtOk() (*string, bool)`

GetClosesAtOk returns a tuple with the ClosesAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClosesAt

`func (o *CalendarDay) SetClosesAt(v string)`

SetClosesAt sets ClosesAt field to given value.

### HasClosesAt

`func (o *CalendarDay) HasClosesAt() bool`

HasClosesAt returns a boolean if a field has been set.

### SetClosesAtNil

`func (o *CalendarDay) SetClosesAtNil(b bool)`

 SetClosesAtNil sets the value for ClosesAt to be an explicit nil

### UnsetClosesAt
`func (o *CalendarDay) UnsetClosesAt()`

UnsetClosesAt ensures that no value is present for ClosesAt, not even an explicit nil
### GetClosureReason

`func (o *CalendarDay) GetClosureReason() ClosureReason`

GetClosureReason returns the ClosureReason field if non-nil, zero value otherwise.

### GetClosureReasonOk

`func (o *CalendarDay) GetClosureReasonOk() (*ClosureReason, bool)`

GetClosureReasonOk returns a tuple with the ClosureReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClosureReason

`func (o *CalendarDay) SetClosureReason(v ClosureReason)`

SetClosureReason sets ClosureReason field to given value.

### HasClosureReason

`func (o *CalendarDay) HasClosureReason() bool`

HasClosureReason returns a boolean if a field has been set.

### SetClosureReasonNil

`func (o *CalendarDay) SetClosureReasonNil(b bool)`

 SetClosureReasonNil sets the value for ClosureReason to be an explicit nil

### UnsetClosureReason
`func (o *CalendarDay) UnsetClosureReason()`

UnsetClosureReason ensures that no value is present for ClosureReason, not even an explicit nil
### GetSpecialEvent

`func (o *CalendarDay) GetSpecialEvent() string`

GetSpecialEvent returns the SpecialEvent field if non-nil, zero value otherwise.

### GetSpecialEventOk

`func (o *CalendarDay) GetSpecialEventOk() (*string, bool)`

GetSpecialEventOk returns a tuple with the SpecialEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpecialEvent

`func (o *CalendarDay) SetSpecialEvent(v string)`

SetSpecialEvent sets SpecialEvent field to given value.

### HasSpecialEvent

`func (o *CalendarDay) HasSpecialEvent() bool`

HasSpecialEvent returns a boolean if a field has been set.

### SetSpecialEventNil

`func (o *CalendarDay) SetSpecialEventNil(b bool)`

 SetSpecialEventNil sets the value for SpecialEvent to be an explicit nil

### UnsetSpecialEvent
`func (o *CalendarDay) UnsetSpecialEvent()`

UnsetSpecialEvent ensures that no value is present for SpecialEvent, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


