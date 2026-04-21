# PointMarker

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** |  | 
**X** | **float64** |  | 
**Y** | **float64** |  | 
**Icon** | Pointer to [**MarkerIcon**](MarkerIcon.md) |  | [optional] 
**Color** | Pointer to **string** |  | [optional] 
**Amenity** | Pointer to [**Amenity**](Amenity.md) |  | [optional] 
**Kind** | **string** |  | 
**ParkingLot** | Pointer to [**ParkingLot**](ParkingLot.md) |  | [optional] 
**Label** | **string** |  | 
**Searchable** | Pointer to **bool** |  | [optional] 

## Methods

### NewPointMarker

`func NewPointMarker(uuid string, x float64, y float64, kind string, label string, ) *PointMarker`

NewPointMarker instantiates a new PointMarker object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPointMarkerWithDefaults

`func NewPointMarkerWithDefaults() *PointMarker`

NewPointMarkerWithDefaults instantiates a new PointMarker object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *PointMarker) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *PointMarker) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *PointMarker) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetX

`func (o *PointMarker) GetX() float64`

GetX returns the X field if non-nil, zero value otherwise.

### GetXOk

`func (o *PointMarker) GetXOk() (*float64, bool)`

GetXOk returns a tuple with the X field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetX

`func (o *PointMarker) SetX(v float64)`

SetX sets X field to given value.


### GetY

`func (o *PointMarker) GetY() float64`

GetY returns the Y field if non-nil, zero value otherwise.

### GetYOk

`func (o *PointMarker) GetYOk() (*float64, bool)`

GetYOk returns a tuple with the Y field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetY

`func (o *PointMarker) SetY(v float64)`

SetY sets Y field to given value.


### GetIcon

`func (o *PointMarker) GetIcon() MarkerIcon`

GetIcon returns the Icon field if non-nil, zero value otherwise.

### GetIconOk

`func (o *PointMarker) GetIconOk() (*MarkerIcon, bool)`

GetIconOk returns a tuple with the Icon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcon

`func (o *PointMarker) SetIcon(v MarkerIcon)`

SetIcon sets Icon field to given value.

### HasIcon

`func (o *PointMarker) HasIcon() bool`

HasIcon returns a boolean if a field has been set.

### GetColor

`func (o *PointMarker) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *PointMarker) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *PointMarker) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *PointMarker) HasColor() bool`

HasColor returns a boolean if a field has been set.

### GetAmenity

`func (o *PointMarker) GetAmenity() Amenity`

GetAmenity returns the Amenity field if non-nil, zero value otherwise.

### GetAmenityOk

`func (o *PointMarker) GetAmenityOk() (*Amenity, bool)`

GetAmenityOk returns a tuple with the Amenity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmenity

`func (o *PointMarker) SetAmenity(v Amenity)`

SetAmenity sets Amenity field to given value.

### HasAmenity

`func (o *PointMarker) HasAmenity() bool`

HasAmenity returns a boolean if a field has been set.

### GetKind

`func (o *PointMarker) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *PointMarker) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *PointMarker) SetKind(v string)`

SetKind sets Kind field to given value.


### GetParkingLot

`func (o *PointMarker) GetParkingLot() ParkingLot`

GetParkingLot returns the ParkingLot field if non-nil, zero value otherwise.

### GetParkingLotOk

`func (o *PointMarker) GetParkingLotOk() (*ParkingLot, bool)`

GetParkingLotOk returns a tuple with the ParkingLot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParkingLot

`func (o *PointMarker) SetParkingLot(v ParkingLot)`

SetParkingLot sets ParkingLot field to given value.

### HasParkingLot

`func (o *PointMarker) HasParkingLot() bool`

HasParkingLot returns a boolean if a field has been set.

### GetLabel

`func (o *PointMarker) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *PointMarker) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *PointMarker) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetSearchable

`func (o *PointMarker) GetSearchable() bool`

GetSearchable returns the Searchable field if non-nil, zero value otherwise.

### GetSearchableOk

`func (o *PointMarker) GetSearchableOk() (*bool, bool)`

GetSearchableOk returns a tuple with the Searchable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearchable

`func (o *PointMarker) SetSearchable(v bool)`

SetSearchable sets Searchable field to given value.

### HasSearchable

`func (o *PointMarker) HasSearchable() bool`

HasSearchable returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


