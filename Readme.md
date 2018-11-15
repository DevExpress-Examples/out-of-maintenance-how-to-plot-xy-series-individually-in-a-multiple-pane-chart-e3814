<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/WpfApplication/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/WpfApplication/MainWindow.xaml))
<!-- default file list end -->
# How to plot XY-series individually in a multiple pane chart


<p>This example demonstrates the capability of XY-series to be plotted individually in a multiple pane chart.</p><br />



<h3>Description</h3>

<p>To accomplish this task, it is necessary to bind each XY-series (e.g., <a href="http://help.devexpress.com/#WPF/clsDevExpressXpfChartsAreaSeries2Dtopic"><u>AreaSeries2D</u></a>, <a href="http://help.devexpress.com/#WPF/clsDevExpressXpfChartsLineSeries2Dtopic"><u>LineSeries2D</u></a>, <a href="http://help.devexpress.com/#WPF/clsDevExpressXpfChartsBarSideBySideSeries2Dtopic"><u>BarSideBySideSeries2D</u></a> objects) to a corresponding pane using the <a href="http://help.devexpress.com/#WPF/DevExpressXpfChartsXYDiagram2D_SeriesPanetopic"><u>XYDiagram2D.SeriesPane</u></a> attached property. </p>

<br/>


