# TrailMapElementOneOf4

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** |  | 
**Uuid** | **string** |  | 
**X** | **float64** |  | 
**Y** | **float64** |  | 
**Icon** | Pointer to [**NullableMarkerIcon**](MarkerIcon.md) |  | [optional] 
**Color** | Pointer to **NullableString** |  | [optional] 
**Amenity** | Pointer to [**NullableAmenity**](Amenity.md) |  | [optional] 
**GroupLabel** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewTrailMapElementOneOf4

`func NewTrailMapElementOneOf4(type_ string, uuid string, x float64, y float64, ) *TrailMapElementOneOf4`

NewTrailMapElementOneOf4 instantiates a new TrailMapElementOneOf4 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrailMapElementOneOf4WithDefaults

`func NewTrailMapElementOneOf4WithDefaults() *TrailMapElementOneOf4`

NewTrailMapElementOneOf4WithDefaults instantiates a new TrailMapElementOneOf4 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *TrailMapElementOneOf4) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TrailMapElementOneOf4) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TrailMapElementOneOf4) SetType(v string)`

SetType sets Type field to given value.


### GetUuid

`func (o *TrailMapElementOneOf4) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *TrailMapElementOneOf4) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *TrailMapElementOneOf4) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetX

`func (o *TrailMapElementOneOf4) GetX() float64`

GetX returns the X field if non-nil, zero value otherwise.

### GetXOk

`func (o *TrailMapElementOneOf4) GetXOk() (*float64, bool)`

GetXOk returns a tuple with the X field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetX

`func (o *TrailMapElementOneOf4) SetX(v float64)`

SetX sets X field to given value.


### GetY

`func (o *TrailMapElementOneOf4) GetY() float64`

GetY returns the Y field if non-nil, zero value otherwise.

### GetYOk

`func (o *TrailMapElementOneOf4) GetYOk() (*float64, bool)`

GetYOk returns a tuple with the Y field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetY

`func (o *TrailMapElementOneOf4) SetY(v float64)`

SetY sets Y field to given value.


### GetIcon

`func (o *TrailMapElementOneOf4) GetIcon() MarkerIcon`

GetIcon returns the Icon field if non-nil, zero value otherwise.

### GetIconOk

`func (o *TrailMapElementOneOf4) GetIconOk() (*MarkerIcon, bool)`

GetIconOk returns a tuple with the Icon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcon

`func (o *TrailMapElementOneOf4) SetIcon(v MarkerIcon)`

SetIcon sets Icon field to given value.

### HasIcon

`func (o *TrailMapElementOneOf4) HasIcon() bool`

HasIcon returns a boolean if a field has been set.

### SetIconNil

`func (o *TrailMapElementOneOf4) SetIconNil(b bool)`

 SetIconNil sets the value for Icon to be an explicit nil

### UnsetIcon
`func (o *TrailMapElementOneOf4) UnsetIcon()`

UnsetIcon ensures that no value is present for Icon, not even an explicit nil
### GetColor

`func (o *TrailMapElementOneOf4) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *TrailMapElementOneOf4) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *TrailMapElementOneOf4) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *TrailMapElementOneOf4) HasColor() bool`

HasColor returns a boolean if a field has been set.

### SetColorNil

`func (o *TrailMapElementOneOf4) SetColorNil(b bool)`

 SetColorNil sets the value for Color to be an explicit nil

### UnsetColor
`func (o *TrailMapElementOneOf4) UnsetColor()`

UnsetColor ensures that no value is present for Color, not even an explicit nil
### GetAmenity

`func (o *TrailMapElementOneOf4) GetAmenity() Amenity`

GetAmenity returns the Amenity field if non-nil, zero value otherwise.

### GetAmenityOk

`func (o *TrailMapElementOneOf4) GetAmenityOk() (*Amenity, bool)`

GetAmenityOk returns a tuple with the Amenity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmenity

`func (o *TrailMapElementOneOf4) SetAmenity(v Amenity)`

SetAmenity sets Amenity field to given value.

### HasAmenity

`func (o *TrailMapElementOneOf4) HasAmenity() bool`

HasAmenity returns a boolean if a field has been set.

### SetAmenityNil

`func (o *TrailMapElementOneOf4) SetAmenityNil(b bool)`

 SetAmenityNil sets the value for Amenity to be an explicit nil

### UnsetAmenity
`func (o *TrailMapElementOneOf4) UnsetAmenity()`

UnsetAmenity ensures that no value is present for Amenity, not even an explicit nil
### GetGroupLabel

`func (o *TrailMapElementOneOf4) GetGroupLabel() string`

GetGroupLabel returns the GroupLabel field if non-nil, zero value otherwise.

### GetGroupLabelOk

`func (o *TrailMapElementOneOf4) GetGroupLabelOk() (*string, bool)`

GetGroupLabelOk returns a tuple with the GroupLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupLabel

`func (o *TrailMapElementOneOf4) SetGroupLabel(v string)`

SetGroupLabel sets GroupLabel field to given value.

### HasGroupLabel

`func (o *TrailMapElementOneOf4) HasGroupLabel() bool`

HasGroupLabel returns a boolean if a field has been set.

### SetGroupLabelNil

`func (o *TrailMapElementOneOf4) SetGroupLabelNil(b bool)`

 SetGroupLabelNil sets the value for GroupLabel to be an explicit nil

### UnsetGroupLabel
`func (o *TrailMapElementOneOf4) UnsetGroupLabel()`

UnsetGroupLabel ensures that no value is present for GroupLabel, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


