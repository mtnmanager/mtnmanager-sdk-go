# MtnManager Go SDK

SDK for interacting with the MtnManager API, providing real-time access to your ski resort’s public operational data.

For more information, please visit [https://mtnmanager.com](https://mtnmanager.com)

## Installation

Install the following dependencies:

```sh
go get github.com/stretchr/testify/assert
go get golang.org/x/net/context
```

Put the package under your project folder and add the following in import:

```go
import mtnmanager "github.com/mtnmanager/mtnmanager-sdk-go/mtnmanager"
```

## Documentation for API Endpoints

All URIs are relative to *https://your-resort.mtnmanager.com*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*MtnManagerAPI* | [**GetFullReport**](docs/MtnManagerAPI.md#getfullreport) | **Get** /api/v1/report | Get full report
*MtnManagerAPI* | [**GetHours**](docs/MtnManagerAPI.md#gethours) | **Get** /api/v1/report/hours | Get operating hours
*MtnManagerAPI* | [**GetLifts**](docs/MtnManagerAPI.md#getlifts) | **Get** /api/v1/report/lifts | Get lifts
*MtnManagerAPI* | [**GetOverview**](docs/MtnManagerAPI.md#getoverview) | **Get** /api/v1/report/overview | Get overview
*MtnManagerAPI* | [**GetParkingLots**](docs/MtnManagerAPI.md#getparkinglots) | **Get** /api/v1/report/parking-lots | Get parking lots
*MtnManagerAPI* | [**GetRuns**](docs/MtnManagerAPI.md#getruns) | **Get** /api/v1/report/runs | Get runs
*MtnManagerAPI* | [**GetSnow**](docs/MtnManagerAPI.md#getsnow) | **Get** /api/v1/report/snow | Get snow conditions
*MtnManagerAPI* | [**GetSummerTrails**](docs/MtnManagerAPI.md#getsummertrails) | **Get** /api/v1/report/summer-trails | Get summer trails
*MtnManagerAPI* | [**GetTerrainParks**](docs/MtnManagerAPI.md#getterrainparks) | **Get** /api/v1/report/terrain-parks | Get terrain parks
*MtnManagerAPI* | [**GetTrailMap**](docs/MtnManagerAPI.md#gettrailmap) | **Get** /api/v1/report/trail-map/{uuid} | Get trail map
*MtnManagerAPI* | [**GetTrailMaps**](docs/MtnManagerAPI.md#gettrailmaps) | **Get** /api/v1/report/trail-maps | Get trail maps
*MtnManagerAPI* | [**GetWeather**](docs/MtnManagerAPI.md#getweather) | **Get** /api/v1/report/weather | Get weather


## Documentation For Models

 - [Amenity](docs/Amenity.md)
 - [AmenityCalendarEntry](docs/AmenityCalendarEntry.md)
 - [AmenityCategory](docs/AmenityCategory.md)
 - [AmenitySchedule](docs/AmenitySchedule.md)
 - [CalendarDay](docs/CalendarDay.md)
 - [ClosureReason](docs/ClosureReason.md)
 - [CurrentWeather](docs/CurrentWeather.md)
 - [CurrentWeatherImperial](docs/CurrentWeatherImperial.md)
 - [CurrentWeatherMetric](docs/CurrentWeatherMetric.md)
 - [DailyForecast](docs/DailyForecast.md)
 - [DailyForecastImperial](docs/DailyForecastImperial.md)
 - [DailyForecastMetric](docs/DailyForecastMetric.md)
 - [DayOfWeek](docs/DayOfWeek.md)
 - [FeatureSize](docs/FeatureSize.md)
 - [FeatureType](docs/FeatureType.md)
 - [FullReport](docs/FullReport.md)
 - [GeoControlPoint](docs/GeoControlPoint.md)
 - [HourlyForecast](docs/HourlyForecast.md)
 - [HourlyForecastImperial](docs/HourlyForecastImperial.md)
 - [HourlyForecastMetric](docs/HourlyForecastMetric.md)
 - [LabelOffset](docs/LabelOffset.md)
 - [Lift](docs/Lift.md)
 - [LiftStatus](docs/LiftStatus.md)
 - [LiftType](docs/LiftType.md)
 - [MarkerIcon](docs/MarkerIcon.md)
 - [OperatingHours](docs/OperatingHours.md)
 - [Overview](docs/Overview.md)
 - [OverviewLifts](docs/OverviewLifts.md)
 - [OverviewNews](docs/OverviewNews.md)
 - [OverviewRuns](docs/OverviewRuns.md)
 - [OverviewSummerTrails](docs/OverviewSummerTrails.md)
 - [OverviewTerrainParks](docs/OverviewTerrainParks.md)
 - [ParkingLot](docs/ParkingLot.md)
 - [ParkingLotStatus](docs/ParkingLotStatus.md)
 - [PathUuid](docs/PathUuid.md)
 - [PointMarker](docs/PointMarker.md)
 - [PointMarkerOneOf](docs/PointMarkerOneOf.md)
 - [PointMarkerOneOf1](docs/PointMarkerOneOf1.md)
 - [PointMarkerOneOf2](docs/PointMarkerOneOf2.md)
 - [Region](docs/Region.md)
 - [ResortInfo](docs/ResortInfo.md)
 - [ResortStatus](docs/ResortStatus.md)
 - [Run](docs/Run.md)
 - [RunDifficulty](docs/RunDifficulty.md)
 - [RunStatus](docs/RunStatus.md)
 - [Schedule](docs/Schedule.md)
 - [SeasonType](docs/SeasonType.md)
 - [SnowMetrics](docs/SnowMetrics.md)
 - [SnowReport](docs/SnowReport.md)
 - [SummerTrail](docs/SummerTrail.md)
 - [SummerTrailDifficulty](docs/SummerTrailDifficulty.md)
 - [SummerTrailStatus](docs/SummerTrailStatus.md)
 - [SummerTrailType](docs/SummerTrailType.md)
 - [SurfaceCondition](docs/SurfaceCondition.md)
 - [TerrainPark](docs/TerrainPark.md)
 - [TerrainParkFeature](docs/TerrainParkFeature.md)
 - [TerrainParkFeatureStatus](docs/TerrainParkFeatureStatus.md)
 - [TerrainParkStatus](docs/TerrainParkStatus.md)
 - [TrailMap](docs/TrailMap.md)
 - [TrailMapElement](docs/TrailMapElement.md)
 - [TrailMapElementOneOf](docs/TrailMapElementOneOf.md)
 - [TrailMapElementOneOf1](docs/TrailMapElementOneOf1.md)
 - [TrailMapElementOneOf2](docs/TrailMapElementOneOf2.md)
 - [TrailMapElementOneOf3](docs/TrailMapElementOneOf3.md)
 - [TrailMapElementOneOf4](docs/TrailMapElementOneOf4.md)
 - [TrailMapSummary](docs/TrailMapSummary.md)
 - [UnitPreference](docs/UnitPreference.md)
 - [Weather](docs/Weather.md)
 - [WeatherConditionCode](docs/WeatherConditionCode.md)


## Documentation For Authorization

Endpoints do not require authorization.
