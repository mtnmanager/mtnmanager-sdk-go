# Schedule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DaysString** | **string** | Human-readable description of which days this schedule applies to.  Examples: \&quot;Daily\&quot;, \&quot;Saturday &amp; Sunday\&quot;, \&quot;Monday, Wednesday, and Friday\&quot; | 
**DaysOfWeek** | [**[]DayOfWeek**](DayOfWeek.md) | Array of days of the week this schedule applies to.  For programmatic use. | 
**TimeString** | **string** | Human-readable time range.  Example: \&quot;9:00 a.m. to 4:00 p.m.\&quot; | 
**OpensAt** | **string** | Opening time in 24-hour format (HH:MM), in resort&#39;s local timezone. | 
**ClosesAt** | **string** | Closing time in 24-hour format (HH:MM), in resort&#39;s local timezone. | 
**InEffect** | **bool** | Whether this schedule is currently in effect.  &#x60;false&#x60; for upcoming schedules that haven&#39;t started yet. | 
**EffectiveString** | **string** | Human-readable date range when this schedule is effective.  Example: \&quot;November 1, 2024 to April 15, 2025\&quot; | 
**EffectiveFrom** | **string** | Start date of the effective period (YYYY-MM-DD). | 
**EffectiveTo** | **string** | End date of the effective period (YYYY-MM-DD). | 

## Methods

### NewSchedule

`func NewSchedule(daysString string, daysOfWeek []DayOfWeek, timeString string, opensAt string, closesAt string, inEffect bool, effectiveString string, effectiveFrom string, effectiveTo string, ) *Schedule`

NewSchedule instantiates a new Schedule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewScheduleWithDefaults

`func NewScheduleWithDefaults() *Schedule`

NewScheduleWithDefaults instantiates a new Schedule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDaysString

`func (o *Schedule) GetDaysString() string`

GetDaysString returns the DaysString field if non-nil, zero value otherwise.

### GetDaysStringOk

`func (o *Schedule) GetDaysStringOk() (*string, bool)`

GetDaysStringOk returns a tuple with the DaysString field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDaysString

`func (o *Schedule) SetDaysString(v string)`

SetDaysString sets DaysString field to given value.


### GetDaysOfWeek

`func (o *Schedule) GetDaysOfWeek() []DayOfWeek`

GetDaysOfWeek returns the DaysOfWeek field if non-nil, zero value otherwise.

### GetDaysOfWeekOk

`func (o *Schedule) GetDaysOfWeekOk() (*[]DayOfWeek, bool)`

GetDaysOfWeekOk returns a tuple with the DaysOfWeek field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDaysOfWeek

`func (o *Schedule) SetDaysOfWeek(v []DayOfWeek)`

SetDaysOfWeek sets DaysOfWeek field to given value.


### GetTimeString

`func (o *Schedule) GetTimeString() string`

GetTimeString returns the TimeString field if non-nil, zero value otherwise.

### GetTimeStringOk

`func (o *Schedule) GetTimeStringOk() (*string, bool)`

GetTimeStringOk returns a tuple with the TimeString field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeString

`func (o *Schedule) SetTimeString(v string)`

SetTimeString sets TimeString field to given value.


### GetOpensAt

`func (o *Schedule) GetOpensAt() string`

GetOpensAt returns the OpensAt field if non-nil, zero value otherwise.

### GetOpensAtOk

`func (o *Schedule) GetOpensAtOk() (*string, bool)`

GetOpensAtOk returns a tuple with the OpensAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpensAt

`func (o *Schedule) SetOpensAt(v string)`

SetOpensAt sets OpensAt field to given value.


### GetClosesAt

`func (o *Schedule) GetClosesAt() string`

GetClosesAt returns the ClosesAt field if non-nil, zero value otherwise.

### GetClosesAtOk

`func (o *Schedule) GetClosesAtOk() (*string, bool)`

GetClosesAtOk returns a tuple with the ClosesAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClosesAt

`func (o *Schedule) SetClosesAt(v string)`

SetClosesAt sets ClosesAt field to given value.


### GetInEffect

`func (o *Schedule) GetInEffect() bool`

GetInEffect returns the InEffect field if non-nil, zero value otherwise.

### GetInEffectOk

`func (o *Schedule) GetInEffectOk() (*bool, bool)`

GetInEffectOk returns a tuple with the InEffect field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInEffect

`func (o *Schedule) SetInEffect(v bool)`

SetInEffect sets InEffect field to given value.


### GetEffectiveString

`func (o *Schedule) GetEffectiveString() string`

GetEffectiveString returns the EffectiveString field if non-nil, zero value otherwise.

### GetEffectiveStringOk

`func (o *Schedule) GetEffectiveStringOk() (*string, bool)`

GetEffectiveStringOk returns a tuple with the EffectiveString field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveString

`func (o *Schedule) SetEffectiveString(v string)`

SetEffectiveString sets EffectiveString field to given value.


### GetEffectiveFrom

`func (o *Schedule) GetEffectiveFrom() string`

GetEffectiveFrom returns the EffectiveFrom field if non-nil, zero value otherwise.

### GetEffectiveFromOk

`func (o *Schedule) GetEffectiveFromOk() (*string, bool)`

GetEffectiveFromOk returns a tuple with the EffectiveFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveFrom

`func (o *Schedule) SetEffectiveFrom(v string)`

SetEffectiveFrom sets EffectiveFrom field to given value.


### GetEffectiveTo

`func (o *Schedule) GetEffectiveTo() string`

GetEffectiveTo returns the EffectiveTo field if non-nil, zero value otherwise.

### GetEffectiveToOk

`func (o *Schedule) GetEffectiveToOk() (*string, bool)`

GetEffectiveToOk returns a tuple with the EffectiveTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveTo

`func (o *Schedule) SetEffectiveTo(v string)`

SetEffectiveTo sets EffectiveTo field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


