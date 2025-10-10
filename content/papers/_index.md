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

<!-- ======================== -->
<!--   JOB MARKET PAPER       -->
<!-- ======================== -->

<h2><i class="fas fa-briefcase" style="color: #841617; margin-right: 8px;"></i>Job Market Paper</h2>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">Market Dispatch and Emissions in U.S. Electricity Markets: Spatial Reallocation and Operational Efficiency</a>   
<br>
<button class="accordion">Abstract</button>
<div class="panel" style="background-color: #F1F1F1; color: #555; padding: 10px;">
<p>
This study evaluates the impact of market-based electricity dispatch on social welfare during the U.S. deregulation period from 1999 to 2012. By comparing the observed market dispatch against counterfactual least-cost and least-emissions regimes, we find that while markets yielded modest reductions in CO₂ and NOₓ damages via efficiency gains, they also triggered a sharp increase in SO₂ damages. This increase was driven by expanded trade and a shift toward cheaper coal generation. The net effect was an annual increase in environmental damages of $2–11 billion—a figure that far surpasses the documented $3–5 billion in private cost savings. These losses were concentrated in early-adopting, coal-reliant regions with a high proportion of merchant generators. Our results demonstrate that while deregulated markets improved private efficiency, they created even larger social costs by amplifying environmental externalities, highlighting an urgent need to align wholesale market rules with environmental goals.
</p>
</div>

<p style="margin:0"><button class="accordion">Download</button></p>
<div class="panel" style="background-color: #F1F1F1; color: #555; padding: 10px;">
<p>Coming soon</p>
</div>

<br>

<!-- ======================== -->
<!--   WORKING PAPERS         -->
<!-- ======================== -->

<h2><i class="fas fa-file-alt" style="color: #1976d2; margin-right: 8px;"></i>Working Papers</h2>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">Weather–Energy Events and Market Dispatch: Emissions and Market Outcomes under Symmetric and Asymmetric Shocks</a>  
<br> with Chris Malloy 
<br>
<button class="accordion">Abstract</button>
<div class="panel" style="background-color: #F1F1F1; color: #555; padding: 10px;">
<p>
We propose a new empirical design to estimate when electricity transmission provides the greatest value, exploiting variation in extreme net-load events. As power systems integrate more renewables, the grid faces increasing stress from days with severe imbalances between demand and renewable supply. We hypothesize that the private cost-saving value of transmission is highly heterogeneous and is disproportionately driven by its ability to insure against asymmetric regional shocks—where one region has a deficit while another has a surplus—compared to symmetric ones. Using day-ahead market data from MISO and SPP, we calculate the daily value of transmission against a counterfactual autarky equilibrium. A key innovation is our use of exogenous day-ahead forecasts of load and renewables to define extreme events, ensuring identification is free of post-treatment bias. We then estimate a causal model relating these event types to transmission value. Our findings will quantify the extent to which transmission acts as regional insurance, providing crucial guidance for infrastructure policy and the efficient integration of renewables.
</p>
</div>

<p style="margin:0"><button class="accordion">Download</button></p>
<div class="panel" style="background-color: #F1F1F1; color: #555; padding: 10px;">
<p>Coming soon</p>
</div>

<br>

<p style="margin:0"> 
<a style="margin:0; font-size:100%; font-weight:bold">How Does In-State Renewable Electricity Capacity Affect CO<sub>2</sub> Emissions? The Role of Renewable Portfolio Standards</a>  
<br> Sara Asgari  
<br>
<button class="accordion">Abstract</button>
<div class="panel" style="background-color: #F1F1F1; color: #555; padding: 10px;">
<p>
State-level policies, particularly Renewable Portfolio Standards (RPS), have been a primary driver of renewable energy adoption in the United States. While crucial for decarbonization, the expansion of renewable infrastructure carries its own ecological footprint, raising questions about its net environmental benefits. This study investigates how heterogeneous RPS design features—specifically, the allowance of out-of-state Renewable Energy Credit (REC) trading and policy stringency—shape these outcomes. We find that states prioritizing in-state renewable capacity development successfully spur local infrastructure growth. However, this same focus impedes their ability to control emissions and reduce their carbon footprint effectively. These results illuminate a critical tension in clean energy policy, demonstrating that the design of an RPS creates a trade-off between fostering a local green industry and achieving cost-effective emissions reductions.
</p>
</div>

<p style="margin:0"><button class="accordion">Download</button></p>
<div class="panel" style="background-color: #F1F1F1; color: #555; padding: 10px;">
<p>Coming soon</p>
</div>

<br>

<script>
document.addEventListener("DOMContentLoaded", function() {
  var acc = document.getElementsByClassName("accordion");
  for (var i = 0; i < acc.length; i++) {
    acc[i].addEventListener("click", function() {
      this.classList.toggle("active");
      this.nextElementSibling.classList.toggle("show");
    });
  }
});
</script>

