Skip to content
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@AdelAltuwaijri 
AdelAltuwaijri
/
Combining-Predictive-Techniques
1
00
 Code Issues 0 Pull requests 0 Actions Projects 0 Wiki Security Insights Settings
Combining-Predictive-Techniques/Combining Predictive Tools.htm
@AdelAltuwaijri AdelAltuwaijri Add files via upload
e446a40 14 seconds ago
1943 lines (1872 sloc)  101 KB
  
<html>

<head>
<meta http-equiv=Content-Type content="text/html; charset=windows-1256">
<meta name=Generator content="Microsoft Word 15 (filtered)">
<style>
<!--
 /* Font Definitions */
 @font-face
	{font-family:Helvetica;
	panose-1:2 11 6 4 2 2 2 2 2 4;}
@font-face
	{font-family:"Cambria Math";
	panose-1:2 4 5 3 5 4 6 3 2 4;}
@font-face
	{font-family:Calibri;
	panose-1:2 15 5 2 2 2 4 3 2 4;}
@font-face
	{font-family:Cambria;
	panose-1:2 4 5 3 5 4 6 3 2 4;}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{margin-top:0cm;
	margin-right:0cm;
	margin-bottom:10.0pt;
	margin-left:0cm;
	line-height:120%;
	font-size:10.5pt;
	font-family:"Cambria",serif;}
h2
	{mso-style-link:"Heading 2 Char";
	margin-top:4.0pt;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:0cm;
	margin-bottom:.0001pt;
	page-break-after:avoid;
	font-size:14.0pt;
	font-family:"Calibri",sans-serif;
	color:#E36C0A;
	font-weight:normal;}
a:link, span.MsoHyperlink
	{color:blue;
	text-decoration:underline;}
p.MsoListParagraph, li.MsoListParagraph, div.MsoListParagraph
	{margin-top:0cm;
	margin-right:0cm;
	margin-bottom:10.0pt;
	margin-left:36.0pt;
	line-height:120%;
	font-size:10.5pt;
	font-family:"Cambria",serif;}
p.MsoListParagraphCxSpFirst, li.MsoListParagraphCxSpFirst, div.MsoListParagraphCxSpFirst
	{margin-top:0cm;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:36.0pt;
	margin-bottom:.0001pt;
	line-height:120%;
	font-size:10.5pt;
	font-family:"Cambria",serif;}
p.MsoListParagraphCxSpMiddle, li.MsoListParagraphCxSpMiddle, div.MsoListParagraphCxSpMiddle
	{margin-top:0cm;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:36.0pt;
	margin-bottom:.0001pt;
	line-height:120%;
	font-size:10.5pt;
	font-family:"Cambria",serif;}
p.MsoListParagraphCxSpLast, li.MsoListParagraphCxSpLast, div.MsoListParagraphCxSpLast
	{margin-top:0cm;
	margin-right:0cm;
	margin-bottom:10.0pt;
	margin-left:36.0pt;
	line-height:120%;
	font-size:10.5pt;
	font-family:"Cambria",serif;}
span.Heading2Char
	{mso-style-name:"Heading 2 Char";
	mso-style-link:"Heading 2";
	font-family:"Calibri",sans-serif;
	color:#E36C0A;}
.MsoChpDefault
	{font-size:10.5pt;
	font-family:"Cambria",serif;}
.MsoPapDefault
	{margin-bottom:10.0pt;
	line-height:120%;}
@page WordSection1
	{size:595.3pt 841.9pt;
	margin:36.0pt 36.0pt 36.0pt 36.0pt;}
div.WordSection1
	{page:WordSection1;}
 /* List Definitions */
 ol
	{margin-bottom:0cm;}
ul
	{margin-bottom:0cm;}
-->
</style>

</head>

<body bgcolor=white lang=EN-US link=blue vlink=purple>

<div class=WordSection1>

<p class=MsoNormal align=center style='text-align:center'><u><span
style='font-size:16.0pt;line-height:120%'>Project: Predictive Analytics
Capstone</span></u></p>

<p class=MsoNormal align=center style='text-align:center'><span
style='font-size:11.0pt;line-height:120%'><a
href="https://coco.udacity.com/nanodegrees/nd008/locale/en-us/versions/1.0.0/parts/7271/project"></a></span></p>

<h2 style='margin-top:12.0pt;margin-right:0cm;margin-bottom:2.0pt;margin-left:
0cm;page-break-after:auto'>Task 1: Determine Store Formats for Existing Stores</h2>

<ol style='margin-top:0cm' start=1 type=1>
 <li class=MsoNormal style='line-height:normal'>What is the optimal number of
     store formats? How did you arrive at that number?</li>
</ol>

<p class=MsoNormal style='margin-left:36.0pt;line-height:normal'>The optimal
number of store formats is 3. This was arrived by using the K-Centroid
Diagnostics tool in Alteryx.  AR and CH value for each of the cluster is
compared, in which Median of cluster 3 is high. AR value 0.7313 and CH Value 31.0.</p>

<p class=MsoNormal style='margin-left:36.0pt;line-height:normal'>&nbsp;</p>

<p class=MsoNormal style='margin-left:36.0pt;line-height:normal'><img border=0
width=625 height=200 id="Picture 1"
src="Combining%20Predictive%20Tools_files/image001.gif"
alt="A screenshot of a video game&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal style='margin-left:36.0pt;line-height:normal'>&nbsp;</p>

<p class=MsoNormal style='margin-left:36.0pt;line-height:normal'><img border=0
width=519 height=519 id="Picture 2"
src="Combining%20Predictive%20Tools_files/image002.gif"
alt="A screenshot of a cell phone&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal style='margin-left:36.0pt;line-height:normal'>&nbsp;</p>

<ol style='margin-top:0cm' start=2 type=1>
 <li class=MsoNormal style='line-height:normal'>How many stores fall into each
     store format?</li>
</ol>

<p class=MsoNormal style='margin-left:36.0pt;line-height:normal'>Using K-Means,
cluster analysis is performed, and the distribution is as shown below. </p>

<p class=MsoNormal style='margin-left:36.0pt;line-height:normal'> <img
border=0 width=270 height=118 id="Picture 3"
src="Combining%20Predictive%20Tools_files/image003.gif"
alt="A screenshot of a social media post&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal style='margin-left:36.0pt;line-height:normal'>&nbsp;</p>

<ol style='margin-top:0cm' start=3 type=1>
 <li class=MsoNormal style='line-height:normal'>Based on the results of the
     clustering model, what is one way that the clusters differ from one
     another?</li>
</ol>

<p class=MsoListParagraph>Looking at the graph shown below, we can notice that
Stores in Cluster 1 sell more on an average when compared to the stores in the
other two clusters.</p>

<p class=MsoNormal style='margin-left:36.0pt;line-height:normal'>&nbsp;</p>

<p class=MsoNormal style='margin-left:36.0pt;line-height:normal'><img border=0
width=363 height=234 id="Picture 6"
src="Combining%20Predictive%20Tools_files/image004.gif"
alt="A close up of text on a white background&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal style='margin-left:36.0pt'>&nbsp;</p>

<ol style='margin-top:0cm' start=4 type=1>
 <li class=MsoNormal style='line-height:normal'>Please provide a Tableau
     visualization (saved as a Tableau Public file) that shows the location of
     the stores, uses color to show cluster, and size to show total sales.</li>
</ol>

<p class=MsoNormal style='line-height:normal'><img border=0 width=698
height=330 id="Picture 7"
src="Combining%20Predictive%20Tools_files/image005.gif"
alt="A close up of a map&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal style='line-height:normal'><a
href="https://public.tableau.com/profile/adel.altuwaijri#!/vizhome/Storesclustersmap/store-locations">https://public.tableau.com/profile/adel.altuwaijri#!/vizhome/Storesclustersmap/store-locations</a></p>

<h2 style='margin-top:12.0pt;margin-right:0cm;margin-bottom:2.0pt;margin-left:
0cm;page-break-after:auto'>Task 2: Formats for New Stores </h2>

<ol style='margin-top:0cm' start=1 type=1>
 <li class=MsoNormal><a name="_1fob9te"></a>What methodology did you use to
     predict the best store format for the new stores? Why did you choose that
     methodology? (Remember to Use a 20% validation sample with Random Seed = 3
     to test differences in models.)</li>
</ol>

<p class=MsoNormal>I used Decision tree, Forest, and boosted models to predict
the most fit cluster for each new store and then compared the accuracy of these
models using Model Comparison tool. According to resulted report, I found that
accuracy and F1 measures is best with boosted model.</p>

<p class=MsoNormal><img border=0 width=698 height=113 id="Picture 4"
src="Combining%20Predictive%20Tools_files/image006.gif"
alt="A screenshot of a cell phone&#10;&#10;Description automatically generated"> </p>

<ol style='margin-top:0cm' start=2 type=1>
 <li class=MsoNormal>What format do each of the 10 new stores fall into? Please
     fill in the table below.</li>
</ol>

<div align=center>

<table class=MsoTable15Plain4 border=0 cellspacing=0 cellpadding=0
 style='border-collapse:collapse'>
 <tr style='height:11.35pt'>
  <td valign=top style='background:#F2F2F2;padding:0cm 5.4pt 0cm 5.4pt;
  height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%'>Store Number</span></p>
  </td>
  <td valign=top style='background:#F2F2F2;padding:0cm 5.4pt 0cm 5.4pt;
  height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%;color:black'>Segment</span></p>
  </td>
 </tr>
 <tr style='height:11.35pt'>
  <td valign=top style='padding:0cm 5.4pt 0cm 5.4pt;height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%'>S0086</span></p>
  </td>
  <td valign=top style='padding:0cm 5.4pt 0cm 5.4pt;height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%'>3</span></p>
  </td>
 </tr>
 <tr style='height:11.35pt'>
  <td valign=top style='background:#F2F2F2;padding:0cm 5.4pt 0cm 5.4pt;
  height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%;color:black'>S0087</span></p>
  </td>
  <td valign=top style='background:#F2F2F2;padding:0cm 5.4pt 0cm 5.4pt;
  height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%;color:black'>2</span></p>
  </td>
 </tr>
 <tr style='height:11.35pt'>
  <td valign=top style='padding:0cm 5.4pt 0cm 5.4pt;height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%'>S0088</span></p>
  </td>
  <td valign=top style='padding:0cm 5.4pt 0cm 5.4pt;height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%'>1</span></p>
  </td>
 </tr>
 <tr style='height:17.0pt'>
  <td valign=top style='background:#F2F2F2;padding:0cm 5.4pt 0cm 5.4pt;
  height:17.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%;color:black'>S0089</span></p>
  </td>
  <td valign=top style='background:#F2F2F2;padding:0cm 5.4pt 0cm 5.4pt;
  height:17.0pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%;color:black'>2</span></p>
  </td>
 </tr>
 <tr style='height:11.35pt'>
  <td valign=top style='padding:0cm 5.4pt 0cm 5.4pt;height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%'>S0090</span></p>
  </td>
  <td valign=top style='padding:0cm 5.4pt 0cm 5.4pt;height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%'>2</span></p>
  </td>
 </tr>
 <tr style='height:11.35pt'>
  <td valign=top style='background:#F2F2F2;padding:0cm 5.4pt 0cm 5.4pt;
  height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%;color:black'>S0091</span></p>
  </td>
  <td valign=top style='background:#F2F2F2;padding:0cm 5.4pt 0cm 5.4pt;
  height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%;color:black'>1</span></p>
  </td>
 </tr>
 <tr style='height:11.35pt'>
  <td valign=top style='padding:0cm 5.4pt 0cm 5.4pt;height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%'>S0092</span></p>
  </td>
  <td valign=top style='padding:0cm 5.4pt 0cm 5.4pt;height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%'>2</span></p>
  </td>
 </tr>
 <tr style='height:11.35pt'>
  <td valign=top style='background:#F2F2F2;padding:0cm 5.4pt 0cm 5.4pt;
  height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%;color:black'>S0093</span></p>
  </td>
  <td valign=top style='background:#F2F2F2;padding:0cm 5.4pt 0cm 5.4pt;
  height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%;color:black'>1</span></p>
  </td>
 </tr>
 <tr style='height:11.35pt'>
  <td valign=top style='padding:0cm 5.4pt 0cm 5.4pt;height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%'>S0094</span></p>
  </td>
  <td valign=top style='padding:0cm 5.4pt 0cm 5.4pt;height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%'>2</span></p>
  </td>
 </tr>
 <tr style='height:11.35pt'>
  <td valign=top style='background:#F2F2F2;padding:0cm 5.4pt 0cm 5.4pt;
  height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%;color:black'>S0095</span></p>
  </td>
  <td valign=top style='background:#F2F2F2;padding:0cm 5.4pt 0cm 5.4pt;
  height:11.35pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  115%'><span style='font-size:10.0pt;line-height:115%;color:black'>2</span></p>
  </td>
 </tr>
</table>

</div>

<p class=MsoNormal style='margin-left:36.0pt'><span style='font-size:10.0pt;
line-height:120%'>&nbsp;</span></p>

<ol style='margin-top:0cm' start=3 type=1>
 <li class=MsoNormal><span style='font-family:"Helvetica",sans-serif;
     color:#4F4F4F;background:white'>What are the three most important
     variables that help explain the relationship between demographic
     indicators and store formats? Please include a visualization.</span></li>
</ol>

<p class=MsoNormal style='margin-left:36.0pt'><span style='font-family:"Helvetica",sans-serif;
color:#4F4F4F;background:white'>According to variable importance plot result from
boosted model tool, the three most important variables are: <b>Age0to9</b>, <b>HVAL750kPlus</b>,
and <b>EdHSGrad</b>.</span></p>

<p class=MsoNormal style='margin-left:36.0pt'><img border=0 width=463
height=338 id="Picture 5"
src="Combining%20Predictive%20Tools_files/image007.gif"
alt="A screenshot of a social media post&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal>&nbsp;</p>

<h2 style='margin-top:12.0pt;margin-right:0cm;margin-bottom:2.0pt;margin-left:
0cm;page-break-after:auto'>Task 3: Predicting Produce Sales</h2>

<p class=MsoNormal style='margin-left:36.0pt'>1. What type of ETS or ARIMA
model did you use for each forecast? Use ETS(a,m,n) or ARIMA(ar, i, ma)
notation. How did you come to that decision?</p>

<p class=MsoNormal style='margin-left:36.0pt'>I have prepared a forecast with
monthly granularity for product sales for 2016 for existing and new stores. To
forecast sales for existing stores, I aggregate sales in all stores per month
and produce a forecast. The time series is broken down into three time series,
which is the seasonal component, the trend component and the rest. Below, I
report the decomposition graph:</p>

<p class=MsoNormal style='margin-left:36.0pt'><img border=0 width=654
height=448 id="Picture 8"
src="Combining%20Predictive%20Tools_files/image008.gif"
alt="A close up of text on a white surface&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal style='margin-left:36.0pt'>I built the ETS model, examining
the seasonal component, trend component and rest component in the time series
decomposition graph. Seasonality is growing slightly over time (the peaks are
increasing very slowly), so i apply this multiplicatively, the series</p>

<p class=MsoNormal style='margin-left:36.0pt'>there is no trend, the error is
increasing or decreasing over time, so i apply the error multiplicatively, so i
choose the ETS (M, N, M).</p>

<p class=MsoNormal style='margin-left:36.0pt'>The ARIMA model requires that the
series be stationary. Autocorrelation (ACF) or partial autocorrelation (PACF)
charts help me determine whether autocorrelation exists:</p>

<p class=MsoNormal style='margin-left:36.0pt'>&nbsp;</p>

<p class=MsoNormal style='margin-left:36.0pt'><img border=0 width=646
height=178 id="Picture 10"
src="Combining%20Predictive%20Tools_files/image009.gif"
alt="A picture containing screenshot&#10;&#10;Description automatically generated"><img
border=0 width=654 height=174 id="Picture 11"
src="Combining%20Predictive%20Tools_files/image010.gif"></p>

<p class=MsoNormal style='margin-left:36.0pt'>&nbsp;</p>

<p class=MsoNormal style='margin-left:36.0pt'>I noted that the ACF shows an fluctuation,
indicating a seasonal series, in the &quot;lags&quot; i can observe several
seasonal periods. In the monthly data, i can observe that in the lags 12, 24,
the peaks occur at intervals of 12 months and 24 months, in addition , i
observed that a peak in delay 1 on an ACF graph indicates a strong correlation
between each value in the series and the previous value, and then i adjust the
series with the seasonal model ARIMA. Non-stationary series can be corrected by
a transformation such as applying the first seasonal difference. By observing
the ACF and PACF autocorrelation graphs of the first seasonal difference, i can
identify the numbers of ARIMA terms needed</p>

<p class=MsoNormal style='margin-left:36.0pt'>&nbsp;</p>

<p class=MsoNormal style='margin-left:36.0pt'><img border=0 width=662
height=149 id="Picture 12"
src="Combining%20Predictive%20Tools_files/image011.gif"
alt="A screenshot of a social media post&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal style='margin-left:36.0pt'>Observing the two negative peaks
in FAC in lag 1, which indicates non-seasonal BF terms. For seasonal terms, i
note that there is a negative peak at 12-month intervals. This indicates
seasonal MA terms. So, the model that fits is ARIMA (0, 1, 1) (0, 1, 1) 12.</p>

<p class=MsoNormal style='margin-left:36.0pt'>&nbsp;</p>

<p class=MsoNormal style='margin-left:36.0pt'><img border=0 width=469
height=119 id="Picture 13"
src="Combining%20Predictive%20Tools_files/image012.gif"
alt="A screenshot of a cell phone&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal style='margin-left:36.0pt'>&nbsp;</p>

<p class=MsoNormal style='margin-left:36.0pt'>From the values in the table, I concluded
that the ETS model is better than the ARIMA model for this problem, given that
the RMSE and MASE of the ETS model are inferior to the ARIMA model. For the ETS
model, RMSE is 1983593 and MASE 1.2691 and for the ARIMA model, RMSE is 2999244
and MASE is 1.6988, here is the graph that shows all the time series values and
forecast values for all the compared models.</p>

<p class=MsoNormal style='margin-left:36.0pt'>Looking at the graph below, its
obvious that ETS model behaves more accurately than the ARIMA model.</p>

<p class=MsoNormal style='margin-left:36.0pt'><img border=0 width=530
height=407 id="Picture 14"
src="Combining%20Predictive%20Tools_files/image013.gif"
alt="A close up of text on a black background&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal style='margin-left:36.0pt'>2. <span style='color:#4F4F4F'>Please
provide a table of your forecasts for existing and new stores. Also, provide visualization
of your forecasts that includes historical data, existing stores forecasts, and
new stores forecasts.</span></p>

<div align=center>

<table class=MsoTable15Grid1LightAccent6 border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none'>
 <tr style='height:8.5pt'>
  <td nowrap colspan=5 valign=top style='border:solid #FBD4B4 1.0pt;border-bottom:
  solid #FABF8F 1.5pt;background:#FDE9D9;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>Historical <span style='color:black'>Sales</span></span></b></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border:solid #FBD4B4 1.0pt;border-top:none;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>Year</span></b></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>Month</span></b></p>
  </td>
  <td nowrap colspan=3 valign=top style='border-top:none;border-left:none;
  border-bottom:solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal style='margin-bottom:0cm;margin-bottom:.0001pt;line-height:
  normal'><span style='font-size:9.0pt;font-family:"Calibri",sans-serif'>  <b>Sales</b></span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap rowspan=10 valign=top style='border:solid #FBD4B4 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>2012</span></b></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>03</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>25151526</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Times New Roman",serif'>&nbsp;</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>04</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>24406048</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Times New Roman",serif'>&nbsp;</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>05</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>28249539</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Times New Roman",serif'>&nbsp;</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>06</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>28691364</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Times New Roman",serif'>&nbsp;</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>07</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>28535707</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Times New Roman",serif'>&nbsp;</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>08</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>25793521</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Times New Roman",serif'>&nbsp;</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>09</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>21915642</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Times New Roman",serif'>&nbsp;</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>10</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>21203563</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>11</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>21736159</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>12</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>21962977</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap rowspan=12 valign=top style='border:solid #FBD4B4 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>2013</span></b></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>01</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>20322684</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>02</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>19829621</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>03</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>22717070</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>04</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>21625385</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>05</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>23000152</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>06</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>24755406</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>07</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>26803106</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>08</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>22600217</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>09</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>21401266</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>10</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>19296578</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>11</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>20489773</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>12</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>21715707</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap rowspan=12 valign=top style='border:solid #FBD4B4 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>2014</span></b></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>01</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>22544458</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>02</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>21262413</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>03</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>23247169</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>04</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>22541988</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>05</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>25943047</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>06</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>24782178</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>07</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>24263118</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>08</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>21879989</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>09</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>18407264</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>10</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>19497572</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>11</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>19444753</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>12</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>19240385</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap rowspan=12 valign=top style='border:solid #FBD4B4 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>2015</span></b></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>01</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>20088529</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>02</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>19772333</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>03</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>24608407</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>04</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>21559729</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>05</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>25792075</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>06</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>27212464</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>07</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>26338477</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>08</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>23130627</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>09</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>20774416</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>10</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>20359981</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>11</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>21936907</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>12</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>20462899</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap colspan=5 valign=top style='border:solid #FBD4B4 1.0pt;border-top:
  none;background:#FDE9D9;padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b><span style='font-size:9.0pt;
  font-family:"Times New Roman",serif;color:black'>Forecasting Sales</span></b></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border:solid #FBD4B4 1.0pt;border-top:none;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b><span style='font-size:9.0pt;
  font-family:"Times New Roman",serif'>Year</span></b></p>
  </td>
  <td valign=top style='border-top:none;border-left:none;border-bottom:solid #FBD4B4 1.0pt;
  border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b><span style='font-size:9.0pt;
  font-family:"Times New Roman",serif'>Month</span></b></p>
  </td>
  <td valign=top style='border-top:none;border-left:none;border-bottom:solid #FBD4B4 1.0pt;
  border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b><span style='font-size:9.0pt;
  font-family:"Times New Roman",serif'>&nbsp;</span></b></p>
  </td>
  <td valign=top style='border-top:none;border-left:none;border-bottom:solid #FBD4B4 1.0pt;
  border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b><span style='font-size:9.0pt;
  font-family:"Times New Roman",serif'>Existing Stores</span></b></p>
  </td>
  <td valign=top style='border-top:none;border-left:none;border-bottom:solid #FBD4B4 1.0pt;
  border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b><span style='font-size:9.0pt;
  font-family:"Times New Roman",serif'>New Stores</span></b></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap rowspan=12 valign=top style='border:solid #FBD4B4 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><b><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>2016</span></b></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>1</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>21829060</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>2588357</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>2</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>21146330</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>2498567</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>3</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>23735687</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>2919067</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>4</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>22409515</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>2797280</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>5</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>25621829</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>3163765</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>6</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>26307858</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>3202813</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>7</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>26705093</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>3228212</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>8</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>23440761</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>2868915</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>9</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>20640047</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>2538372</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>10</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>20086270</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>2485732</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>11</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>20858120</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>2583448</span></p>
  </td>
 </tr>
 <tr style='height:8.5pt'>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>12</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;background:#F2F2F2;
  padding:0cm 5.4pt 0cm 5.4pt;height:8.5pt'></td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>21255190</span></p>
  </td>
  <td nowrap valign=top style='border-top:none;border-left:none;border-bottom:
  solid #FBD4B4 1.0pt;border-right:solid #FBD4B4 1.0pt;padding:0cm 5.4pt 0cm 5.4pt;
  height:8.5pt'>
  <p class=MsoNormal align=center style='margin-bottom:0cm;margin-bottom:.0001pt;
  text-align:center;line-height:normal'><span style='font-size:9.0pt;
  font-family:"Calibri",sans-serif'>2562182</span></p>
  </td>
 </tr>
</table>

</div>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal><img border=0 width=698 height=352 id="Picture 15"
src="Combining%20Predictive%20Tools_files/image014.gif"
alt="A close up of a logo&#10;&#10;Description automatically generated"></p>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal><a
href="https://public.tableau.com/profile/adel.altuwaijri%23!/vizhome/ProduceSalesAnalysis/Sheet1?publish=yes">https://public.tableau.com/profile/adel.altuwaijri#!/vizhome/ProduceSalesAnalysis/Sheet1?publish=yes</a></p>

</div>

</body>

</html>
© 2020 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
