# D3 v4 Race Chart

Running on [gh-pages](https://shanegibney.github.io/RaceChart/)

### To do:

* Add Isanuk's [zoom and pan](https://bl.ocks.org/misanuk/fc39ecc400eed9a3300d807783ef7607) to main chart. Have already implemented this in this [repo](https://github.com/shanegibney/d3RaceChard3barChartZoomBrushScaleBand)
  * difficulty with scaleBand(), may need to completely build feature from scratch for smooth zooming and panning.
* Add [Update Pattern](https://github.com/shanegibney/D3-v4-Bar-Chart-Update-Pattern) and Bootstrap nav bar to enable users to switch between different race JSON files.
* Improve UI of sort buttons
* Make bars center on ticks regardless of number objects in data
* Filter main bar chart and table by clicking on pie chart segments and clubs bar chart. This will involve filter original data and then implementing update pattern.
* Prevent mouseover until animations are complete. Simply add a delay which is equal to running time of animation. Delay will start at same time as animation.
* Fix tooltip on club bar chart. Make it independent of tooltips on main bar chart.
* Correct right y-axis point axis.
* Make main bar chart sortable on points also

<img width="1436" alt="screen shot 2017-09-03 at 16 40 35" src="https://user-images.githubusercontent.com/17167992/30004431-eb7fb13e-90c6-11e7-8119-1e65e3dc73c3.png">

<img width="1427" alt="screen shot 2017-09-03 at 16 39 52" src="https://user-images.githubusercontent.com/17167992/30004416-c0a4cb98-90c6-11e7-8aa9-9016bfa54f17.png">
