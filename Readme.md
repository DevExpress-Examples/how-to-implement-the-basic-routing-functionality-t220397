<!-- default file list -->
*Files to look at*:

* **[MainPage.xaml](./CS/Routing/MainPage.xaml) (VB: [MainPage.xaml](./VB/Routing/MainPage.xaml))**
* [MainPage.xaml.cs](./CS/Routing/MainPage.xaml.cs) (VB: [MainPage.xaml.vb](./VB/Routing/MainPage.xaml.vb))
<!-- default file list end -->
# How to implement the basic routing functionality


This example demonstrates how to implement the basic routing functionality.<br /><br />To do this, create an <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapInformationLayertopic">InformationLayer</a> object and add it to the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfMapMapControl_Layerstopic">MapControl.Layers</a> collection. Then create a <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapBingRouteDataProvidertopic">BingRouteDataProvider</a> object specify its parameters, and assign it to the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfMapInformationLayer_DataProvidertopic">InformationLayer.DataProvider</a> property.<br />To build a route, call the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfMapBingRouteDataProvider_CalculateRoutetopic">BingRouteDataProvider.CalculateRoute</a> method.

<br/>


