<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Apache Hadoop and MapReduce FastPack</title>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
<meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
<meta content="Scroll Wiki Publisher" name="generator"/>
<link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
<link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
<!--[if lt IE 8]><link rel="stylesheet" href="css/blueprint/ie.css" type="text/css" media="screen, projection"/><![endif]-->
<link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
<link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
<link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
<div class="container" style="min-width: 760px;">
<div class="header block">
<div class="header-left column span-6">
</div>
<div class="column span-18 header-right last">
<h4>Apache Hadoop and MapReduce FastPack</h4>
</div>
</div>
<div class="block">
<div class="toc column span-6 prepend-top">
<h3>Table of Contents
</h3>
<ul class="toc">
</ul>
</div>
<div id="74383484" class="content column span-18 last">
<h1>Apache Hadoop and MapReduce FastPack</h1>
<p>
<img src="images_community/download/attachments/25789254/mapreduce-logo_small.png" alt="images_community/download/attachments/25789254/mapreduce-logo_small.png" class="confluence-embedded-image image-left" />
Compuware APM dynaTrace 5.5 has <a href="https://community/display/DOCDT55/Hadoop+MapReduce">built-in support for Hadoop MapReduce</a>. This FastPack provides additional dashboards and a Job Monitor for further monitoring and analysis. </p>
<div class="section-2" id="74383484_ApacheHadoopandMapReduceFastPack-FastPackDetails" >
<h2>Fast Pack Details</h2>
<div class="tablewrap">
<table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" "> <tr>
<td rowspan="1" colspan="1">
<p>
Name </p>
</td>
<td rowspan="1" colspan="1">
<p>
<strong class=" ">Apache Hadoop FastPack</strong> </p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>
Version </p>
</td>
<td rowspan="1" colspan="1">
<p>
5.5.0.5225, 5.6.0.5802 </p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>
dynaTrace Version </p>
</td>
<td rowspan="1" colspan="1">
<p>
5.5, 5.6 </p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>
Author </p>
</td>
<td rowspan="1" colspan="1">
<p>
Michael Kopp </p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>
License </p>
</td>
<td rowspan="1" colspan="1">
<p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a> </p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>
Support </p>
</td>
<td rowspan="1" colspan="1">
<p>
<a href="https://community/display/DL/Support+Levels#SupportLevels-Community">Not Supported </a> </p>
</td>
</tr>
<tr>
<td rowspan="1" colspan="1">
<p>
FastPack Contents dynaTrace 5.5 </p>
</td>
<td rowspan="1" colspan="1">
<p>
<a href="attachments_122978600_1_ApacheHadoopFastpack_5.5.dtp">Fastpack Download for dynaTrace 5.5</a> contains: </p>
<ul class=" "><li class=" "> <p>
MapReduce Jobs Dashboard </p>
</li><li class=" "> <p>
Hadoop HDFS Statistics Dashboard </p>
</li><li class=" "> <p>
Hadoop Cluster Overview Dashboard </p>
</li><li class=" "> <p>
Two Hadoop Metric Groups for the Data and Name Nodes </p>
</li><li class=" "> <p>
Job Monitor that works for all major Hadoop Versions </p>
</li><li class=" "> <p>
Sensor and Profile are built-in with dynaTrace 5.5 </p>
</li></ul> <p>
<a href="attachments_167215201_1_ApacheHadoopFastpack_5.6.0.5802.dtp">Fastpack Download for dynaTrace 5.6</a> additionally contains support for: </p>
<ul class=" "><li class=" "> <p>
Amazon EMR 1.0.3 </p>
</li><li class=" "> <p>
Cloudera 4.6.0 (MR1) </p>
</li><li class=" "> <p>
Cloudera 4.3.0 (MR1 + MR2) </p>
</li><li class=" "> <p>
Cloudera 4.0.0 (MR1) </p>
</li></ul> </td>
</tr>
</tbody> </table>
</div>
<p>
If you have any questions, please don't hesitate to ask in our <a href="https://community/display/DTFORUM/Community+Plugins+and+Extensions">Plugins and Extension Forum</a>. </p>
</div>
<div class="section-2" id="74383484_ApacheHadoopandMapReduceFastPack-HadoopMapReduceJobs" >
<h2>Hadoop MapReduce Jobs</h2>
<p>
<img src="images_community/download/attachments/74383484/dashboard.png" alt="images_community/download/attachments/74383484/dashboard.png" class="" />
</p>
<p>
The MapReduce Dashboard gives an overview of the currently running Jobs and how much the Hadoop Environment is utilized. In addition it shows the specific running and completed jobs (lower pane). This dashboard relies on the Job Monitor. </p>
</div>
<div class="section-2" id="74383484_ApacheHadoopandMapReduceFastPack-HDFS%28NameNode%29Statistics" >
<h2>HDFS (NameNode) Statistics</h2>
<p>
<img src="images_community/download/attachments/74383484/dashboard1.png" alt="images_community/download/attachments/74383484/dashboard1.png" class="" />
</p>
<p>
The HDFS (NameNode) Statistics Dashboard gives an overview over the most important HDFS Nodes. It shows the summary as seen by the name node. In addition the user can put the metrics for specific data nodes on separate dashboards if that is desired.<br/> <img src="images_community/download/attachments/74383484/Measures.png" alt="images_community/download/attachments/74383484/Measures.png" class="" />
</p>
</div>
<div class="section-2" id="74383484_ApacheHadoopandMapReduceFastPack-HadoopClusterOverview" >
<h2>Hadoop Cluster Overview</h2>
<p>
<img src="images_community/download/attachments/74383484/dashboard4.png" alt="images_community/download/attachments/74383484/dashboard4.png" class="" />
</p>
<p>
The Hadoop Cluster Overview shows a consolidated view of the cluster resource usage over time. It gives a sense of how much CPU is consumed and the load average of the whole cluster. It does the same for Disk and Network I/I as well as memory. It serves the same purpose as Ganglia dashboards do. </p>
</div>
<div class="section-2" id="74383484_ApacheHadoopandMapReduceFastPack-FastPackInformation" >
<h2>FastPack Information</h2>
<p>
dynaTrace 5.5. has <a href="https://community/display/DOCDT55/Hadoop+MapReduce">Hadoop MapReduce support</a> built in. This fastpack contains three additional Dashboards, a Job Monitor and two Metric Groups for the Name Node and Data Node respectively. dynaTrace can monitor any JMX attribute available withing the Hadoop nodes in addition to those supplied in this fastpack. </p>
</div>
<div class="section-2" id="74383484_ApacheHadoopandMapReduceFastPack-Installation" >
<h2>Installation</h2>
<p>
You should first inject Agents into your Hadoop environment and create a new system profile. See <a href="https://community.compuwareapm.com/community/display/DOCDT55/Hadoop+MapReduce">the documentation</a> on how to do this. </p>
<p>
Next just download and import the FastPack on your dynaTrace Server (see <a href="https://community.compuwareapm.com/community/display/DOCDT55/Plugin+Management">Plugin Management</a>). </p>
<p>
As a last step setup the Job Monitor, give it the name &quot;Apache Hadoop Job Monitor&quot; to make all dashboards work out of the box. </p>
</div>
</div>
</div>
<div class="footer">
</div>
</div>
</body>
</html>
