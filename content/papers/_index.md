---
title: ""
aliases: /papers/
description: "Research Papers"
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
button.accordion {
font:14px/1.5 Lato, "Helvetica Neue", Helvetica, Arial, sans-serif;
cursor: pointer;
padding: 0px;
border: none;
text-align: left;
outline: none;
font-size: 100%;
transition: 0.3s;
background-color: #f8f8f8;
}
button.accordion.active, button.accordion:hover {
background-color: #f8f8f8;
}
button.accordion:after {
content: " [+] ";
font-size: 90%;
color:#777;
float: left;
margin-left: 1px;
}
button.accordion.active:after {
content: " [\2212] ";
}
div.panel {
padding: 0 20px;
margin-top: 5px;
display: none;
background-color: white;
font-size: 100%;
}
div.panel.show {
display: block !important;
}
</style>

<h2><i class="fas fa-file-alt" style="color: #1976d2; margin-right: 8px;"></i>Working Papers</h2>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">Market Dispatch and Emissions in U.S. Electricity Markets: Spatial Reallocation and Operational Efficiency</a> <br> with Chris Malloy and Qihong Liu <br> (Job Market Paper) <br>
<button class="accordion">Abstract</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>This paper studies how the adoption of market dispatch across all U.S. electricity markets reshapes generation patterns and emissions by improving operational efficiency and reallocating generation across regions.</p>
</div>
<p style="margin:0"><button class="accordion">Download</button></p>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>Coming soon</p>
</div>
<br>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">Weather–Energy Events and Market Dispatch: Emissions and Market Outcomes under Symmetric and Asymmetric Shocks</a> <br> with Chris Malloy and Qihong Liu <br>
<button class="accordion">Abstract</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>This paper analyzes how emissions and market outcomes depend jointly on weather and load conditions under both symmetric and asymmetric shocks, with particular attention to SPP–MISO and ERCOT.</p>
</div>
<p style="margin:0"><button class="accordion">Download</button></p>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>Coming soon</p>
</div>
<br>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">How Does In-State Renewable Electricity Capacity Affect CO<sub>2</sub> Emissions? The Role of Renewable Portfolio Standards</a> <br> Solo-authored <br>
<button class="accordion">Abstract</button>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>This paper investigates how the design features of Renewable Portfolio Standards—particularly stringency and out-of-state Renewable Energy Credit (REC) trading—shape the relationship between renewable capacity and state-level CO<sub>2</sub> emissions.</p>
</div>
<p style="margin:0"><button class="accordion">Download</button></p>
<div class="panel" style="background-color: #F1F1F1; color: #666; padding: 10px;">
<p>Coming soon</p>
</div>
<br>

<script> 
var acc = document.getElementsByClassName("accordion");
var i;
for (i = 0; i < acc.length; i++) {
    acc[i].onclick = function(){
        this.classList.toggle("active");
        this.nextElementSibling.classList.toggle("show");
  }
}
</script>
