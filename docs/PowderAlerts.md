# PowderAlerts

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **bool** | Guests can sign up for text alerts via  &#x60;POST /api/notifications/v1/text/powder/signup&#x60; on the resort&#39;s host. | 
**Push** | **bool** | Guests can subscribe to push alerts in the resort&#39;s mobile app. | 

## Methods

### NewPowderAlerts

`func NewPowderAlerts(text bool, push bool, ) *PowderAlerts`

NewPowderAlerts instantiates a new PowderAlerts object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPowderAlertsWithDefaults

`func NewPowderAlertsWithDefaults() *PowderAlerts`

NewPowderAlertsWithDefaults instantiates a new PowderAlerts object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *PowderAlerts) GetText() bool`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *PowderAlerts) GetTextOk() (*bool, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *PowderAlerts) SetText(v bool)`

SetText sets Text field to given value.


### GetPush

`func (o *PowderAlerts) GetPush() bool`

GetPush returns the Push field if non-nil, zero value otherwise.

### GetPushOk

`func (o *PowderAlerts) GetPushOk() (*bool, bool)`

GetPushOk returns a tuple with the Push field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPush

`func (o *PowderAlerts) SetPush(v bool)`

SetPush sets Push field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


