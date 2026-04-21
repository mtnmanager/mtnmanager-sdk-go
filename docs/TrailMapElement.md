# TrailMapElement

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** |  | 
**Uuid** | **string** |  | 
**Points** | **[]float64** |  | 
**Tension** | Pointer to **float64** |  | [optional] 
**Lift** | Pointer to [**Lift**](Lift.md) |  | [optional] 
**Run** | Pointer to [**Run**](Run.md) |  | [optional] 
**LabelOffset** | Pointer to [**LabelOffset**](LabelOffset.md) |  | [optional] 
**TerrainPark** | Pointer to [**TerrainPark**](TerrainPark.md) |  | [optional] 
**SummerTrail** | Pointer to [**SummerTrail**](SummerTrail.md) |  | [optional] 
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

### NewTrailMapElement

`func NewTrailMapElement(type_ string, uuid string, points []float64, x float64, y float64, kind string, label string, ) *TrailMapElement`

NewTrailMapElement instantiates a new TrailMapElement object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrailMapElementWithDefaults

`func NewTrailMapElementWithDefaults() *TrailMapElement`

NewTrailMapElementWithDefaults instantiates a new TrailMapElement object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *TrailMapElement) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TrailMapElement) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TrailMapElement) SetType(v string)`

SetType sets Type field to given value.


### GetUuid

`func (o *TrailMapElement) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *TrailMapElement) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *TrailMapElement) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetPoints

`func (o *TrailMapElement) GetPoints() []float64`

GetPoints returns the Points field if non-nil, zero value otherwise.

### GetPointsOk

`func (o *TrailMapElement) GetPointsOk() (*[]float64, bool)`

GetPointsOk returns a tuple with the Points field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoints

`func (o *TrailMapElement) SetPoints(v []float64)`

SetPoints sets Points field to given value.


### GetTension

`func (o *TrailMapElement) GetTension() float64`

GetTension returns the Tension field if non-nil, zero value otherwise.

### GetTensionOk

`func (o *TrailMapElement) GetTensionOk() (*float64, bool)`

GetTensionOk returns a tuple with the Tension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTension

`func (o *TrailMapElement) SetTension(v float64)`

SetTension sets Tension field to given value.

### HasTension

`func (o *TrailMapElement) HasTension() bool`

HasTension returns a boolean if a field has been set.

### GetLift

`func (o *TrailMapElement) GetLift() Lift`

GetLift returns the Lift field if non-nil, zero value otherwise.

### GetLiftOk

`func (o *TrailMapElement) GetLiftOk() (*Lift, bool)`

GetLiftOk returns a tuple with the Lift field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLift

`func (o *TrailMapElement) SetLift(v Lift)`

SetLift sets Lift field to given value.

### HasLift

`func (o *TrailMapElement) HasLift() bool`

HasLift returns a boolean if a field has been set.

### GetRun

`func (o *TrailMapElement) GetRun() Run`

GetRun returns the Run field if non-nil, zero value otherwise.

### GetRunOk

`func (o *TrailMapElement) GetRunOk() (*Run, bool)`

GetRunOk returns a tuple with the Run field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRun

`func (o *TrailMapElement) SetRun(v Run)`

SetRun sets Run field to given value.

### HasRun

`func (o *TrailMapElement) HasRun() bool`

HasRun returns a boolean if a field has been set.

### GetLabelOffset

`func (o *TrailMapElement) GetLabelOffset() LabelOffset`

GetLabelOffset returns the LabelOffset field if non-nil, zero value otherwise.

### GetLabelOffsetOk

`func (o *TrailMapElement) GetLabelOffsetOk() (*LabelOffset, bool)`

GetLabelOffsetOk returns a tuple with the LabelOffset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelOffset

`func (o *TrailMapElement) SetLabelOffset(v LabelOffset)`

SetLabelOffset sets LabelOffset field to given value.

### HasLabelOffset

`func (o *TrailMapElement) HasLabelOffset() bool`

HasLabelOffset returns a boolean if a field has been set.

### GetTerrainPark

`func (o *TrailMapElement) GetTerrainPark() TerrainPark`

GetTerrainPark returns the TerrainPark field if non-nil, zero value otherwise.

### GetTerrainParkOk

`func (o *TrailMapElement) GetTerrainParkOk() (*TerrainPark, bool)`

GetTerrainParkOk returns a tuple with the TerrainPark field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerrainPark

`func (o *TrailMapElement) SetTerrainPark(v TerrainPark)`

SetTerrainPark sets TerrainPark field to given value.

### HasTerrainPark

`func (o *TrailMapElement) HasTerrainPark() bool`

HasTerrainPark returns a boolean if a field has been set.

### GetSummerTrail

`func (o *TrailMapElement) GetSummerTrail() SummerTrail`

GetSummerTrail returns the SummerTrail field if non-nil, zero value otherwise.

### GetSummerTrailOk

`func (o *TrailMapElement) GetSummerTrailOk() (*SummerTrail, bool)`

GetSummerTrailOk returns a tuple with the SummerTrail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummerTrail

`func (o *TrailMapElement) SetSummerTrail(v SummerTrail)`

SetSummerTrail sets SummerTrail field to given value.

### HasSummerTrail

`func (o *TrailMapElement) HasSummerTrail() bool`

HasSummerTrail returns a boolean if a field has been set.

### GetX

`func (o *TrailMapElement) GetX() float64`

GetX returns the X field if non-nil, zero value otherwise.

### GetXOk

`func (o *TrailMapElement) GetXOk() (*float64, bool)`

GetXOk returns a tuple with the X field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetX

`func (o *TrailMapElement) SetX(v float64)`

SetX sets X field to given value.


### GetY

`func (o *TrailMapElement) GetY() float64`

GetY returns the Y field if non-nil, zero value otherwise.

### GetYOk

`func (o *TrailMapElement) GetYOk() (*float64, bool)`

GetYOk returns a tuple with the Y field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetY

`func (o *TrailMapElement) SetY(v float64)`

SetY sets Y field to given value.


### GetIcon

`func (o *TrailMapElement) GetIcon() MarkerIcon`

GetIcon returns the Icon field if non-nil, zero value otherwise.

### GetIconOk

`func (o *TrailMapElement) GetIconOk() (*MarkerIcon, bool)`

GetIconOk returns a tuple with the Icon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcon

`func (o *TrailMapElement) SetIcon(v MarkerIcon)`

SetIcon sets Icon field to given value.

### HasIcon

`func (o *TrailMapElement) HasIcon() bool`

HasIcon returns a boolean if a field has been set.

### GetColor

`func (o *TrailMapElement) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *TrailMapElement) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *TrailMapElement) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *TrailMapElement) HasColor() bool`

HasColor returns a boolean if a field has been set.

### GetAmenity

`func (o *TrailMapElement) GetAmenity() Amenity`

GetAmenity returns the Amenity field if non-nil, zero value otherwise.

### GetAmenityOk

`func (o *TrailMapElement) GetAmenityOk() (*Amenity, bool)`

GetAmenityOk returns a tuple with the Amenity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmenity

`func (o *TrailMapElement) SetAmenity(v Amenity)`

SetAmenity sets Amenity field to given value.

### HasAmenity

`func (o *TrailMapElement) HasAmenity() bool`

HasAmenity returns a boolean if a field has been set.

### GetKind

`func (o *TrailMapElement) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *TrailMapElement) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *TrailMapElement) SetKind(v string)`

SetKind sets Kind field to given value.


### GetParkingLot

`func (o *TrailMapElement) GetParkingLot() ParkingLot`

GetParkingLot returns the ParkingLot field if non-nil, zero value otherwise.

### GetParkingLotOk

`func (o *TrailMapElement) GetParkingLotOk() (*ParkingLot, bool)`

GetParkingLotOk returns a tuple with the ParkingLot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParkingLot

`func (o *TrailMapElement) SetParkingLot(v ParkingLot)`

SetParkingLot sets ParkingLot field to given value.

### HasParkingLot

`func (o *TrailMapElement) HasParkingLot() bool`

HasParkingLot returns a boolean if a field has been set.

### GetLabel

`func (o *TrailMapElement) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *TrailMapElement) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *TrailMapElement) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetSearchable

`func (o *TrailMapElement) GetSearchable() bool`

GetSearchable returns the Searchable field if non-nil, zero value otherwise.

### GetSearchableOk

`func (o *TrailMapElement) GetSearchableOk() (*bool, bool)`

GetSearchableOk returns a tuple with the Searchable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearchable

`func (o *TrailMapElement) SetSearchable(v bool)`

SetSearchable sets Searchable field to given value.

### HasSearchable

`func (o *TrailMapElement) HasSearchable() bool`

HasSearchable returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


