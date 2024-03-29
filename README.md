# Quickstart Sample for Android

### Description
The Map Suite Android Edition illustrated QuickStart Guide will guide you through the process of creating a sample application and will help you become familiar with Map Suite. This edition of the QuickStart Guide supports Android Edition 10.0.0 and higher and will show you how to create an Android application using Map Suite Android Edition.

Please refer to [Wiki](http://wiki.thinkgeo.com/wiki/map_suite_mobile_for_android) for the details.

![Screenshot](https://github.com/ThinkGeo/QuickstartSample-ForAndroid/blob/master/Screenshot.PNG)

### Requirements
This sample makes use of the following NuGet Packages

[MapSuite 10.0.0](https://www.nuget.org/packages?q=ThinkGeo)

### About the Code
```csharp
LayerOverlay overlay = new LayerOverlay();
overlay.Opacity = 0.8;
overlay.Layers.Add(worldLayer);
overlay.Layers.Add(capitalLayer);
// Add the label layer to LayerOverlay.
overlay.Layers.Add(capitalLabelLayer);
```
### Getting Help

- [Map Suite mobile for Android Wiki Resources](http://wiki.thinkgeo.com/wiki/map_suite_mobile_for_android)
- [Map Suite mobile for Android Product Description](https://thinkgeo.com/ui-controls#mobile-platforms)
- [ThinkGeo Community Site](http://community.thinkgeo.com/)
- [ThinkGeo Web Site](http://www.thinkgeo.com)

### Key APIs
This example makes use of the following APIs:

- [ThinkGeo.MapSuite.Android.MapView](http://wiki.thinkgeo.com/wiki/api/thinkgeo.mapsuite.android.mapview)
- [ThinkGeo.MapSuite.Android.LayerOverlay](http://wiki.thinkgeo.com/wiki/api/thinkgeo.mapsuite.android.layeroverlay)
- [ThinkGeo.MapSuite.Android.WorldStreetsAndImageryOverlay](http://wiki.thinkgeo.com/wiki/api/thinkgeo.mapsuite.android.worldstreetsandimageryoverlay)

### About Map Suite
Map Suite is a set of powerful development components and services for the .Net Framework.

### About ThinkGeo
ThinkGeo is a GIS (Geographic Information Systems) company founded in 2004 and located in Frisco, TX. Our clients are in more than 40 industries including agriculture, energy, transportation, government, engineering, software development, and defense.
