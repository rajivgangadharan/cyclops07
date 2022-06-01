# Fusion Corporate Channels 








## Delivery Metrics 





###  Cycle Time


#### Summary

The below [Five-number summary](https://en.wikipedia.org/wiki/Five-number_summary) 
will provide a high level distribution of the cycle times. 
The 75% Qartile value is significant because that is the number which you can 
typically see as the turn around time (TAT) to service a work item.

<table class="table table-striped" style="width: auto !important; margin-left: auto; margin-right: auto;">
<caption>(\#tab:fcc-cycle-time-summ)5 Number Summary</caption>
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
   <td style="text-align:left;"> Critical </td>
   <td style="text-align:right;"> 65 </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 109.0 </td>
   <td style="text-align:right;"> 126.0 </td>
   <td style="text-align:right;"> 185.0 </td>
   <td style="text-align:right;"> 345 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Epic </td>
   <td style="text-align:left;"> High </td>
   <td style="text-align:right;"> 27 </td>
   <td style="text-align:right;"> 4 </td>
   <td style="text-align:right;"> 70.5 </td>
   <td style="text-align:right;"> 114.0 </td>
   <td style="text-align:right;"> 147.0 </td>
   <td style="text-align:right;"> 419 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Epic </td>
   <td style="text-align:left;"> Medium </td>
   <td style="text-align:right;"> 24 </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 52.0 </td>
   <td style="text-align:right;"> 100.5 </td>
   <td style="text-align:right;"> 146.5 </td>
   <td style="text-align:right;"> 260 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Story </td>
   <td style="text-align:left;"> Critical </td>
   <td style="text-align:right;"> 132 </td>
   <td style="text-align:right;"> 8 </td>
   <td style="text-align:right;"> 34.5 </td>
   <td style="text-align:right;"> 70.5 </td>
   <td style="text-align:right;"> 98.5 </td>
   <td style="text-align:right;"> 341 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Story </td>
   <td style="text-align:left;"> High </td>
   <td style="text-align:right;"> 192 </td>
   <td style="text-align:right;"> 4 </td>
   <td style="text-align:right;"> 14.0 </td>
   <td style="text-align:right;"> 28.0 </td>
   <td style="text-align:right;"> 79.5 </td>
   <td style="text-align:right;"> 377 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Story </td>
   <td style="text-align:left;"> Medium </td>
   <td style="text-align:right;"> 906 </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 25.0 </td>
   <td style="text-align:right;"> 45.0 </td>
   <td style="text-align:right;"> 77.0 </td>
   <td style="text-align:right;"> 405 </td>
  </tr>
</tbody>
</table>

#### Epics


<div class="figure" style="text-align: center">
<img src="04-fcc_files/figure-html/fcc-epics-cycle-time-trend-fig-1.png" alt="Cycle Time Trend" width="80%" />
<p class="caption">(\#fig:fcc-epics-cycle-time-trend-fig)Cycle Time Trend</p>
</div>


<table class="table table-striped" style="width: auto !important; margin-left: auto; margin-right: auto;">
<caption>(\#tab:fcc-epics-summary-metrics)5 Number Summary</caption>
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
   <td style="text-align:left;"> Critical </td>
   <td style="text-align:right;"> 65 </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 109.0 </td>
   <td style="text-align:right;"> 126.0 </td>
   <td style="text-align:right;"> 185.0 </td>
   <td style="text-align:right;"> 345 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Epic </td>
   <td style="text-align:left;"> High </td>
   <td style="text-align:right;"> 27 </td>
   <td style="text-align:right;"> 4 </td>
   <td style="text-align:right;"> 70.5 </td>
   <td style="text-align:right;"> 114.0 </td>
   <td style="text-align:right;"> 147.0 </td>
   <td style="text-align:right;"> 419 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Epic </td>
   <td style="text-align:left;"> Medium </td>
   <td style="text-align:right;"> 24 </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 52.0 </td>
   <td style="text-align:right;"> 100.5 </td>
   <td style="text-align:right;"> 146.5 </td>
   <td style="text-align:right;"> 260 </td>
  </tr>
</tbody>
</table>

#### Stories

<div class="figure" style="text-align: center">
<img src="04-fcc_files/figure-html/fcc-stories-cycle-time-trend-fig-1.png" alt="Cycle Time Trend" width="80%" />
<p class="caption">(\#fig:fcc-stories-cycle-time-trend-fig)Cycle Time Trend</p>
</div>


<table class="table table-striped" style="width: auto !important; margin-left: auto; margin-right: auto;">
<caption>(\#tab:fcc-story-summary-metrics)5 Number Summary</caption>
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
   <td style="text-align:left;"> Story </td>
   <td style="text-align:left;"> Critical </td>
   <td style="text-align:right;"> 132 </td>
   <td style="text-align:right;"> 8 </td>
   <td style="text-align:right;"> 34.5 </td>
   <td style="text-align:right;"> 70.5 </td>
   <td style="text-align:right;"> 98.5 </td>
   <td style="text-align:right;"> 341 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Story </td>
   <td style="text-align:left;"> High </td>
   <td style="text-align:right;"> 192 </td>
   <td style="text-align:right;"> 4 </td>
   <td style="text-align:right;"> 14.0 </td>
   <td style="text-align:right;"> 28.0 </td>
   <td style="text-align:right;"> 79.5 </td>
   <td style="text-align:right;"> 377 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Story </td>
   <td style="text-align:left;"> Medium </td>
   <td style="text-align:right;"> 906 </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 25.0 </td>
   <td style="text-align:right;"> 45.0 </td>
   <td style="text-align:right;"> 77.0 </td>
   <td style="text-align:right;"> 405 </td>
  </tr>
</tbody>
</table>

### Throughput

#### Epics

<div class="figure" style="text-align: center">
<img src="04-fcc_files/figure-html/fcc-completed-epics-week-fig-1.png" alt="Closed Epics by Week" width="80%" />
<p class="caption">(\#fig:fcc-completed-epics-week-fig)Closed Epics by Week</p>
</div>

The plot below shows the number of epics closed in every week, marked separately in different color based on priority

<img src="04-fcc_files/figure-html/fcc-epics-wk-agg-fig-1.png" width="80%" style="display: block; margin: auto;" />


<!-- - Density distribution -->

<!-- Gives and indication of the densities especially the occurrence of multiple maxima in the data. This can be due to multiple categories of work items which may be investigated further.  -->

<!-- ```{r fcc-density-distibution-closed-epics-fig, include=TRUE, echo=FALSE, out.width="80%", fig.align="center", fig.asp=.75, fig.cap="Priority based Density Distribution", message=FALSE, warning=FALSE} -->
<!-- epics.closed %>% violin_plot.CycleTimeVsPriority() -->
<!-- ``` -->


#### Stories


Tells us the number of work items (stories) completed aggregated for each 
week which is an indication of how stable the throughput is.

<img src="04-fcc_files/figure-html/fcc-completed-items-week-fig-1.png" width="80%" style="display: block; margin: auto;" />

The plot below shows the number of stories closed in every week, marked separately in different color based on priority


<div class="figure" style="text-align: center">
<img src="04-fcc_files/figure-html/fcc-stories-wk-agg-fig-1.png" alt="Number of Stories Closed in a Week colored by Priority" width="80%" />
<p class="caption">(\#fig:fcc-stories-wk-agg-fig)Number of Stories Closed in a Week colored by Priority</p>
</div>

- Density distribution

Gives and indication of the densities especially the occurrence of multiple maxima in the data. This can be due to multiple categories of work items which may be investigated further. 

<div class="figure" style="text-align: center">
<img src="04-fcc_files/figure-html/fcc-density-distibution-closed-stories-fig-1.png" alt="Priority based Density Distribution" width="80%" />
<p class="caption">(\#fig:fcc-density-distibution-closed-stories-fig)Priority based Density Distribution</p>
</div>


### Flow

#### Work in Progress (WiP)

##### Epics 



<div class="figure" style="text-align: center">
<img src="04-fcc_files/figure-html/fcc-epics-work-in-progress-fig -1.png" alt="WiP in Days" width="80%" />
<p class="caption">(\#fig:fcc-epics-work-in-progress-fig )WiP in Days</p>
</div>

##### Stories



<div class="figure" style="text-align: center">
<img src="04-fcc_files/figure-html/fcc-stories-work-in-progress-fig -1.png" alt="WiP in Days" width="80%" />
<p class="caption">(\#fig:fcc-stories-work-in-progress-fig )WiP in Days</p>
</div>

#### Inflow/OutFlow

##### Epics

<img src="04-fcc_files/figure-html/fcc-epics-inflow-outflow-1.png" width="80%" style="display: block; margin: auto;" />

<img src="04-fcc_files/figure-html/fcc-epics-inflow-outflow-cumsumm-1.png" width="80%" style="display: block; margin: auto;" />


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
<div id="htmlwidget-8813bebc2d40f288d833" style="width:100%;height:400px;" class="plotly html-widget"></div>
<script type="application/json" data-for="htmlwidget-8813bebc2d40f288d833">{"x":{"visdat":{"7d286e9be6":["function () ","plotlyVisDat"]},"cur_data":"7d286e9be6","attrs":{"7d286e9be6":{"x":{},"y":{},"mode":"lines+markers","color":{},"colors":["#D55E00","#E69F00","#56B4E9","#F0E442","#999999"],"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"scatter"}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"legend":{"orientation":"h","xanchor":"center","x":0.5,"y":-0.2},"xaxis":{"domain":[0,1],"automargin":true,"title":"FloorDate"},"yaxis":{"domain":[0,1],"automargin":true,"title":"CumSum"},"hovermode":"closest","showlegend":true},"source":"A","config":{"modeBarButtonsToAdd":["hoverclosest","hovercompare"],"showSendToCloud":false,"displaylogo":false,"modeBarButtonsToRemove":["zoomIn2d","zoomOut2d"]},"data":[{"x":["2020-11-29","2021-01-03","2021-01-10","2021-01-31","2021-02-07","2021-02-14","2021-02-21","2021-03-07","2021-03-14","2021-03-21","2021-04-04","2021-04-11","2021-05-02","2021-05-09","2021-05-23","2021-06-06","2021-06-13","2021-06-20","2021-07-11","2021-08-08","2021-08-15","2021-08-22","2021-08-29","2021-09-05","2021-09-12","2021-09-19","2021-09-26","2021-10-03","2021-10-17","2021-10-24","2021-11-07","2021-11-21","2021-12-05","2021-12-12","2022-01-16","2022-02-06","2022-02-20","2022-03-13","2022-03-20","2022-03-27","2022-04-03","2022-05-08","2022-05-15"],"y":[1,2,9,11,14,16,17,16,17,20,23,28,30,32,34,35,36,36,37,43,50,52,55,55,56,58,59,60,59,61,61,62,61,56,57,58,63,65,74,73,76,79,81],"mode":"lines+markers","type":"scatter","name":"Medium","marker":{"color":"rgba(86,180,233,1)","line":{"color":"rgba(86,180,233,1)"}},"textfont":{"color":"rgba(86,180,233,1)"},"error_y":{"color":"rgba(86,180,233,1)"},"error_x":{"color":"rgba(86,180,233,1)"},"line":{"color":"rgba(86,180,233,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":["2020-11-29","2021-01-03","2021-01-10","2021-02-07","2021-02-21","2021-02-28","2021-03-07","2021-03-14","2021-03-28","2021-04-11","2021-05-02","2021-05-30","2021-06-13","2021-06-20","2021-06-27","2021-07-04","2021-08-08","2021-08-15","2021-08-29","2021-09-05","2021-09-12","2021-10-03","2021-11-14","2021-12-05","2021-12-12","2022-01-02","2022-01-16","2022-03-06","2022-03-27","2022-04-03","2022-05-08"],"y":[1,2,3,4,11,10,10,11,13,15,16,17,16,17,18,21,24,25,20,18,21,22,23,26,24,27,26,31,30,31,34],"mode":"lines+markers","type":"scatter","name":"High","marker":{"color":"rgba(230,159,0,1)","line":{"color":"rgba(230,159,0,1)"}},"textfont":{"color":"rgba(230,159,0,1)"},"error_y":{"color":"rgba(230,159,0,1)"},"error_x":{"color":"rgba(230,159,0,1)"},"line":{"color":"rgba(230,159,0,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":["2020-11-29","2020-12-13","2021-01-03","2021-01-17","2021-01-31","2021-02-07","2021-02-21","2021-02-28","2021-03-07","2021-03-14","2021-03-21","2021-04-04","2021-04-11","2021-05-02","2021-05-09","2021-05-16","2021-05-23","2021-05-30","2021-06-06","2021-06-13","2021-06-20","2021-06-27","2021-07-11","2021-07-18","2021-07-25","2021-08-08","2021-08-15","2021-08-22","2021-08-29","2021-09-05","2021-09-12","2021-09-26","2021-10-31","2021-11-07","2021-11-14","2021-11-21","2021-11-28","2021-12-05","2021-12-12","2022-01-02","2022-02-20","2022-03-06","2022-03-13","2022-03-20","2022-03-27","2022-04-03","2022-05-08","2022-05-15"],"y":[10,13,14,16,18,19,28,40,38,41,46,47,48,49,51,52,56,57,58,53,50,44,46,47,46,49,53,56,55,58,57,58,57,58,63,65,65,69,60,58,59,60,62,67,57,54,57,58],"mode":"lines+markers","type":"scatter","name":"Critical","marker":{"color":"rgba(213,94,0,1)","line":{"color":"rgba(213,94,0,1)"}},"textfont":{"color":"rgba(213,94,0,1)"},"error_y":{"color":"rgba(213,94,0,1)"},"error_x":{"color":"rgba(213,94,0,1)"},"line":{"color":"rgba(213,94,0,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot","plotly_sunburstclick"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>
</div>
```


```{=html}
<div id="htmlwidget-82ac31a3e9cef9e5e089" style="width:100%;height:auto;" class="datatables html-widget"></div>
<script type="application/json" data-for="htmlwidget-82ac31a3e9cef9e5e089">{"x":{"filter":"top","vertical":false,"filterHTML":"<tr>\n  <td><\/td>\n  <td data-type=\"date\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"1.606608e+12\" data-max=\"1652572800000\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"factor\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"width: 100%; display: none;\">\n      <select multiple=\"multiple\" style=\"width: 100%;\" data-options=\"[&quot;Critical&quot;,&quot;High&quot;,&quot;Medium&quot;,&quot;Low&quot;,&quot;None&quot;]\"><\/select>\n    <\/div>\n  <\/td>\n  <td data-type=\"number\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"0\" data-max=\"12\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"number\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"0\" data-max=\"11\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"number\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"1\" data-max=\"81\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n<\/tr>","data":[["1","2","3","4","5","6","7","8","9","10","11","12","13","14","15","16","17","18","19","20","21","22","23","24","25","26","27","28","29","30","31","32","33","34","35","36","37","38","39","40","41","42","43","44","45","46","47","48","49","50","51","52","53","54","55","56","57","58","59","60","61","62","63","64","65","66","67","68","69","70","71","72","73","74","75","76","77","78","79","80","81","82","83","84","85","86","87","88","89","90","91","92","93","94","95","96","97","98","99","100","101","102","103","104","105","106","107","108","109","110","111","112","113","114","115","116","117","118","119","120","121","122"],["2020-11-29","2020-11-29","2020-11-29","2020-12-13","2021-01-03","2021-01-03","2021-01-03","2021-01-10","2021-01-10","2021-01-17","2021-01-31","2021-01-31","2021-02-07","2021-02-07","2021-02-07","2021-02-14","2021-02-21","2021-02-21","2021-02-21","2021-02-28","2021-02-28","2021-03-07","2021-03-07","2021-03-07","2021-03-14","2021-03-14","2021-03-14","2021-03-21","2021-03-21","2021-03-28","2021-04-04","2021-04-04","2021-04-11","2021-04-11","2021-04-11","2021-05-02","2021-05-02","2021-05-02","2021-05-09","2021-05-09","2021-05-16","2021-05-23","2021-05-23","2021-05-30","2021-05-30","2021-06-06","2021-06-06","2021-06-13","2021-06-13","2021-06-13","2021-06-20","2021-06-20","2021-06-20","2021-06-27","2021-06-27","2021-07-04","2021-07-11","2021-07-11","2021-07-18","2021-07-25","2021-08-08","2021-08-08","2021-08-08","2021-08-15","2021-08-15","2021-08-15","2021-08-22","2021-08-22","2021-08-29","2021-08-29","2021-08-29","2021-09-05","2021-09-05","2021-09-05","2021-09-12","2021-09-12","2021-09-12","2021-09-19","2021-09-26","2021-09-26","2021-10-03","2021-10-03","2021-10-17","2021-10-24","2021-10-31","2021-11-07","2021-11-07","2021-11-14","2021-11-14","2021-11-21","2021-11-21","2021-11-28","2021-12-05","2021-12-05","2021-12-05","2021-12-12","2021-12-12","2021-12-12","2022-01-02","2022-01-02","2022-01-16","2022-01-16","2022-02-06","2022-02-20","2022-02-20","2022-03-06","2022-03-06","2022-03-13","2022-03-13","2022-03-20","2022-03-20","2022-03-27","2022-03-27","2022-03-27","2022-04-03","2022-04-03","2022-04-03","2022-05-08","2022-05-08","2022-05-08","2022-05-15","2022-05-15"],["Critical","High","Medium","Critical","Critical","High","Medium","High","Medium","Critical","Critical","Medium","Critical","High","Medium","Medium","Critical","High","Medium","Critical","High","Critical","High","Medium","Critical","High","Medium","Critical","Medium","High","Critical","Medium","Critical","High","Medium","Critical","High","Medium","Critical","Medium","Critical","Critical","Medium","Critical","High","Critical","Medium","Critical","High","Medium","Critical","High","Medium","Critical","High","High","Critical","Medium","Critical","Critical","Critical","High","Medium","Critical","High","Medium","Critical","Medium","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Medium","Critical","Medium","High","Medium","Medium","Medium","Critical","Critical","Medium","Critical","High","Critical","Medium","Critical","Critical","High","Medium","Critical","High","Medium","Critical","High","High","Medium","Medium","Critical","Medium","Critical","High","Critical","Medium","Critical","Medium","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Critical","Medium"],[10,1,1,3,1,1,1,1,7,2,2,2,1,2,3,2,10,7,1,12,0,1,1,0,3,2,2,5,3,2,1,3,1,2,5,1,1,2,2,3,1,4,2,1,1,1,1,2,0,3,0,1,1,0,1,3,2,1,1,1,4,3,6,4,1,7,3,2,5,3,7,3,0,1,0,3,1,2,1,1,1,1,1,2,0,1,1,5,1,2,3,1,7,4,1,2,4,0,0,3,0,1,1,1,5,1,5,2,2,8,9,1,0,0,1,4,3,3,3,3,1,2],[0,0,0,0,0,0,0,0,0,0,0,0,0,1,0,0,1,0,0,0,1,3,1,1,0,1,1,0,0,0,0,0,0,0,0,0,0,0,0,1,0,0,0,0,0,0,0,7,1,2,3,0,1,6,0,0,0,0,0,2,1,0,0,0,0,0,0,0,6,8,4,0,2,1,1,0,0,0,0,0,0,0,2,0,1,0,1,0,0,0,2,1,3,1,2,11,6,5,2,0,1,0,0,0,0,0,0,0,0,3,0,11,1,1,4,3,0,0,0,0,0,0],[10,1,1,13,14,2,2,3,9,16,18,11,19,4,14,16,28,11,17,40,10,38,10,16,41,11,17,46,20,13,47,23,48,15,28,49,16,30,51,32,52,56,34,57,17,58,35,53,16,36,50,17,36,44,18,21,46,37,47,46,49,24,43,53,25,50,56,52,55,20,55,58,18,55,57,21,56,58,58,59,22,60,59,61,57,58,61,63,23,65,62,65,69,26,61,60,24,56,58,27,26,57,58,59,63,60,31,62,65,67,74,57,30,73,54,31,76,57,34,79,58,81]],"container":"<table class=\"display\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>FloorDate<\/th>\n      <th>Priority<\/th>\n      <th>Opened<\/th>\n      <th>Closed<\/th>\n      <th>CumSum<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"columnDefs":[{"className":"dt-right","targets":[3,4,5]},{"orderable":false,"targets":0}],"order":[],"autoWidth":false,"orderClasses":false,"orderCellsTop":true}},"evals":[],"jsHooks":[]}</script>
```
##### Stories

<img src="04-fcc_files/figure-html/fcc-stories-inflow-outflow-1.png" width="80%" style="display: block; margin: auto;" />

<img src="04-fcc_files/figure-html/fcc-stories-inflow-outflow-cumsumm-1.png" width="80%" style="display: block; margin: auto;" />

## Defect Metrics






###  Cycle Time

Below is the [5 Number Summary](https://en.wikipedia.org/wiki/Five-number_summary) 
of the entire data set. The 75% Qartile value is significant because that is the 
number which you can typically see as the turn around time (TAT) to service a defect.

#### Summary

<table class="table table-striped" style="width: auto !important; margin-left: auto; margin-right: auto;">
<caption>(\#tab:fcc-defects-tab-cycle-time-basic-stats)5 Number Summary</caption>
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
   <td style="text-align:right;"> 3 </td>
   <td style="text-align:right;"> 7 </td>
   <td style="text-align:right;"> 22 </td>
   <td style="text-align:right;"> 447 </td>
  </tr>
</tbody>
</table>


#### Cycle Time Trend

This reflects the capacity/capability of the team to resolve across all 
priorities as indicated by a trend.

<div class="figure" style="text-align: center">
<img src="04-fcc_files/figure-html/fcc-defects-cycle-time-trend-all-1.png" alt="All Severities" width="80%" />
<p class="caption">(\#fig:fcc-defects-cycle-time-trend-all)All Severities</p>
</div>


#### 5 Number Summary

<table class="table table-striped" style="width: auto !important; margin-left: auto; margin-right: auto;">
<caption>(\#tab:fcc-defects-cycle-time-summary)All Severities</caption>
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
   <td style="text-align:left;"> Critical </td>
   <td style="text-align:right;"> 65 </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 109.0 </td>
   <td style="text-align:right;"> 126.0 </td>
   <td style="text-align:right;"> 185.0 </td>
   <td style="text-align:right;"> 345 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Epic </td>
   <td style="text-align:left;"> High </td>
   <td style="text-align:right;"> 27 </td>
   <td style="text-align:right;"> 4 </td>
   <td style="text-align:right;"> 70.5 </td>
   <td style="text-align:right;"> 114.0 </td>
   <td style="text-align:right;"> 147.0 </td>
   <td style="text-align:right;"> 419 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Epic </td>
   <td style="text-align:left;"> Medium </td>
   <td style="text-align:right;"> 24 </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 52.0 </td>
   <td style="text-align:right;"> 100.5 </td>
   <td style="text-align:right;"> 146.5 </td>
   <td style="text-align:right;"> 260 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Story </td>
   <td style="text-align:left;"> Critical </td>
   <td style="text-align:right;"> 132 </td>
   <td style="text-align:right;"> 8 </td>
   <td style="text-align:right;"> 34.5 </td>
   <td style="text-align:right;"> 70.5 </td>
   <td style="text-align:right;"> 98.5 </td>
   <td style="text-align:right;"> 341 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Story </td>
   <td style="text-align:left;"> High </td>
   <td style="text-align:right;"> 192 </td>
   <td style="text-align:right;"> 4 </td>
   <td style="text-align:right;"> 14.0 </td>
   <td style="text-align:right;"> 28.0 </td>
   <td style="text-align:right;"> 79.5 </td>
   <td style="text-align:right;"> 377 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Story </td>
   <td style="text-align:left;"> Medium </td>
   <td style="text-align:right;"> 906 </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 25.0 </td>
   <td style="text-align:right;"> 45.0 </td>
   <td style="text-align:right;"> 77.0 </td>
   <td style="text-align:right;"> 405 </td>
  </tr>
</tbody>
</table>

<div class="figure" style="text-align: center">
<img src="04-fcc_files/figure-html/fcc-defects-cycle-time-trend-for-hnc-1.png" alt="High and Critical" width="80%" />
<p class="caption">(\#fig:fcc-defects-cycle-time-trend-for-hnc)High and Critical</p>
</div>


<table class="table table-striped" style="width: auto !important; margin-left: auto; margin-right: auto;">
<caption>(\#tab:fcc-defects-cycle-time-stat-for-high-and-critical)5 Number Summary for High and Critical Defects</caption>
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
   <td style="text-align:left;"> Defect </td>
   <td style="text-align:left;"> Critical </td>
   <td style="text-align:right;"> 471 </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 2 </td>
   <td style="text-align:right;"> 5 </td>
   <td style="text-align:right;"> 12.5 </td>
   <td style="text-align:right;"> 244 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Defect </td>
   <td style="text-align:left;"> High </td>
   <td style="text-align:right;"> 1966 </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 3 </td>
   <td style="text-align:right;"> 7 </td>
   <td style="text-align:right;"> 20.0 </td>
   <td style="text-align:right;"> 447 </td>
  </tr>
</tbody>
</table>


### Throughput


<div class="figure" style="text-align: center">
<img src="04-fcc_files/figure-html/fcc-defects-closed-metric-for-each-week-1.png" alt="Closure metrics - All Defects" width="80%" />
<p class="caption">(\#fig:fcc-defects-closed-metric-for-each-week)Closure metrics - All Defects</p>
</div>


<div class="figure" style="text-align: center">
<img src="04-fcc_files/figure-html/fcc-defects-fig-completed-hnc-defects-week-1.png" alt="Closed defects by Week" width="80%" />
<p class="caption">(\#fig:fcc-defects-fig-completed-hnc-defects-week)Closed defects by Week</p>
</div>




The plot below shows the number of defects closed in every week, marked separately in different color based on priority


<img src="04-fcc_files/figure-html/fcc-defects-all-wk-agg-fig-1.png" width="80%" style="display: block; margin: auto;" />

<img src="04-fcc_files/figure-html/fcc-defects-fig-hnc-wk-agg-1.png" width="80%" style="display: block; margin: auto;" />


```{=html}
<div id="htmlwidget-1172805515c4fc992ac5" style="width:100%;height:auto;" class="datatables html-widget"></div>
<script type="application/json" data-for="htmlwidget-1172805515c4fc992ac5">{"x":{"filter":"top","vertical":false,"filterHTML":"<tr>\n  <td><\/td>\n  <td data-type=\"date\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"1.606608e+12\" data-max=\"1653177600000\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"factor\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"width: 100%; display: none;\">\n      <select multiple=\"multiple\" style=\"width: 100%;\" data-options=\"[&quot;Critical&quot;,&quot;High&quot;,&quot;Medium&quot;,&quot;Low&quot;,&quot;None&quot;]\"><\/select>\n    <\/div>\n  <\/td>\n  <td data-type=\"integer\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"1\" data-max=\"108\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n<\/tr>","data":[["1","2","3","4","5","6","7","8","9","10","11","12","13","14","15","16","17","18","19","20","21","22","23","24","25","26","27","28","29","30","31","32","33","34","35","36","37","38","39","40","41","42","43","44","45","46","47","48","49","50","51","52","53","54","55","56","57","58","59","60","61","62","63","64","65","66","67","68","69","70","71","72","73","74","75","76","77","78","79","80","81","82","83","84","85","86","87","88","89","90","91","92","93","94","95","96","97","98","99","100","101","102","103","104","105","106","107","108","109","110","111","112","113","114","115","116","117","118","119","120","121","122","123","124","125","126","127","128","129","130","131","132","133","134","135","136","137","138","139","140","141","142","143","144","145","146","147","148","149","150","151","152","153","154","155","156","157","158","159","160","161","162","163","164","165","166","167","168","169","170","171","172","173","174","175","176","177","178","179","180","181","182","183","184","185","186","187","188","189","190","191","192","193","194","195","196","197","198","199","200","201","202","203","204","205","206","207","208","209","210","211","212","213","214","215","216","217","218","219","220","221","222","223","224","225","226","227","228","229","230","231","232","233","234","235","236","237","238","239","240","241","242","243","244","245","246","247","248","249","250","251","252","253","254","255","256","257","258","259","260","261","262","263","264","265","266","267","268","269","270","271","272","273","274","275","276","277","278","279","280","281","282","283","284","285","286","287","288"],["2020-11-29","2020-11-29","2020-11-29","2020-12-06","2020-12-06","2020-12-06","2020-12-06","2020-12-13","2020-12-13","2020-12-13","2020-12-13","2020-12-20","2021-01-03","2021-01-03","2021-01-10","2021-01-10","2021-01-17","2021-01-17","2021-01-17","2021-01-24","2021-01-24","2021-01-24","2021-01-24","2021-01-31","2021-01-31","2021-01-31","2021-01-31","2021-02-07","2021-02-07","2021-02-07","2021-02-07","2021-02-14","2021-02-14","2021-02-14","2021-02-14","2021-02-21","2021-02-21","2021-02-21","2021-02-21","2021-02-28","2021-02-28","2021-02-28","2021-02-28","2021-03-07","2021-03-07","2021-03-07","2021-03-07","2021-03-14","2021-03-14","2021-03-14","2021-03-14","2021-03-21","2021-03-21","2021-03-21","2021-03-21","2021-03-28","2021-03-28","2021-03-28","2021-03-28","2021-04-04","2021-04-04","2021-04-04","2021-04-04","2021-04-11","2021-04-11","2021-04-11","2021-04-11","2021-04-18","2021-04-18","2021-04-18","2021-04-18","2021-04-25","2021-04-25","2021-04-25","2021-04-25","2021-05-02","2021-05-02","2021-05-02","2021-05-02","2021-05-09","2021-05-09","2021-05-09","2021-05-16","2021-05-16","2021-05-16","2021-05-16","2021-05-23","2021-05-23","2021-05-23","2021-05-23","2021-05-30","2021-05-30","2021-05-30","2021-05-30","2021-06-06","2021-06-06","2021-06-06","2021-06-06","2021-06-13","2021-06-13","2021-06-13","2021-06-13","2021-06-20","2021-06-20","2021-06-20","2021-06-20","2021-06-27","2021-06-27","2021-06-27","2021-06-27","2021-07-04","2021-07-04","2021-07-04","2021-07-04","2021-07-11","2021-07-11","2021-07-11","2021-07-11","2021-07-18","2021-07-18","2021-07-18","2021-07-25","2021-07-25","2021-07-25","2021-07-25","2021-08-01","2021-08-01","2021-08-01","2021-08-01","2021-08-08","2021-08-08","2021-08-08","2021-08-08","2021-08-15","2021-08-15","2021-08-15","2021-08-15","2021-08-22","2021-08-22","2021-08-22","2021-08-22","2021-08-29","2021-08-29","2021-08-29","2021-08-29","2021-09-05","2021-09-05","2021-09-05","2021-09-05","2021-09-12","2021-09-12","2021-09-12","2021-09-12","2021-09-19","2021-09-19","2021-09-19","2021-09-26","2021-09-26","2021-09-26","2021-09-26","2021-10-03","2021-10-03","2021-10-03","2021-10-03","2021-10-10","2021-10-10","2021-10-10","2021-10-10","2021-10-17","2021-10-17","2021-10-17","2021-10-17","2021-10-24","2021-10-24","2021-10-24","2021-10-24","2021-10-31","2021-10-31","2021-10-31","2021-11-07","2021-11-07","2021-11-07","2021-11-14","2021-11-14","2021-11-14","2021-11-14","2021-11-21","2021-11-21","2021-11-21","2021-11-28","2021-11-28","2021-11-28","2021-11-28","2021-12-05","2021-12-05","2021-12-05","2021-12-05","2021-12-12","2021-12-12","2021-12-12","2021-12-12","2021-12-19","2021-12-19","2021-12-26","2021-12-26","2021-12-26","2021-12-26","2022-01-02","2022-01-02","2022-01-02","2022-01-02","2022-01-09","2022-01-09","2022-01-09","2022-01-16","2022-01-16","2022-01-16","2022-01-16","2022-01-23","2022-01-23","2022-01-23","2022-01-23","2022-01-30","2022-01-30","2022-01-30","2022-01-30","2022-02-06","2022-02-06","2022-02-06","2022-02-06","2022-02-13","2022-02-13","2022-02-13","2022-02-13","2022-02-20","2022-02-20","2022-02-20","2022-02-20","2022-02-27","2022-02-27","2022-02-27","2022-02-27","2022-03-06","2022-03-06","2022-03-06","2022-03-06","2022-03-13","2022-03-13","2022-03-13","2022-03-20","2022-03-20","2022-03-20","2022-03-20","2022-03-27","2022-03-27","2022-03-27","2022-03-27","2022-04-03","2022-04-03","2022-04-03","2022-04-03","2022-04-10","2022-04-10","2022-04-10","2022-04-10","2022-04-17","2022-04-17","2022-04-17","2022-04-17","2022-04-24","2022-04-24","2022-04-24","2022-04-24","2022-05-01","2022-05-01","2022-05-01","2022-05-01","2022-05-08","2022-05-08","2022-05-08","2022-05-08","2022-05-15","2022-05-15","2022-05-15","2022-05-15","2022-05-22","2022-05-22","2022-05-22"],["Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","High","High","Medium","High","Medium","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium"],[12,13,2,1,9,16,1,5,33,26,2,1,6,3,2,6,16,15,2,2,5,7,1,1,12,7,2,3,14,28,2,8,37,29,2,7,47,27,3,20,86,64,4,14,103,78,2,4,30,60,5,10,50,76,4,4,26,57,4,4,34,26,2,2,25,39,3,6,29,64,7,6,32,44,4,6,18,38,5,1,2,17,4,20,37,1,8,32,54,8,11,39,54,3,3,37,68,3,12,68,101,4,20,87,108,8,13,84,108,10,2,6,19,3,1,4,15,1,4,19,24,15,40,50,2,6,14,18,1,8,28,19,2,8,22,42,2,18,53,82,8,14,73,85,3,4,24,35,2,3,5,5,2,6,11,10,2,16,18,3,9,15,34,4,3,10,8,1,1,21,17,3,5,33,44,3,2,21,19,4,16,26,4,10,18,2,8,18,21,11,30,38,1,14,50,61,8,13,86,88,6,1,2,1,4,8,2,3,6,4,1,3,8,1,7,6,6,1,1,3,12,3,7,23,15,3,6,7,9,3,6,13,11,4,6,25,41,6,2,11,16,1,4,14,7,1,7,25,25,21,55,49,3,25,79,103,7,3,4,20,7,1,8,26,2,2,15,29,2,4,10,20,5,2,6,10,2,3,12,11,3,6,11,27,3,2,3,5]],"container":"<table class=\"display\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>FloorDate<\/th>\n      <th>Priority<\/th>\n      <th>NumClosed<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"columnDefs":[{"className":"dt-right","targets":3},{"orderable":false,"targets":0}],"order":[],"autoWidth":false,"orderClasses":false,"orderCellsTop":true}},"evals":[],"jsHooks":[]}</script>
```

- Density distribution

Gives and indication of the densities especially the occurrence of multiple maxima in the data. This can be due to multiple categories of work items which may be investigated further. Below are the violin plots for all defects and also high and critical defects.

<div class="figure" style="text-align: center">
<img src="04-fcc_files/figure-html/fcc-defects-fig-densdist-closed-overall-1.png" alt="Priority based Density Distribution" width="80%" />
<p class="caption">(\#fig:fcc-defects-fig-densdist-closed-overall)Priority based Density Distribution</p>
</div>



### Flow

#### Work in Progress (WiP)

<img src="04-fcc_files/figure-html/fcc-defects-fig-areaplot-wip-1.png" width="80%" style="display: block; margin: auto;" />

#### Inflow Outflow

<img src="04-fcc_files/figure-html/fcc-defects-inflow-outflow-1.png" width="80%" style="display: block; margin: auto;" />

<img src="04-fcc_files/figure-html/fcc-defects-inflow-outflow-cumsumm-1.png" width="80%" style="display: block; margin: auto;" />


```{=html}
<div id="htmlwidget-825b2d90f7e736af4185" style="width:100%;height:auto;" class="datatables html-widget"></div>
<script type="application/json" data-for="htmlwidget-825b2d90f7e736af4185">{"x":{"filter":"top","vertical":false,"filterHTML":"<tr>\n  <td><\/td>\n  <td data-type=\"date\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"1.606608e+12\" data-max=\"1653177600000\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"factor\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"width: 100%; display: none;\">\n      <select multiple=\"multiple\" style=\"width: 100%;\" data-options=\"[&quot;Critical&quot;,&quot;High&quot;,&quot;Medium&quot;,&quot;Low&quot;,&quot;None&quot;]\"><\/select>\n    <\/div>\n  <\/td>\n  <td data-type=\"integer\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"1\" data-max=\"104\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"number\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"0\" data-max=\"109\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n  <td data-type=\"number\" style=\"vertical-align: top;\">\n    <div class=\"form-group has-feedback\" style=\"margin-bottom: auto;\">\n      <input type=\"search\" placeholder=\"All\" class=\"form-control\" style=\"width: 100%;\"/>\n      <span class=\"glyphicon glyphicon-remove-circle form-control-feedback\"><\/span>\n    <\/div>\n    <div style=\"display: none;position: absolute;width: 200px;opacity: 1\">\n      <div data-min=\"1\" data-max=\"1026\"><\/div>\n      <span style=\"float: left;\"><\/span>\n      <span style=\"float: right;\"><\/span>\n    <\/div>\n  <\/td>\n<\/tr>","data":[["1","2","3","4","5","6","7","8","9","10","11","12","13","14","15","16","17","18","19","20","21","22","23","24","25","26","27","28","29","30","31","32","33","34","35","36","37","38","39","40","41","42","43","44","45","46","47","48","49","50","51","52","53","54","55","56","57","58","59","60","61","62","63","64","65","66","67","68","69","70","71","72","73","74","75","76","77","78","79","80","81","82","83","84","85","86","87","88","89","90","91","92","93","94","95","96","97","98","99","100","101","102","103","104","105","106","107","108","109","110","111","112","113","114","115","116","117","118","119","120","121","122","123","124","125","126","127","128","129","130","131","132","133","134","135","136","137","138","139","140","141","142","143","144","145","146","147","148","149","150","151","152","153","154","155","156","157","158","159","160","161","162","163","164","165","166","167","168","169","170","171","172","173","174","175","176","177","178","179","180","181","182","183","184","185","186","187","188","189","190","191","192","193","194","195","196","197","198","199","200","201","202","203","204","205","206","207","208","209","210","211","212","213","214","215","216","217","218","219","220","221","222","223","224","225","226","227","228","229","230","231","232","233","234","235","236","237","238","239","240","241","242","243","244","245","246","247","248","249","250","251","252","253","254","255","256","257","258","259","260","261","262","263","264","265","266","267","268","269","270","271","272","273","274","275","276","277","278","279","280","281","282","283","284","285","286","287","288","289","290","291","292","293","294","295","296","297","298","299","300","301","302","303","304","305","306","307","308"],["2020-11-29","2020-11-29","2020-11-29","2020-11-29","2020-12-06","2020-12-06","2020-12-06","2020-12-06","2020-12-13","2020-12-13","2020-12-13","2020-12-13","2020-12-20","2020-12-20","2020-12-20","2020-12-27","2020-12-27","2020-12-27","2021-01-03","2021-01-03","2021-01-03","2021-01-03","2021-01-10","2021-01-10","2021-01-10","2021-01-10","2021-01-17","2021-01-17","2021-01-17","2021-01-17","2021-01-24","2021-01-24","2021-01-24","2021-01-24","2021-01-31","2021-01-31","2021-01-31","2021-01-31","2021-02-07","2021-02-07","2021-02-07","2021-02-07","2021-02-14","2021-02-14","2021-02-14","2021-02-14","2021-02-21","2021-02-21","2021-02-21","2021-02-21","2021-02-28","2021-02-28","2021-02-28","2021-02-28","2021-03-07","2021-03-07","2021-03-07","2021-03-07","2021-03-14","2021-03-14","2021-03-14","2021-03-14","2021-03-21","2021-03-21","2021-03-21","2021-03-21","2021-03-28","2021-03-28","2021-03-28","2021-03-28","2021-04-04","2021-04-04","2021-04-04","2021-04-04","2021-04-11","2021-04-11","2021-04-11","2021-04-11","2021-04-18","2021-04-18","2021-04-18","2021-04-18","2021-04-25","2021-04-25","2021-04-25","2021-04-25","2021-05-02","2021-05-02","2021-05-02","2021-05-02","2021-05-09","2021-05-09","2021-05-09","2021-05-16","2021-05-16","2021-05-16","2021-05-16","2021-05-23","2021-05-23","2021-05-23","2021-05-23","2021-05-30","2021-05-30","2021-05-30","2021-05-30","2021-06-06","2021-06-06","2021-06-06","2021-06-06","2021-06-13","2021-06-13","2021-06-13","2021-06-13","2021-06-20","2021-06-20","2021-06-20","2021-06-20","2021-06-27","2021-06-27","2021-06-27","2021-06-27","2021-07-04","2021-07-04","2021-07-04","2021-07-04","2021-07-11","2021-07-11","2021-07-11","2021-07-11","2021-07-18","2021-07-18","2021-07-18","2021-07-18","2021-07-25","2021-07-25","2021-07-25","2021-07-25","2021-08-01","2021-08-01","2021-08-01","2021-08-01","2021-08-08","2021-08-08","2021-08-08","2021-08-08","2021-08-15","2021-08-15","2021-08-15","2021-08-15","2021-08-22","2021-08-22","2021-08-22","2021-08-22","2021-08-29","2021-08-29","2021-08-29","2021-08-29","2021-09-05","2021-09-05","2021-09-05","2021-09-05","2021-09-12","2021-09-12","2021-09-12","2021-09-12","2021-09-19","2021-09-19","2021-09-19","2021-09-19","2021-09-26","2021-09-26","2021-09-26","2021-09-26","2021-10-03","2021-10-03","2021-10-03","2021-10-03","2021-10-10","2021-10-10","2021-10-10","2021-10-10","2021-10-17","2021-10-17","2021-10-17","2021-10-17","2021-10-24","2021-10-24","2021-10-24","2021-10-24","2021-10-31","2021-10-31","2021-10-31","2021-10-31","2021-11-07","2021-11-07","2021-11-07","2021-11-07","2021-11-14","2021-11-14","2021-11-14","2021-11-14","2021-11-21","2021-11-21","2021-11-21","2021-11-21","2021-11-28","2021-11-28","2021-11-28","2021-11-28","2021-12-05","2021-12-05","2021-12-05","2021-12-05","2021-12-12","2021-12-12","2021-12-12","2021-12-12","2021-12-19","2021-12-19","2021-12-19","2021-12-19","2021-12-26","2021-12-26","2021-12-26","2021-12-26","2022-01-02","2022-01-02","2022-01-02","2022-01-02","2022-01-09","2022-01-09","2022-01-09","2022-01-09","2022-01-16","2022-01-16","2022-01-16","2022-01-16","2022-01-23","2022-01-23","2022-01-23","2022-01-23","2022-01-30","2022-01-30","2022-01-30","2022-01-30","2022-02-06","2022-02-06","2022-02-06","2022-02-06","2022-02-13","2022-02-13","2022-02-13","2022-02-13","2022-02-20","2022-02-20","2022-02-20","2022-02-20","2022-02-27","2022-02-27","2022-02-27","2022-02-27","2022-03-06","2022-03-06","2022-03-06","2022-03-06","2022-03-13","2022-03-13","2022-03-13","2022-03-13","2022-03-20","2022-03-20","2022-03-20","2022-03-20","2022-03-27","2022-03-27","2022-03-27","2022-03-27","2022-04-03","2022-04-03","2022-04-03","2022-04-03","2022-04-10","2022-04-10","2022-04-10","2022-04-10","2022-04-17","2022-04-17","2022-04-17","2022-04-17","2022-04-24","2022-04-24","2022-04-24","2022-04-24","2022-05-01","2022-05-01","2022-05-01","2022-05-01","2022-05-08","2022-05-08","2022-05-08","2022-05-08","2022-05-15","2022-05-15","2022-05-15","2022-05-15","2022-05-22","2022-05-22","2022-05-22"],["Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","High","Medium","Low","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium","Low","Critical","High","Medium"],[23,68,52,4,4,19,28,5,2,37,35,8,3,5,2,3,2,1,1,7,15,2,3,4,7,1,2,34,36,6,1,18,20,2,7,43,37,7,9,54,32,4,7,75,50,6,16,52,61,3,15,83,104,4,6,59,88,8,5,26,43,3,8,43,95,10,4,13,13,3,7,39,72,9,5,28,65,7,14,30,52,2,6,29,55,5,1,31,53,4,2,22,38,7,36,61,9,14,30,72,2,6,39,64,6,8,50,67,3,14,55,67,7,20,83,91,10,7,23,67,11,4,19,32,4,7,29,38,1,8,32,57,2,13,40,54,11,19,26,37,4,10,38,62,3,13,53,57,6,17,54,103,5,19,56,97,2,12,24,61,8,8,19,40,4,19,38,30,5,5,31,26,5,10,42,30,6,4,29,22,4,7,39,45,3,18,53,70,5,8,30,41,3,15,26,59,5,17,25,58,4,21,36,59,8,17,37,63,7,19,57,95,8,13,55,90,17,3,12,12,2,3,8,1,1,3,18,25,6,6,18,19,11,13,12,14,8,7,7,17,9,9,27,23,4,9,30,27,11,7,28,37,8,4,26,24,2,8,24,18,1,7,39,36,1,8,31,33,6,20,74,91,3,13,34,87,11,2,15,14,3,7,15,22,3,6,23,40,1,4,17,24,2,11,17,20,1,9,32,51,8,5,28,41,2,1,2,10],[21,19,3,0,2,11,22,1,5,36,30,3,1,0,0,0,0,0,0,6,3,0,0,2,6,0,0,16,15,2,2,5,7,1,1,12,7,2,3,14,28,2,8,37,29,2,7,47,27,3,20,86,64,4,14,104,78,2,4,30,60,5,10,50,76,4,4,26,57,4,4,34,26,2,2,25,39,3,6,29,65,7,6,33,44,4,6,18,38,5,1,3,17,4,20,37,1,8,32,54,8,11,39,54,3,3,37,68,3,12,68,101,4,20,87,109,8,13,84,109,10,2,6,19,3,1,4,15,1,4,19,24,0,15,40,50,2,6,14,18,1,8,28,19,2,8,22,42,2,18,53,82,8,14,73,85,3,4,24,35,2,3,5,5,2,6,11,10,0,2,16,18,3,9,15,34,4,3,10,8,1,1,21,17,3,5,33,44,3,2,21,19,0,4,16,26,0,4,10,18,2,8,18,21,0,11,31,38,1,14,50,61,8,13,86,88,6,0,1,2,0,1,4,8,2,3,6,4,1,0,3,8,1,7,6,6,1,1,3,12,3,7,23,15,3,6,7,9,3,6,13,11,4,6,25,41,6,2,11,16,1,4,14,7,1,7,25,25,0,21,55,49,3,25,79,103,7,3,4,20,7,1,8,26,2,2,15,29,2,4,10,20,5,2,6,10,2,3,12,11,3,6,11,27,3,2,3,5],[2,49,49,4,4,57,55,8,1,58,60,13,60,65,15,63,67,16,2,64,79,18,5,66,80,19,7,84,101,23,6,97,114,24,12,128,144,29,18,168,148,31,17,206,169,35,26,211,203,35,21,208,243,35,13,163,253,41,14,159,236,39,12,152,255,45,12,139,211,44,15,144,257,51,18,147,283,55,26,148,270,50,26,144,281,51,21,157,296,50,22,176,317,25,192,341,58,31,190,359,52,26,190,369,55,31,203,368,55,33,190,334,58,33,186,316,60,27,125,274,61,29,138,287,62,35,163,310,62,39,176,343,64,37,176,347,73,50,188,366,76,52,198,409,77,57,229,424,81,56,230,445,78,61,213,457,77,69,213,483,83,74,227,518,85,87,254,538,90,90,269,546,92,91,296,542,94,92,315,556,97,98,333,584,97,111,353,610,99,117,362,632,102,128,372,665,107,141,387,705,109,154,405,743,117,160,411,768,123,165,418,802,123,165,387,804,134,168,398,814,136,170,402,807,135,170,414,828,140,176,429,839,150,182,435,847,157,188,439,852,163,190,443,860,164,193,466,878,172,194,481,904,176,192,482,887,172,198,495,889,172,201,520,918,172,202,526,926,178,201,545,968,178,189,500,952,182,188,511,946,178,194,518,942,179,198,526,953,178,198,533,957,175,207,544,967,174,213,564,1007,179,212,581,1021,178,211,580,1026]],"container":"<table class=\"display\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>FloorDate<\/th>\n      <th>Priority<\/th>\n      <th>Opened<\/th>\n      <th>Closed<\/th>\n      <th>CumSum<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"columnDefs":[{"className":"dt-right","targets":[3,4,5]},{"orderable":false,"targets":0}],"order":[],"autoWidth":false,"orderClasses":false,"orderCellsTop":true}},"evals":[],"jsHooks":[]}</script>
```
