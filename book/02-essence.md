# Essence (Solution)








## Delivery Metrics 





### Overview 

#### Distribution of priorities across projects

The [Tree Map](https://en.wikipedia.org/wiki/Treemapping) of the entire dataset
provides an excellent solution level overview of the total number of 
work items (Stories) that flowed in across different projects and priorities.




<div class="figure" style="text-align: center">
<img src="02-essence_files/figure-html/essence-stories-summary-treemap-fig-1.png" alt="Summary Tree Map" width="80%" />
<p class="caption">(\#fig:essence-stories-summary-treemap-fig)Summary Tree Map</p>
</div>


###  Cycle Time


#### Summary

The below [Five-number summary](https://en.wikipedia.org/wiki/Five-number_summary) 
will provide a high level distribution of the cycle times. 
The 75% Qartile value is significant because that is the number which you can 
typically see as the turn around time (TAT) to service a work item.

<table class="table table-striped" style="width: auto !important; margin-left: auto; margin-right: auto;">
<caption>(\#tab:essence-cycle-time-summ)5 Number Summary</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Type </th>
   <th style="text-align:left;"> Priority </th>
   <th style="text-align:right;"> Count </th>
   <th style="text-align:right;"> Min </th>
   <th style="text-align:right;"> LoQ </th>
   <th style="text-align:right;"> Med </th>
   <th style="text-align:right;"> UpQ </th>
   <th style="text-align:right;"> Max </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Epic </td>
   <td style="text-align:left;"> High </td>
   <td style="text-align:right;"> 4 </td>
   <td style="text-align:right;"> 68 </td>
   <td style="text-align:right;"> 95.0 </td>
   <td style="text-align:right;"> 112.5 </td>
   <td style="text-align:right;"> 207.0 </td>
   <td style="text-align:right;"> 465 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Epic </td>
   <td style="text-align:left;"> Medium </td>
   <td style="text-align:right;"> 5 </td>
   <td style="text-align:right;"> 2 </td>
   <td style="text-align:right;"> 36.0 </td>
   <td style="text-align:right;"> 118.0 </td>
   <td style="text-align:right;"> 184.0 </td>
   <td style="text-align:right;"> 340 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Story </td>
   <td style="text-align:left;"> Critical </td>
   <td style="text-align:right;"> 53 </td>
   <td style="text-align:right;"> 9 </td>
   <td style="text-align:right;"> 55.0 </td>
   <td style="text-align:right;"> 92.0 </td>
   <td style="text-align:right;"> 149.0 </td>
   <td style="text-align:right;"> 295 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Story </td>
   <td style="text-align:left;"> High </td>
   <td style="text-align:right;"> 491 </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 39.5 </td>
   <td style="text-align:right;"> 78.0 </td>
   <td style="text-align:right;"> 115.5 </td>
   <td style="text-align:right;"> 469 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Story </td>
   <td style="text-align:left;"> Medium </td>
   <td style="text-align:right;"> 1413 </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 27.0 </td>
   <td style="text-align:right;"> 79.0 </td>
   <td style="text-align:right;"> 126.0 </td>
   <td style="text-align:right;"> 385 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Story </td>
   <td style="text-align:left;"> Low </td>
   <td style="text-align:right;"> 13 </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 16.0 </td>
   <td style="text-align:right;"> 93.0 </td>
   <td style="text-align:right;"> 276.0 </td>
   <td style="text-align:right;"> 343 </td>
  </tr>
</tbody>
</table>

#### Epics


<div class="figure" style="text-align: center">
<img src="02-essence_files/figure-html/essence-epics-cycle-time-trend-fig-1.png" alt="Cycle Time Trend" width="80%" />
<p class="caption">(\#fig:essence-epics-cycle-time-trend-fig)Cycle Time Trend</p>
</div>


<table class="table table-striped" style="width: auto !important; margin-left: auto; margin-right: auto;">
<caption>(\#tab:essence-epics-summary-metrics)5 Number Summary</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Priority </th>
   <th style="text-align:right;"> Min </th>
   <th style="text-align:right;"> LoQ </th>
   <th style="text-align:right;"> Med </th>
   <th style="text-align:right;"> UpQ </th>
   <th style="text-align:right;"> Max </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> High </td>
   <td style="text-align:right;"> 68 </td>
   <td style="text-align:right;"> 95 </td>
   <td style="text-align:right;"> 112.5 </td>
   <td style="text-align:right;"> 207 </td>
   <td style="text-align:right;"> 465 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Medium </td>
   <td style="text-align:right;"> 2 </td>
   <td style="text-align:right;"> 36 </td>
   <td style="text-align:right;"> 118.0 </td>
   <td style="text-align:right;"> 184 </td>
   <td style="text-align:right;"> 340 </td>
  </tr>
</tbody>
</table>

#### Stories

<div class="figure" style="text-align: center">
<img src="02-essence_files/figure-html/essence-stories-cycle-time-trend-fig-1.png" alt="Cycle Time Trend" width="80%" />
<p class="caption">(\#fig:essence-stories-cycle-time-trend-fig)Cycle Time Trend</p>
</div>


<table class="table table-striped" style="width: auto !important; margin-left: auto; margin-right: auto;">
<caption>(\#tab:essence-story-summary-metrics)5 Number Summary</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Priority </th>
   <th style="text-align:right;"> Min </th>
   <th style="text-align:right;"> LoQ </th>
   <th style="text-align:right;"> Med </th>
   <th style="text-align:right;"> UpQ </th>
   <th style="text-align:right;"> Max </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Critical </td>
   <td style="text-align:right;"> 9 </td>
   <td style="text-align:right;"> 55.0 </td>
   <td style="text-align:right;"> 92 </td>
   <td style="text-align:right;"> 149.0 </td>
   <td style="text-align:right;"> 295 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> High </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 39.5 </td>
   <td style="text-align:right;"> 78 </td>
   <td style="text-align:right;"> 115.5 </td>
   <td style="text-align:right;"> 469 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Medium </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 27.0 </td>
   <td style="text-align:right;"> 79 </td>
   <td style="text-align:right;"> 126.0 </td>
   <td style="text-align:right;"> 385 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Low </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 16.0 </td>
   <td style="text-align:right;"> 93 </td>
   <td style="text-align:right;"> 276.0 </td>
   <td style="text-align:right;"> 343 </td>
  </tr>
</tbody>
</table>

### Throughput

#### Epics

<div class="figure" style="text-align: center">
<img src="02-essence_files/figure-html/essence-completed-epics-week-fig-1.png" alt="Closed Epics by Week" width="80%" />
<p class="caption">(\#fig:essence-completed-epics-week-fig)Closed Epics by Week</p>
</div>

The plot below shows the number of epics closed in every week, marked separately in different color based on priority

<img src="02-essence_files/figure-html/essence-epics-wk-agg-fig-1.png" width="80%" style="display: block; margin: auto;" />


<!-- - Density distribution -->

<!-- Gives and indication of the densities especially the occurrence of multiple maxima in the data. This can be due to multiple categories of work items which may be investigated further.  -->

<!-- ```{r essence-density-distibution-closed-epics-fig, include=TRUE, echo=FALSE, out.width="80%", fig.align="center", fig.asp=.75, fig.cap="Priority based Density Distribution", message=FALSE, warning=FALSE} -->
<!-- epics.closed %>% violin_plot.CycleTimeVsPriority() -->
<!-- ``` -->


#### Stories


Tells us the number of work items (stories) completed aggregated for each 
week which is an indication of how stable the throughput is.

<img src="02-essence_files/figure-html/essence-completed-items-week-fig-1.png" width="80%" style="display: block; margin: auto;" />

The plot below shows the number of stories closed in every week, marked separately in different color based on priority


<div class="figure" style="text-align: center">
<img src="02-essence_files/figure-html/essence-stories-wk-agg-fig-1.png" alt="Number of Stories Closed in a Week colored by Priority" width="80%" />
<p class="caption">(\#fig:essence-stories-wk-agg-fig)Number of Stories Closed in a Week colored by Priority</p>
</div>

- Density distribution

Gives and indication of the densities especially the occurrence of multiple maxima in the data. This can be due to multiple categories of work items which may be investigated further. 

<div class="figure" style="text-align: center">
<img src="02-essence_files/figure-html/essence-density-distibution-closed-stories-fig-1.png" alt="Priority based Density Distribution" width="80%" />
<p class="caption">(\#fig:essence-density-distibution-closed-stories-fig)Priority based Density Distribution</p>
</div>


### Flow

#### Work in Progress (WiP)

##### Epics 



<div class="figure" style="text-align: center">
<img src="02-essence_files/figure-html/essence-epics-work-in-progress-fig -1.png" alt="WiP in Days" width="80%" />
<p class="caption">(\#fig:essence-epics-work-in-progress-fig )WiP in Days</p>
</div>

##### Stories



<div class="figure" style="text-align: center">
<img src="02-essence_files/figure-html/essence-stories-work-in-progress-fig -1.png" alt="WiP in Days" width="80%" />
<p class="caption">(\#fig:essence-stories-work-in-progress-fig )WiP in Days</p>
</div>

#### Inflow/OutFlow

##### Epics

<img src="02-essence_files/figure-html/essence-epics-inflow-outflow-1.png" width="80%" style="display: block; margin: auto;" />

<img src="02-essence_files/figure-html/essence-epics-inflow-outflow-cumsumm-1.png" width="80%" style="display: block; margin: auto;" />


```{=html}
<style type="text/css">
.plot-fill { width: 80%; height: 100%; }
.center {
                          display: block; 
                          margin-left: auto; 
                          margin-right: auto;
                        }
#left_plt { float: left; background-color: #ccffcc;  }
#right_plt { float: right; background-color: #ccffcc; }
#center_plt { float: center; background-color: #ccffcc; }
</style>
<div id="center_plt" class="plot-fill center">
<div id="htmlwidget-ff4fe8d271fdf7f10256" style="width:100%;height:400px;" class="plotly html-widget"></div>
<script type="application/json" data-for="htmlwidget-ff4fe8d271fdf7f10256">{"x":{"visdat":{"496efc755e":["function () ","plotlyVisDat"]},"cur_data":"496efc755e","attrs":{"496efc755e":{"x":{},"y":{},"mode":"lines+markers","color":{},"colors":["#D55E00","#E69F00","#56B4E9","#F0E442","#999999"],"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"scatter"}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"legend":{"orientation":"h","xanchor":"center","x":0.5,"y":-0.2},"xaxis":{"domain":[0,1],"automargin":true,"title":"FloorDate"},"yaxis":{"domain":[0,1],"automargin":true,"title":"CumSum"},"hovermode":"closest","showlegend":true},"source":"A","config":{"modeBarButtonsToAdd":["hoverclosest","hovercompare"],"showSendToCloud":false,"displaylogo":false,"modeBarButtonsToRemove":["zoomIn2d","zoomOut2d"]},"data":[{"x":["2020-12-27","2021-01-10","2021-01-17","2021-01-24","2021-01-31","2021-02-07","2021-02-14","2021-02-21","2021-02-28","2021-03-28","2021-04-11","2021-04-25","2021-05-09","2021-05-16","2021-05-23","2021-05-30","2021-06-06","2021-06-13","2021-06-20","2021-07-04","2021-07-11","2021-07-18","2021-07-25","2021-08-01","2021-08-15","2021-08-29","2021-09-05","2021-09-12","2021-09-19","2021-09-26","2021-10-03","2021-10-10","2021-10-17","2021-10-24","2021-11-21","2021-12-05","2021-12-19","2021-12-26","2022-01-02","2022-01-16","2022-01-23","2022-01-30","2022-02-20","2022-02-27","2022-03-06","2022-03-13","2022-03-20","2022-03-27","2022-04-03","2022-04-17","2022-05-01","2022-05-15","2022-05-22"],"y":[1,6,8,9,10,14,16,18,19,20,27,30,34,35,38,39,41,41,42,44,46,47,50,51,52,53,55,56,59,61,64,65,68,69,70,72,76,77,78,80,82,86,87,88,89,90,91,90,92,93,95,98,99],"mode":"lines+markers","type":"scatter","name":"Medium","marker":{"color":"rgba(86,180,233,1)","line":{"color":"rgba(86,180,233,1)"}},"textfont":{"color":"rgba(86,180,233,1)"},"error_y":{"color":"rgba(86,180,233,1)"},"error_x":{"color":"rgba(86,180,233,1)"},"line":{"color":"rgba(86,180,233,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":["2020-12-13","2020-12-20","2021-01-10","2021-01-24","2021-02-21","2021-02-28","2021-03-07","2021-03-21","2021-05-02","2021-05-09","2021-06-27","2021-09-05","2021-09-12","2021-09-19","2022-01-02","2022-01-16","2022-01-23","2022-03-06","2022-03-27","2022-04-10","2022-05-08"],"y":[4,5,6,7,8,11,14,15,18,16,17,18,21,22,23,25,27,28,27,28,29],"mode":"lines+markers","type":"scatter","name":"High","marker":{"color":"rgba(230,159,0,1)","line":{"color":"rgba(230,159,0,1)"}},"textfont":{"color":"rgba(230,159,0,1)"},"error_y":{"color":"rgba(230,159,0,1)"},"error_x":{"color":"rgba(230,159,0,1)"},"line":{"color":"rgba(230,159,0,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":["2021-03-07","2021-04-25"],"y":[1,2],"mode":"lines+markers","type":"scatter","name":"Critical","marker":{"color":"rgba(213,94,0,1)","line":{"color":"rgba(213,94,0,1)"}},"textfont":{"color":"rgba(213,94,0,1)"},"error_y":{"color":"rgba(213,94,0,1)"},"error_x":{"color":"rgba(213,94,0,1)"},"line":{"color":"rgba(213,94,0,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot","plotly_sunburstclick"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>
</div>
```


```{=html}
<div id="htmlwidget-260cfd0121d0f2d122ac" style="width:100%;height:auto;" class="datatables html-widget"></div>
<script type="application/json" data-for="htmlwidget-260cfd0121d0f2d122ac">{"x":{"filter":"top","vertical":false,"filterHTML":"<tr>\n  <td><\/td>\n  <td data-type=\"date\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"1607817600000\" data-max=\"1653177600000\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"factor\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"width: 100%; display: none;\">\n      <select multiple=\"multiple\" style=\"width: 100%;\" data-options=\"[&quot;Critical&quot;,&quot;High&quot;,&quot;Medium&quot;,&quot;Low&quot;,&quot;None&quot;]\"><\/select>\n    <\/div>\n  <\/td>\n  <td data-type=\"number\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"0\" data-max=\"7\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"number\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"0\" data-max=\"3\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"number\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"1\" data-max=\"99\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n<\/tr>","data":[["1","2","3","4","5","6","7","8","9","10","11","12","13","14","15","16","17","18","19","20","21","22","23","24","25","26","27","28","29","30","31","32","33","34","35","36","37","38","39","40","41","42","43","44","45","46","47","48","49","50","51","52","53","54","55","56","57","58","59","60","61","62","63","64","65","66","67","68","69","70","71","72","73","74","75","76"],["2020-12-13","2020-12-20","2020-12-27","2021-01-10","2021-01-10","2021-01-17","2021-01-24","2021-01-24","2021-01-31","2021-02-07","2021-02-14","2021-02-21","2021-02-21","2021-02-28","2021-02-28","2021-03-07","2021-03-07","2021-03-21","2021-03-28","2021-04-11","2021-04-25","2021-04-25","2021-05-02","2021-05-09","2021-05-09","2021-05-16","2021-05-23","2021-05-30","2021-06-06","2021-06-13","2021-06-20","2021-06-27","2021-07-04","2021-07-11","2021-07-18","2021-07-25","2021-08-01","2021-08-15","2021-08-29","2021-09-05","2021-09-05","2021-09-12","2021-09-12","2021-09-19","2021-09-19","2021-09-26","2021-10-03","2021-10-10","2021-10-17","2021-10-24","2021-11-21","2021-12-05","2021-12-19","2021-12-26","2022-01-02","2022-01-02","2022-01-16","2022-01-16","2022-01-23","2022-01-23","2022-01-30","2022-02-20","2022-02-27","2022-03-06","2022-03-06","2022-03-13","2022-03-20","2022-03-27","2022-03-27","2022-04-03","2022-04-10","2022-04-17","2022-05-01","2022-05-08","2022-05-15","2022-05-22"],["High","High","Medium","High","Medium","Medium","High","Medium","Medium","Medium","Medium","High","Medium","High","Medium","Critical","High","High","Medium","Medium","Critical","Medium","High","High","Medium","Medium","Medium","Medium","Medium","Medium","Medium","High","Medium","Medium","Medium","Medium","Medium","Medium","Medium","High","Medium","High","Medium","High","Medium","Medium","Medium","Medium","Medium","Medium","Medium","Medium","Medium","Medium","High","Medium","High","Medium","High","Medium","Medium","Medium","Medium","High","Medium","Medium","Medium","High","Medium","Medium","High","Medium","Medium","High","Medium","Medium"],[4,1,1,1,5,2,1,1,1,4,2,1,2,3,1,1,3,1,1,7,1,3,3,1,4,1,3,1,2,1,1,1,2,2,2,3,1,1,1,1,3,3,1,1,3,2,3,1,3,1,1,2,4,1,1,1,2,2,2,2,4,1,1,1,1,1,1,0,1,2,1,1,2,1,3,1],[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,3,0,0,0,0,0,1,0,0,0,0,1,0,0,0,0,0,1,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,2,0,0,0,0,0,0,0],[4,5,1,6,6,8,7,9,10,14,16,8,18,11,19,1,14,15,20,27,2,30,18,16,34,35,38,39,41,41,42,17,44,46,47,50,51,52,53,18,55,21,56,22,59,61,64,65,68,69,70,72,76,77,23,78,25,80,27,82,86,87,88,28,89,90,91,27,90,92,28,93,95,29,98,99]],"container":"<table class=\"display\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>FloorDate<\/th>\n      <th>Priority<\/th>\n      <th>Opened<\/th>\n      <th>Closed<\/th>\n      <th>CumSum<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"columnDefs":[{"className":"dt-right","targets":[3,4,5]},{"orderable":false,"targets":0}],"order":[],"autoWidth":false,"orderClasses":false,"orderCellsTop":true}},"evals":[],"jsHooks":[]}</script>
```
##### Stories

<img src="02-essence_files/figure-html/essence-stories-inflow-outflow-1.png" width="80%" style="display: block; margin: auto;" />

<img src="02-essence_files/figure-html/essence-stories-inflow-outflow-cumsumm-1.png" width="80%" style="display: block; margin: auto;" />

## Defect Metrics






### Overview 

#### Distribution of priorities across projects




<div class="figure" style="text-align: center">
<img src="02-essence_files/figure-html/essence-defects-summary-treemap-fig-1.png" alt="Summary Tree Map" width="80%" />
<p class="caption">(\#fig:essence-defects-summary-treemap-fig)Summary Tree Map</p>
</div>

###  Cycle Time

Below is the [5 Number Summary](https://en.wikipedia.org/wiki/Five-number_summary) 
of the entire data set. The 75% Qartile value is significant because that is the 
number which you can typically see as the turn around time (TAT) to service a defect.

#### Summary

<table class="table table-striped" style="width: auto !important; margin-left: auto; margin-right: auto;">
<caption>(\#tab:essence-defects-tab-cycle-time-basic-stats)5 Number Summary</caption>
 <thead>
  <tr>
   <th style="text-align:right;"> Min </th>
   <th style="text-align:right;"> LoQ </th>
   <th style="text-align:right;"> Med </th>
   <th style="text-align:right;"> UpQ </th>
   <th style="text-align:right;"> Max </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 6 </td>
   <td style="text-align:right;"> 20 </td>
   <td style="text-align:right;"> 55 </td>
   <td style="text-align:right;"> 506 </td>
  </tr>
</tbody>
</table>


#### Cycle Time Trend

This reflects the capacity/capability of the team to resolve across all 
priorities as indicated by a trend.

<div class="figure" style="text-align: center">
<img src="02-essence_files/figure-html/essence-defects-cycle-time-trend-all-1.png" alt="All Severities" width="80%" />
<p class="caption">(\#fig:essence-defects-cycle-time-trend-all)All Severities</p>
</div>


#### 5 Number Summary

<table class="table table-striped" style="width: auto !important; margin-left: auto; margin-right: auto;">
<caption>(\#tab:essence-defects-cycle-time-summary)All Severities</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Type </th>
   <th style="text-align:left;"> Priority </th>
   <th style="text-align:right;"> Count </th>
   <th style="text-align:right;"> Min </th>
   <th style="text-align:right;"> LoQ </th>
   <th style="text-align:right;"> Med </th>
   <th style="text-align:right;"> UpQ </th>
   <th style="text-align:right;"> Max </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Epic </td>
   <td style="text-align:left;"> High </td>
   <td style="text-align:right;"> 4 </td>
   <td style="text-align:right;"> 68 </td>
   <td style="text-align:right;"> 95.0 </td>
   <td style="text-align:right;"> 112.5 </td>
   <td style="text-align:right;"> 207.0 </td>
   <td style="text-align:right;"> 465 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Epic </td>
   <td style="text-align:left;"> Medium </td>
   <td style="text-align:right;"> 5 </td>
   <td style="text-align:right;"> 2 </td>
   <td style="text-align:right;"> 36.0 </td>
   <td style="text-align:right;"> 118.0 </td>
   <td style="text-align:right;"> 184.0 </td>
   <td style="text-align:right;"> 340 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Story </td>
   <td style="text-align:left;"> Critical </td>
   <td style="text-align:right;"> 53 </td>
   <td style="text-align:right;"> 9 </td>
   <td style="text-align:right;"> 55.0 </td>
   <td style="text-align:right;"> 92.0 </td>
   <td style="text-align:right;"> 149.0 </td>
   <td style="text-align:right;"> 295 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Story </td>
   <td style="text-align:left;"> High </td>
   <td style="text-align:right;"> 491 </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 39.5 </td>
   <td style="text-align:right;"> 78.0 </td>
   <td style="text-align:right;"> 115.5 </td>
   <td style="text-align:right;"> 469 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Story </td>
   <td style="text-align:left;"> Medium </td>
   <td style="text-align:right;"> 1413 </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 27.0 </td>
   <td style="text-align:right;"> 79.0 </td>
   <td style="text-align:right;"> 126.0 </td>
   <td style="text-align:right;"> 385 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Story </td>
   <td style="text-align:left;"> Low </td>
   <td style="text-align:right;"> 13 </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 16.0 </td>
   <td style="text-align:right;"> 93.0 </td>
   <td style="text-align:right;"> 276.0 </td>
   <td style="text-align:right;"> 343 </td>
  </tr>
</tbody>
</table>

<div class="figure" style="text-align: center">
<img src="02-essence_files/figure-html/essence-defects-cycle-time-trend-for-hnc-1.png" alt="High and Critical" width="80%" />
<p class="caption">(\#fig:essence-defects-cycle-time-trend-for-hnc)High and Critical</p>
</div>


<table class="table table-striped" style="width: auto !important; margin-left: auto; margin-right: auto;">
<caption>(\#tab:essence-defects-cycle-time-stat-for-high-and-critical)5 Number Summary for High and Critical Defects</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Priority </th>
   <th style="text-align:right;"> Min </th>
   <th style="text-align:right;"> LoQ </th>
   <th style="text-align:right;"> Med </th>
   <th style="text-align:right;"> UpQ </th>
   <th style="text-align:right;"> Max </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Critical </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 3 </td>
   <td style="text-align:right;"> 11 </td>
   <td style="text-align:right;"> 41 </td>
   <td style="text-align:right;"> 506 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> High </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 6 </td>
   <td style="text-align:right;"> 18 </td>
   <td style="text-align:right;"> 52 </td>
   <td style="text-align:right;"> 486 </td>
  </tr>
</tbody>
</table>


### Throughput


<div class="figure" style="text-align: center">
<img src="02-essence_files/figure-html/essence-defects-closed-metric-for-each-week-1.png" alt="Closure metrics - All Defects" width="80%" />
<p class="caption">(\#fig:essence-defects-closed-metric-for-each-week)Closure metrics - All Defects</p>
</div>


<div class="figure" style="text-align: center">
<img src="02-essence_files/figure-html/essence-defects-fig-completed-hnc-defects-week-1.png" alt="Closed defects by Week" width="80%" />
<p class="caption">(\#fig:essence-defects-fig-completed-hnc-defects-week)Closed defects by Week</p>
</div>




The plot below shows the number of defects closed in every week, marked separately in different color based on priority


<img src="02-essence_files/figure-html/essence-defects-all-wk-agg-fig-1.png" width="80%" style="display: block; margin: auto;" />

<img src="02-essence_files/figure-html/essence-defects-fig-hnc-wk-agg-1.png" width="80%" style="display: block; margin: auto;" />


```{=html}
<div id="htmlwidget-39b6931b66f24e29cd40" style="width:100%;height:auto;" class="datatables html-widget"></div>
<script type="application/json" data-for="htmlwidget-39b6931b66f24e29cd40">{"x":{"filter":"top","vertical":false,"filterHTML":"<tr>\n  <td><\/td>\n  <td data-type=\"date\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"1.606608e+12\" data-max=\"1653177600000\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"factor\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"width: 100%; display: none;\">\n      <select multiple=\"multiple\" style=\"width: 100%;\" data-options=\"[&quot;Critical&quot;,&quot;High&quot;,&quot;Medium&quot;,&quot;Low&quot;,&quot;None&quot;]\"><\/select>\n    <\/div>\n  <\/td>\n  <td data-type=\"integer\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"1\" data-max=\"219\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n<\/tr>","data":[["1","2","3","4","5","6","7","8","9","10","11","12","13","14","15","16","17","18","19","20","21","22","23","24","25","26","27","28","29","30","31","32","33","34","35","36","37","38","39","40","41","42","43","44","45","46","47","48","49","50","51","52","53","54","55","56","57","58","59","60","61","62","63","64","65","66","67","68","69","70","71","72","73","74","75","76","77","78","79","80","81","82","83","84","85","86","87","88","89","90","91","92","93","94","95","96","97","98","99","100","101","102","103","104","105","106","107","108","109","110","111","112","113","114","115","116","117","118","119","120","121","122","123","124","125","126","127","128","129","130","131","132","133","134","135","136","137","138","139","140","141","142","143","144","145","146","147","148","149","150","151","152","153","154","155","156","157","158","159","160","161","162","163","164","165","166","167","168","169","170","171","172","173","174","175","176","177","178","179","180","181","182","183","184","185","186","187","188","189","190","191","192","193","194","195","196","197","198","199","200","201","202","203","204","205","206","207","208","209","210","211","212","213","214","215","216","217","218","219","220","221","222","223","224","225","226","227","228","229","230","231","232","233","234","235","236","237","238","239","240","241","242","243","244","245","246","247","248","249","250","251","252","253","254","255","256","257","258","259","260","261","262","263","264","265","266","267","268","269","270","271","272"],["2020-11-29","2020-12-06","2020-12-06","2020-12-06","2020-12-13","2020-12-13","2020-12-13","2020-12-20","2020-12-20","2020-12-20","2020-12-27","2020-12-27","2020-12-27","2021-01-03","2021-01-03","2021-01-03","2021-01-03","2021-01-10","2021-01-10","2021-01-10","2021-01-10","2021-01-17","2021-01-17","2021-01-17","2021-01-17","2021-01-24","2021-01-24","2021-01-24","2021-01-31","2021-01-31","2021-01-31","2021-02-07","2021-02-07","2021-02-07","2021-02-07","2021-02-14","2021-02-14","2021-02-14","2021-02-14","2021-02-21","2021-02-21","2021-02-21","2021-02-21","2021-02-28","2021-02-28","2021-02-28","2021-03-07","2021-03-07","2021-03-07","2021-03-14","2021-03-14","2021-03-14","2021-03-14","2021-03-21","2021-03-21","2021-03-21","2021-03-28","2021-03-28","2021-03-28","2021-03-28","2021-04-04","2021-04-04","2021-04-04","2021-04-04","2021-04-11","2021-04-11","2021-04-11","2021-04-18","2021-04-18","2021-04-18","2021-04-25","2021-04-25","2021-04-25","2021-04-25","2021-05-02","2021-05-02","2021-05-02","2021-05-02","2021-05-09","2021-05-09","2021-05-09","2021-05-09","2021-05-16","2021-05-16","2021-05-16","2021-05-16","2021-05-23","2021-05-23","2021-05-23","2021-05-30","2021-05-30","2021-05-30","2021-05-30","2021-06-06","2021-06-06","2021-06-06","2021-06-13","2021-06-13","2021-06-13","2021-06-13","2021-06-20","2021-06-20","2021-06-20","2021-06-20","2021-06-27","2021-06-27","2021-06-27","2021-07-04","2021-07-04","2021-07-04","2021-07-04","2021-07-11","2021-07-11","2021-07-11","2021-07-11","2021-07-18","2021-07-18","2021-07-18","2021-07-18","2021-07-25","2021-07-25","2021-07-25","2021-07-25","2021-08-01","2021-08-01","2021-08-01","2021-08-01","2021-08-08","2021-08-08","2021-08-08","2021-08-08","2021-08-15","2021-08-15","2021-08-15","2021-08-15","2021-08-22","2021-08-22","2021-08-22","2021-08-22","2021-08-29","2021-08-29","2021-08-29","2021-09-05","2021-09-05","2021-09-05","2021-09-05","2021-09-12","2021-09-12","2021-09-12","2021-09-12","2021-09-19","2021-09-19","2021-09-19","2021-09-26","2021-09-26","2021-09-26","2021-10-03","2021-10-03","2021-10-03","2021-10-10","2021-10-10","2021-10-10","2021-10-17","2021-10-17","2021-10-17","2021-10-24","2021-10-24","2021-10-24","2021-10-31","2021-10-31","2021-10-31","2021-11-07","2021-11-07","2021-11-07","2021-11-14","2021-11-14","2021-11-14","2021-11-21","2021-11-21","2021-11-21","2021-11-21","2021-11-28","2021-11-28","2021-11-28","2021-12-05","2021-12-05","2021-12-05","2021-12-12","2021-12-12","2021-12-12","2021-12-19","2021-12-19","2021-12-19","2021-12-26","2021-12-26","2021-12-26","2022-01-02","2022-01-02","2022-01-02","2022-01-02","2022-01-09","2022-01-09","2022-01-09","2022-01-16","2022-01-16","2022-01-16","2022-01-16","2022-01-23","2022-01-23","2022-01-23","2022-01-30","2022-01-30","2022-01-30","2022-02-06","2022-02-06","2022-02-06","2022-02-13","2022-02-13","2022-02-13","2022-02-13","2022-02-20","2022-02-20","2022-02-20","2022-02-20","2022-02-27","2022-02-27","2022-02-27","2022-02-27","2022-03-06","2022-03-06","2022-03-06","2022-03-13","2022-03-13","2022-03-13","2022-03-13","2022-03-20","2022-03-20","2022-03-20","2022-03-20","2022-03-27","2022-03-27","2022-03-27","2022-04-03","2022-04-03","2022-04-03","2022-04-10","2022-04-10","2022-04-10","2022-04-10","2022-04-17","2022-04-17","2022-04-17","2022-04-17","2022-04-24","2022-04-24","2022-04-24","2022-04-24","2022-05-01","2022-05-01","2022-05-01","2022-05-01","2022-05-08","2022-05-08","2022-05-08","2022-05-08","2022-05-15","2022-05-15","2022-05-15","2022-05-15","2022-05-22","2022-05-22","2022-05-22"],["High","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium"],[2,6,21,5,3,20,7,10,15,9,4,11,3,8,26,12,1,11,33,19,4,17,50,33,1,15,43,15,9,31,9,4,25,12,1,10,36,14,4,9,38,11,1,7,34,20,2,66,13,7,46,26,1,9,37,15,5,16,10,2,9,29,19,2,5,44,21,16,43,23,45,69,42,1,34,166,69,13,23,219,142,8,19,136,81,6,15,89,52,20,73,40,2,6,40,17,9,32,17,1,6,24,8,1,7,54,36,8,40,42,1,6,44,23,2,6,50,20,3,3,23,21,1,4,44,20,3,5,28,10,3,15,41,50,3,11,37,30,2,7,61,26,7,36,18,1,22,71,70,9,26,41,26,4,30,20,6,20,8,5,16,2,9,16,6,4,26,11,2,14,5,11,32,10,14,51,18,10,25,7,1,11,21,26,16,38,10,3,12,9,2,15,16,1,4,2,12,27,21,1,6,33,22,8,67,26,1,7,17,15,2,12,6,3,14,10,6,19,13,1,9,39,29,1,7,23,21,1,3,27,12,6,15,8,2,4,29,10,1,6,14,14,12,49,20,4,10,5,2,6,16,13,2,6,23,14,1,7,30,28,1,9,40,34,1,12,66,33,2,2,11,3]],"container":"<table class=\"display\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>FloorDate<\/th>\n      <th>Priority<\/th>\n      <th>NumClosed<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"columnDefs":[{"className":"dt-right","targets":3},{"orderable":false,"targets":0}],"order":[],"autoWidth":false,"orderClasses":false,"orderCellsTop":true}},"evals":[],"jsHooks":[]}</script>
```

- Density distribution

Gives and indication of the densities especially the occurrence of multiple maxima in the data. This can be due to multiple categories of work items which may be investigated further. Below are the violin plots for all defects and also high and critical defects.

<div class="figure" style="text-align: center">
<img src="02-essence_files/figure-html/essence-defects-fig-densdist-closed-overall-1.png" alt="Priority based Density Distribution" width="80%" />
<p class="caption">(\#fig:essence-defects-fig-densdist-closed-overall)Priority based Density Distribution</p>
</div>



### Flow

#### Work in Progress (WiP)

<img src="02-essence_files/figure-html/essence-defects-fig-areaplot-wip-1.png" width="80%" style="display: block; margin: auto;" />

#### Inflow Outflow

<img src="02-essence_files/figure-html/essence-defects-inflow-outflow-1.png" width="80%" style="display: block; margin: auto;" />

<img src="02-essence_files/figure-html/essence-defects-inflow-outflow-cumsumm-1.png" width="80%" style="display: block; margin: auto;" />


```{=html}
<div id="htmlwidget-4edb12292a29c5748942" style="width:100%;height:auto;" class="datatables html-widget"></div>
<script type="application/json" data-for="htmlwidget-4edb12292a29c5748942">{"x":{"filter":"top","vertical":false,"filterHTML":"<tr>\n  <td><\/td>\n  <td data-type=\"date\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"1.606608e+12\" data-max=\"1653177600000\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"factor\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"width: 100%; display: none;\">\n      <select multiple=\"multiple\" style=\"width: 100%;\" data-options=\"[&quot;Critical&quot;,&quot;High&quot;,&quot;Medium&quot;,&quot;Low&quot;,&quot;None&quot;]\"><\/select>\n    <\/div>\n  <\/td>\n  <td data-type=\"number\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"0\" data-max=\"474\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"number\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"0\" data-max=\"219\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"number\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"1\" data-max=\"2185\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n<\/tr>","data":[["1","2","3","4","5","6","7","8","9","10","11","12","13","14","15","16","17","18","19","20","21","22","23","24","25","26","27","28","29","30","31","32","33","34","35","36","37","38","39","40","41","42","43","44","45","46","47","48","49","50","51","52","53","54","55","56","57","58","59","60","61","62","63","64","65","66","67","68","69","70","71","72","73","74","75","76","77","78","79","80","81","82","83","84","85","86","87","88","89","90","91","92","93","94","95","96","97","98","99","100","101","102","103","104","105","106","107","108","109","110","111","112","113","114","115","116","117","118","119","120","121","122","123","124","125","126","127","128","129","130","131","132","133","134","135","136","137","138","139","140","141","142","143","144","145","146","147","148","149","150","151","152","153","154","155","156","157","158","159","160","161","162","163","164","165","166","167","168","169","170","171","172","173","174","175","176","177","178","179","180","181","182","183","184","185","186","187","188","189","190","191","192","193","194","195","196","197","198","199","200","201","202","203","204","205","206","207","208","209","210","211","212","213","214","215","216","217","218","219","220","221","222","223","224","225","226","227","228","229","230","231","232","233","234","235","236","237","238","239","240","241","242","243","244","245","246","247","248","249","250","251","252","253","254","255","256","257","258","259","260","261","262","263","264","265","266","267","268","269","270","271","272","273","274","275","276","277","278","279","280","281","282","283","284","285","286","287","288","289","290","291","292","293","294","295","296","297","298","299","300","301","302","303","304","305","306"],["2020-11-29","2020-11-29","2020-11-29","2020-11-29","2020-12-06","2020-12-06","2020-12-06","2020-12-06","2020-12-13","2020-12-13","2020-12-13","2020-12-13","2020-12-20","2020-12-20","2020-12-20","2020-12-20","2020-12-27","2020-12-27","2020-12-27","2020-12-27","2021-01-03","2021-01-03","2021-01-03","2021-01-03","2021-01-10","2021-01-10","2021-01-10","2021-01-10","2021-01-17","2021-01-17","2021-01-17","2021-01-17","2021-01-24","2021-01-24","2021-01-24","2021-01-24","2021-01-31","2021-01-31","2021-01-31","2021-01-31","2021-02-07","2021-02-07","2021-02-07","2021-02-07","2021-02-14","2021-02-14","2021-02-14","2021-02-14","2021-02-21","2021-02-21","2021-02-21","2021-02-21","2021-02-28","2021-02-28","2021-02-28","2021-02-28","2021-03-07","2021-03-07","2021-03-07","2021-03-07","2021-03-14","2021-03-14","2021-03-14","2021-03-14","2021-03-21","2021-03-21","2021-03-21","2021-03-21","2021-03-28","2021-03-28","2021-03-28","2021-03-28","2021-04-04","2021-04-04","2021-04-04","2021-04-04","2021-04-11","2021-04-11","2021-04-11","2021-04-18","2021-04-18","2021-04-18","2021-04-18","2021-04-25","2021-04-25","2021-04-25","2021-04-25","2021-05-02","2021-05-02","2021-05-02","2021-05-02","2021-05-09","2021-05-09","2021-05-09","2021-05-09","2021-05-16","2021-05-16","2021-05-16","2021-05-16","2021-05-23","2021-05-23","2021-05-23","2021-05-23","2021-05-30","2021-05-30","2021-05-30","2021-05-30","2021-06-06","2021-06-06","2021-06-06","2021-06-06","2021-06-13","2021-06-13","2021-06-13","2021-06-13","2021-06-20","2021-06-20","2021-06-20","2021-06-20","2021-06-27","2021-06-27","2021-06-27","2021-06-27","2021-07-04","2021-07-04","2021-07-04","2021-07-04","2021-07-11","2021-07-11","2021-07-11","2021-07-11","2021-07-18","2021-07-18","2021-07-18","2021-07-18","2021-07-25","2021-07-25","2021-07-25","2021-07-25","2021-08-01","2021-08-01","2021-08-01","2021-08-01","2021-08-08","2021-08-08","2021-08-08","2021-08-08","2021-08-15","2021-08-15","2021-08-15","2021-08-15","2021-08-22","2021-08-22","2021-08-22","2021-08-22","2021-08-29","2021-08-29","2021-08-29","2021-08-29","2021-09-05","2021-09-05","2021-09-05","2021-09-05","2021-09-12","2021-09-12","2021-09-12","2021-09-12","2021-09-19","2021-09-19","2021-09-19","2021-09-19","2021-09-26","2021-09-26","2021-09-26","2021-09-26","2021-10-03","2021-10-03","2021-10-03","2021-10-03","2021-10-10","2021-10-10","2021-10-10","2021-10-10","2021-10-17","2021-10-17","2021-10-17","2021-10-17","2021-10-24","2021-10-24","2021-10-24","2021-10-24","2021-10-31","2021-10-31","2021-10-31","2021-10-31","2021-11-07","2021-11-07","2021-11-07","2021-11-14","2021-11-14","2021-11-14","2021-11-14","2021-11-21","2021-11-21","2021-11-21","2021-11-21","2021-11-28","2021-11-28","2021-11-28","2021-11-28","2021-12-05","2021-12-05","2021-12-05","2021-12-12","2021-12-12","2021-12-12","2021-12-12","2021-12-19","2021-12-19","2021-12-19","2021-12-26","2021-12-26","2021-12-26","2022-01-02","2022-01-02","2022-01-02","2022-01-02","2022-01-09","2022-01-09","2022-01-09","2022-01-09","2022-01-16","2022-01-16","2022-01-16","2022-01-16","2022-01-23","2022-01-23","2022-01-23","2022-01-23","2022-01-30","2022-01-30","2022-01-30","2022-01-30","2022-02-06","2022-02-06","2022-02-06","2022-02-06","2022-02-13","2022-02-13","2022-02-13","2022-02-13","2022-02-20","2022-02-20","2022-02-20","2022-02-20","2022-02-27","2022-02-27","2022-02-27","2022-02-27","2022-03-06","2022-03-06","2022-03-06","2022-03-06","2022-03-13","2022-03-13","2022-03-13","2022-03-13","2022-03-20","2022-03-20","2022-03-20","2022-03-20","2022-03-27","2022-03-27","2022-03-27","2022-03-27","2022-04-03","2022-04-03","2022-04-03","2022-04-03","2022-04-10","2022-04-10","2022-04-10","2022-04-10","2022-04-17","2022-04-17","2022-04-17","2022-04-17","2022-04-24","2022-04-24","2022-04-24","2022-04-24","2022-05-01","2022-05-01","2022-05-01","2022-05-01","2022-05-08","2022-05-08","2022-05-08","2022-05-08","2022-05-15","2022-05-15","2022-05-15","2022-05-15","2022-05-22","2022-05-22","2022-05-22"],["Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium"],[9,67,40,1,12,84,43,2,18,70,42,2,18,50,27,2,4,20,20,2,19,82,42,3,19,56,39,2,39,132,49,3,13,80,66,2,10,84,42,3,15,94,43,2,13,95,27,2,12,81,31,4,15,79,48,2,4,66,54,4,117,474,305,21,13,79,52,20,13,45,29,3,16,92,39,3,5,56,39,14,86,49,1,12,101,47,4,14,83,37,2,19,74,34,2,18,82,48,5,29,97,93,5,13,58,43,3,10,84,60,6,16,139,46,5,19,60,41,0,6,59,49,1,17,63,36,2,8,74,28,1,7,61,35,2,6,58,37,0,7,50,31,11,7,41,37,2,12,48,45,2,18,63,33,2,11,72,30,1,9,73,32,4,34,73,41,1,7,51,34,3,7,44,19,1,7,42,16,1,18,47,21,1,13,41,14,1,14,74,31,2,12,29,13,1,22,58,31,23,63,33,3,12,53,17,0,11,57,43,3,5,48,35,7,34,26,2,7,27,21,3,13,12,4,52,23,3,11,74,35,1,10,72,36,2,5,44,20,1,16,45,24,3,3,32,30,1,10,53,32,0,9,54,18,3,6,46,31,1,7,37,34,3,19,39,22,4,10,57,30,4,7,45,36,1,13,44,30,1,7,30,26,2,16,59,26,9,8,57,49,2,4,39,25,0,14,55,39,2,19,66,32,3,0,8,5],[0,4,3,0,6,21,5,0,3,21,8,0,10,15,9,0,4,11,3,0,9,27,12,1,11,34,20,4,17,51,34,1,15,43,15,0,9,31,9,0,4,25,12,1,10,36,14,4,9,38,11,1,7,34,20,0,2,66,13,0,7,47,26,1,9,37,15,0,5,16,10,2,9,29,19,2,5,44,21,16,43,23,0,45,69,42,1,34,166,69,13,23,219,142,8,19,136,81,6,15,89,52,0,20,73,40,2,6,40,17,0,9,32,17,1,6,24,8,1,7,54,36,0,8,40,42,1,6,44,23,2,6,50,20,3,3,23,21,1,4,44,20,3,5,28,10,3,15,41,50,3,11,37,30,2,7,61,26,0,7,36,18,1,23,71,70,9,27,41,26,0,4,30,20,0,6,20,8,0,5,16,3,0,9,16,6,0,4,26,11,0,2,14,5,0,11,32,10,14,51,18,0,10,25,7,1,11,21,26,0,16,38,10,3,12,9,0,2,15,16,1,4,2,12,27,21,1,6,33,22,0,8,67,26,1,7,17,15,0,2,12,6,0,3,14,10,0,6,19,13,1,9,39,29,1,7,23,21,1,3,27,12,0,6,15,8,2,4,29,10,1,6,14,14,0,12,49,20,0,4,10,5,2,6,16,13,2,6,23,14,1,7,30,28,1,9,40,34,1,12,66,33,2,2,11,3],[9,63,37,1,15,126,75,3,30,175,109,5,38,210,127,7,38,219,144,9,48,274,174,11,56,296,193,9,78,377,208,11,76,414,259,13,77,467,292,16,88,536,323,17,91,595,336,15,94,638,356,18,102,683,384,20,104,683,425,24,214,1110,704,44,218,1152,741,64,226,1181,760,65,233,1244,780,66,233,1256,798,231,1299,824,67,198,1331,829,70,178,1248,797,59,174,1103,689,53,173,1049,656,52,187,1057,697,57,180,1042,700,58,184,1086,743,64,191,1193,772,68,204,1229,805,67,203,1234,818,68,212,1257,812,69,214,1287,817,68,215,1298,832,67,218,1333,848,66,221,1339,859,74,223,1352,886,73,220,1359,881,72,227,1385,884,72,231,1396,888,73,233,1433,902,76,244,1435,873,68,224,1445,881,71,227,1459,880,72,228,1481,888,73,241,1512,906,74,245,1537,914,75,255,1585,934,77,265,1600,942,78,276,1626,963,285,1638,978,81,287,1666,988,80,287,1702,1005,83,276,1712,1030,280,1734,1047,85,285,1746,1052,287,1755,1062,279,1780,1064,87,284,1821,1077,88,286,1826,1087,89,284,1853,1092,90,298,1886,1110,93,298,1904,1130,94,302,1938,1149,93,302,1953,1138,95,301,1976,1148,95,305,1986,1170,98,318,2010,1184,100,324,2038,1204,103,325,2069,1226,104,326,2064,1236,105,329,2084,1257,105,339,2127,1270,112,341,2161,1305,113,338,2170,1302,112,343,2185,1307,113,350,2185,1306,114,348,2182,1308]],"container":"<table class=\"display\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>FloorDate<\/th>\n      <th>Priority<\/th>\n      <th>Opened<\/th>\n      <th>Closed<\/th>\n      <th>CumSum<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"columnDefs":[{"className":"dt-right","targets":[3,4,5]},{"orderable":false,"targets":0}],"order":[],"autoWidth":false,"orderClasses":false,"orderCellsTop":true}},"evals":[],"jsHooks":[]}</script>
```
