<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128568410/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T377606)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# How to: Add a Custom Legend Item to a Legend


This example demonstrates how to add a custom legend item to a legend.

![custom-legend-item-in-a-legend](img/custom-legend-item-in-a-legend.png)

To do this, create a new instance of the [CustomLegendItem](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.CustomLegendItem) class and add it to the [Legend.CustomItems](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.Legend.CustomItems) collection. Then configure the custom item. For example, you can use the [Text](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.CustomLegendItem.Text) property to set the item's text and the [MarkerTemplate](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.CustomLegendItem.MarkerTemplate) property to set the item's marker.


<!-- default file list -->
## Files to Look At

* [MainWindow.xaml](./CS/CustomLegendItemSample/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/CustomLegendItemSample/MainWindow.xaml))
<!-- default file list end -->

## Documentation 

- [CustomLegendItem](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.CustomLegendItem)
