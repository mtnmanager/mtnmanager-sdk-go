# TrailMapElementOneOf5

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** |  | 
**Uuid** | **string** |  | 
**X** | **float64** |  | 
**Y** | **float64** |  | 
**Icon** | Pointer to [**NullableMarkerIcon**](MarkerIcon.md) |  | [optional] 
**Color** | Pointer to **NullableString** |  | [optional] 
**ParkingLot** | Pointer to [**NullableParkingLot**](ParkingLot.md) |  | [optional] 
**GroupLabel** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewTrailMapElementOneOf5

`func NewTrailMapElementOneOf5(type_ string, uuid string, x float64, y float64, ) *TrailMapElementOneOf5`

NewTrailMapElementOneOf5 instantiates a new TrailMapElementOneOf5 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrailMapElementOneOf5WithDefaults

`func NewTrailMapElementOneOf5WithDefaults() *TrailMapElementOneOf5`

NewTrailMapElementOneOf5WithDefaults instantiates a new TrailMapElementOneOf5 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *TrailMapElementOneOf5) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TrailMapElementOneOf5) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TrailMapElementOneOf5) SetType(v string)`

SetType sets Type field to given value.


### GetUuid

`func (o *TrailMapElementOneOf5) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *TrailMapElementOneOf5) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *TrailMapElementOneOf5) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetX

`func (o *TrailMapElementOneOf5) GetX() float64`

GetX returns the X field if non-nil, zero value otherwise.

### GetXOk

`func (o *TrailMapElementOneOf5) GetXOk() (*float64, bool)`

GetXOk returns a tuple with the X field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetX

`func (o *TrailMapElementOneOf5) SetX(v float64)`

SetX sets X field to given value.


### GetY

`func (o *TrailMapElementOneOf5) GetY() float64`

GetY returns the Y field if non-nil, zero value otherwise.

### GetYOk

`func (o *TrailMapElementOneOf5) GetYOk() (*float64, bool)`

GetYOk returns a tuple with the Y field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetY

`func (o *TrailMapElementOneOf5) SetY(v float64)`

SetY sets Y field to given value.


### GetIcon

`func (o *TrailMapElementOneOf5) GetIcon() MarkerIcon`

GetIcon returns the Icon field if non-nil, zero value otherwise.

### GetIconOk

`func (o *TrailMapElementOneOf5) GetIconOk() (*MarkerIcon, bool)`

GetIconOk returns a tuple with the Icon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcon

`func (o *TrailMapElementOneOf5) SetIcon(v MarkerIcon)`

SetIcon sets Icon field to given value.

### HasIcon

`func (o *TrailMapElementOneOf5) HasIcon() bool`

HasIcon returns a boolean if a field has been set.

### SetIconNil

`func (o *TrailMapElementOneOf5) SetIconNil(b bool)`

 SetIconNil sets the value for Icon to be an explicit nil

### UnsetIcon
`func (o *TrailMapElementOneOf5) UnsetIcon()`

UnsetIcon ensures that no value is present for Icon, not even an explicit nil
### GetColor

`func (o *TrailMapElementOneOf5) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *TrailMapElementOneOf5) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *TrailMapElementOneOf5) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *TrailMapElementOneOf5) HasColor() bool`

HasColor returns a boolean if a field has been set.

### SetColorNil

`func (o *TrailMapElementOneOf5) SetColorNil(b bool)`

 SetColorNil sets the value for Color to be an explicit nil

### UnsetColor
`func (o *TrailMapElementOneOf5) UnsetColor()`

UnsetColor ensures that no value is present for Color, not even an explicit nil
### GetParkingLot

`func (o *TrailMapElementOneOf5) GetParkingLot() ParkingLot`

GetParkingLot returns the ParkingLot field if non-nil, zero value otherwise.

### GetParkingLotOk

`func (o *TrailMapElementOneOf5) GetParkingLotOk() (*ParkingLot, bool)`

GetParkingLotOk returns a tuple with the ParkingLot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParkingLot

`func (o *TrailMapElementOneOf5) SetParkingLot(v ParkingLot)`

SetParkingLot sets ParkingLot field to given value.

### HasParkingLot

`func (o *TrailMapElementOneOf5) HasParkingLot() bool`

HasParkingLot returns a boolean if a field has been set.

### SetParkingLotNil

`func (o *TrailMapElementOneOf5) SetParkingLotNil(b bool)`

 SetParkingLotNil sets the value for ParkingLot to be an explicit nil

### UnsetParkingLot
`func (o *TrailMapElementOneOf5) UnsetParkingLot()`

UnsetParkingLot ensures that no value is present for ParkingLot, not even an explicit nil
### GetGroupLabel

`func (o *TrailMapElementOneOf5) GetGroupLabel() string`

GetGroupLabel returns the GroupLabel field if non-nil, zero value otherwise.

### GetGroupLabelOk

`func (o *TrailMapElementOneOf5) GetGroupLabelOk() (*string, bool)`

GetGroupLabelOk returns a tuple with the GroupLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupLabel

`func (o *TrailMapElementOneOf5) SetGroupLabel(v string)`

SetGroupLabel sets GroupLabel field to given value.

### HasGroupLabel

`func (o *TrailMapElementOneOf5) HasGroupLabel() bool`

HasGroupLabel returns a boolean if a field has been set.

### SetGroupLabelNil

`func (o *TrailMapElementOneOf5) SetGroupLabelNil(b bool)`

 SetGroupLabelNil sets the value for GroupLabel to be an explicit nil

### UnsetGroupLabel
`func (o *TrailMapElementOneOf5) UnsetGroupLabel()`

UnsetGroupLabel ensures that no value is present for GroupLabel, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


