# ParkingLot

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | Unique identifier for the parking lot. | 
**Name** | **string** | Display name of the parking lot. | 
**Slug** | **string** | URL-friendly name of the parking lot. | 
**Status** | [**ParkingLotStatus**](ParkingLotStatus.md) | Current status (open, closed, or full). | 
**Capacity** | Pointer to **NullableInt32** | Maximum vehicle capacity, if set. | [optional] 
**Shuttle** | **bool** | Whether shuttle service is available from this lot. | 
**Paid** | **bool** | Whether parking is paid/requires payment. | 
**ReservationRequired** | **bool** | Whether a reservation is required to park here. | 
**UpdatedAt** | **time.Time** | When this parking lot&#39;s information was last updated. | 

## Methods

### NewParkingLot

`func NewParkingLot(uuid string, name string, slug string, status ParkingLotStatus, shuttle bool, paid bool, reservationRequired bool, updatedAt time.Time, ) *ParkingLot`

NewParkingLot instantiates a new ParkingLot object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewParkingLotWithDefaults

`func NewParkingLotWithDefaults() *ParkingLot`

NewParkingLotWithDefaults instantiates a new ParkingLot object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *ParkingLot) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *ParkingLot) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *ParkingLot) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *ParkingLot) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ParkingLot) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ParkingLot) SetName(v string)`

SetName sets Name field to given value.


### GetSlug

`func (o *ParkingLot) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *ParkingLot) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *ParkingLot) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetStatus

`func (o *ParkingLot) GetStatus() ParkingLotStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ParkingLot) GetStatusOk() (*ParkingLotStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ParkingLot) SetStatus(v ParkingLotStatus)`

SetStatus sets Status field to given value.


### GetCapacity

`func (o *ParkingLot) GetCapacity() int32`

GetCapacity returns the Capacity field if non-nil, zero value otherwise.

### GetCapacityOk

`func (o *ParkingLot) GetCapacityOk() (*int32, bool)`

GetCapacityOk returns a tuple with the Capacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapacity

`func (o *ParkingLot) SetCapacity(v int32)`

SetCapacity sets Capacity field to given value.

### HasCapacity

`func (o *ParkingLot) HasCapacity() bool`

HasCapacity returns a boolean if a field has been set.

### SetCapacityNil

`func (o *ParkingLot) SetCapacityNil(b bool)`

 SetCapacityNil sets the value for Capacity to be an explicit nil

### UnsetCapacity
`func (o *ParkingLot) UnsetCapacity()`

UnsetCapacity ensures that no value is present for Capacity, not even an explicit nil
### GetShuttle

`func (o *ParkingLot) GetShuttle() bool`

GetShuttle returns the Shuttle field if non-nil, zero value otherwise.

### GetShuttleOk

`func (o *ParkingLot) GetShuttleOk() (*bool, bool)`

GetShuttleOk returns a tuple with the Shuttle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShuttle

`func (o *ParkingLot) SetShuttle(v bool)`

SetShuttle sets Shuttle field to given value.


### GetPaid

`func (o *ParkingLot) GetPaid() bool`

GetPaid returns the Paid field if non-nil, zero value otherwise.

### GetPaidOk

`func (o *ParkingLot) GetPaidOk() (*bool, bool)`

GetPaidOk returns a tuple with the Paid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaid

`func (o *ParkingLot) SetPaid(v bool)`

SetPaid sets Paid field to given value.


### GetReservationRequired

`func (o *ParkingLot) GetReservationRequired() bool`

GetReservationRequired returns the ReservationRequired field if non-nil, zero value otherwise.

### GetReservationRequiredOk

`func (o *ParkingLot) GetReservationRequiredOk() (*bool, bool)`

GetReservationRequiredOk returns a tuple with the ReservationRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReservationRequired

`func (o *ParkingLot) SetReservationRequired(v bool)`

SetReservationRequired sets ReservationRequired field to given value.


### GetUpdatedAt

`func (o *ParkingLot) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ParkingLot) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ParkingLot) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


