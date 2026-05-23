# MobileAppResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Banners** | [**[]MobileAppBanner**](MobileAppBanner.md) | Banners shown in the mobile app, in display order. | 

## Methods

### NewMobileAppResponse

`func NewMobileAppResponse(banners []MobileAppBanner, ) *MobileAppResponse`

NewMobileAppResponse instantiates a new MobileAppResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMobileAppResponseWithDefaults

`func NewMobileAppResponseWithDefaults() *MobileAppResponse`

NewMobileAppResponseWithDefaults instantiates a new MobileAppResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBanners

`func (o *MobileAppResponse) GetBanners() []MobileAppBanner`

GetBanners returns the Banners field if non-nil, zero value otherwise.

### GetBannersOk

`func (o *MobileAppResponse) GetBannersOk() (*[]MobileAppBanner, bool)`

GetBannersOk returns a tuple with the Banners field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBanners

`func (o *MobileAppResponse) SetBanners(v []MobileAppBanner)`

SetBanners sets Banners field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


