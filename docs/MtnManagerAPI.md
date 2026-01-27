# \MtnManagerAPI

All URIs are relative to *https://your-resort.mtnmanager.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetFullReport**](MtnManagerAPI.md#GetFullReport) | **Get** /api/v1/report | Get full report
[**GetHours**](MtnManagerAPI.md#GetHours) | **Get** /api/v1/report/hours | Get operating hours
[**GetLifts**](MtnManagerAPI.md#GetLifts) | **Get** /api/v1/report/lifts | Get lifts
[**GetOverview**](MtnManagerAPI.md#GetOverview) | **Get** /api/v1/report/overview | Get overview
[**GetRuns**](MtnManagerAPI.md#GetRuns) | **Get** /api/v1/report/runs | Get runs
[**GetSnow**](MtnManagerAPI.md#GetSnow) | **Get** /api/v1/report/snow | Get snow conditions
[**GetSummerTrails**](MtnManagerAPI.md#GetSummerTrails) | **Get** /api/v1/report/summer-trails | Get summer trails
[**GetTerrainParks**](MtnManagerAPI.md#GetTerrainParks) | **Get** /api/v1/report/terrain-parks | Get terrain parks
[**GetWeather**](MtnManagerAPI.md#GetWeather) | **Get** /api/v1/report/weather | Get weather



## GetFullReport

> FullReport GetFullReport(ctx).Execute()

Get full report

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetFullReport(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetFullReport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFullReport`: FullReport
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetFullReport`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetFullReportRequest struct via the builder pattern


### Return type

[**FullReport**](FullReport.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetHours

> OperatingHours GetHours(ctx).Execute()

Get operating hours

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetHours(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetHours``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetHours`: OperatingHours
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetHours`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetHoursRequest struct via the builder pattern


### Return type

[**OperatingHours**](OperatingHours.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLifts

> []Lift GetLifts(ctx).Execute()

Get lifts

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetLifts(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetLifts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLifts`: []Lift
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetLifts`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetLiftsRequest struct via the builder pattern


### Return type

[**[]Lift**](Lift.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOverview

> Overview GetOverview(ctx).Execute()

Get overview

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetOverview(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetOverview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOverview`: Overview
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetOverview`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetOverviewRequest struct via the builder pattern


### Return type

[**Overview**](Overview.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRuns

> []Run GetRuns(ctx).Execute()

Get runs

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetRuns(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetRuns``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRuns`: []Run
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetRuns`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetRunsRequest struct via the builder pattern


### Return type

[**[]Run**](Run.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSnow

> []SnowReport GetSnow(ctx).Execute()

Get snow conditions

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetSnow(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetSnow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSnow`: []SnowReport
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetSnow`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetSnowRequest struct via the builder pattern


### Return type

[**[]SnowReport**](SnowReport.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSummerTrails

> []SummerTrail GetSummerTrails(ctx).Execute()

Get summer trails

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetSummerTrails(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetSummerTrails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSummerTrails`: []SummerTrail
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetSummerTrails`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetSummerTrailsRequest struct via the builder pattern


### Return type

[**[]SummerTrail**](SummerTrail.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTerrainParks

> []TerrainPark GetTerrainParks(ctx).Execute()

Get terrain parks

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetTerrainParks(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetTerrainParks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTerrainParks`: []TerrainPark
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetTerrainParks`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetTerrainParksRequest struct via the builder pattern


### Return type

[**[]TerrainPark**](TerrainPark.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetWeather

> Weather GetWeather(ctx).Execute()

Get weather

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MtnManagerAPI.GetWeather(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MtnManagerAPI.GetWeather``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWeather`: Weather
	fmt.Fprintf(os.Stdout, "Response from `MtnManagerAPI.GetWeather`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetWeatherRequest struct via the builder pattern


### Return type

[**Weather**](Weather.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

