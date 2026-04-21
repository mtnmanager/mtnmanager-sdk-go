# PointMarkerOneOf

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** |  | 
**X** | **float64** |  | 
**Y** | **float64** |  | 
**Icon** | Pointer to [**NullableMarkerIcon**](MarkerIcon.md) |  | [optional] 
**Color** | Pointer to **NullableString** |  | [optional] 
**Amenity** | Pointer to [**NullableAmenity**](Amenity.md) |  | [optional] 
**Kind** | **string** |  | 

## Methods

### NewPointMarkerOneOf

`func NewPointMarkerOneOf(uuid string, x float64, y float64, kind string, ) *PointMarkerOneOf`

NewPointMarkerOneOf instantiates a new PointMarkerOneOf object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPointMarkerOneOfWithDefaults

`func NewPointMarkerOneOfWithDefaults() *PointMarkerOneOf`

NewPointMarkerOneOfWithDefaults instantiates a new PointMarkerOneOf object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *PointMarkerOneOf) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *PointMarkerOneOf) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *PointMarkerOneOf) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetX

`func (o *PointMarkerOneOf) GetX() float64`

GetX returns the X field if non-nil, zero value otherwise.

### GetXOk

`func (o *PointMarkerOneOf) GetXOk() (*float64, bool)`

GetXOk returns a tuple with the X field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetX

`func (o *PointMarkerOneOf) SetX(v float64)`

SetX sets X field to given value.


### GetY

`func (o *PointMarkerOneOf) GetY() float64`

GetY returns the Y field if non-nil, zero value otherwise.

### GetYOk

`func (o *PointMarkerOneOf) GetYOk() (*float64, bool)`

GetYOk returns a tuple with the Y field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetY

`func (o *PointMarkerOneOf) SetY(v float64)`

SetY sets Y field to given value.


### GetIcon

`func (o *PointMarkerOneOf) GetIcon() MarkerIcon`

GetIcon returns the Icon field if non-nil, zero value otherwise.

### GetIconOk

`func (o *PointMarkerOneOf) GetIconOk() (*MarkerIcon, bool)`

GetIconOk returns a tuple with the Icon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcon

`func (o *PointMarkerOneOf) SetIcon(v MarkerIcon)`

SetIcon sets Icon field to given value.

### HasIcon

`func (o *PointMarkerOneOf) HasIcon() bool`

HasIcon returns a boolean if a field has been set.

### SetIconNil

`func (o *PointMarkerOneOf) SetIconNil(b bool)`

 SetIconNil sets the value for Icon to be an explicit nil

### UnsetIcon
`func (o *PointMarkerOneOf) UnsetIcon()`

UnsetIcon ensures that no value is present for Icon, not even an explicit nil
### GetColor

`func (o *PointMarkerOneOf) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *PointMarkerOneOf) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *PointMarkerOneOf) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *PointMarkerOneOf) HasColor() bool`

HasColor returns a boolean if a field has been set.

### SetColorNil

`func (o *PointMarkerOneOf) SetColorNil(b bool)`

 SetColorNil sets the value for Color to be an explicit nil

### UnsetColor
`func (o *PointMarkerOneOf) UnsetColor()`

UnsetColor ensures that no value is present for Color, not even an explicit nil
### GetAmenity

`func (o *PointMarkerOneOf) GetAmenity() Amenity`

GetAmenity returns the Amenity field if non-nil, zero value otherwise.

### GetAmenityOk

`func (o *PointMarkerOneOf) GetAmenityOk() (*Amenity, bool)`

GetAmenityOk returns a tuple with the Amenity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmenity

`func (o *PointMarkerOneOf) SetAmenity(v Amenity)`

SetAmenity sets Amenity field to given value.

### HasAmenity

`func (o *PointMarkerOneOf) HasAmenity() bool`

HasAmenity returns a boolean if a field has been set.

### SetAmenityNil

`func (o *PointMarkerOneOf) SetAmenityNil(b bool)`

 SetAmenityNil sets the value for Amenity to be an explicit nil

### UnsetAmenity
`func (o *PointMarkerOneOf) UnsetAmenity()`

UnsetAmenity ensures that no value is present for Amenity, not even an explicit nil
### GetKind

`func (o *PointMarkerOneOf) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *PointMarkerOneOf) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *PointMarkerOneOf) SetKind(v string)`

SetKind sets Kind field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


