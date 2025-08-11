---
title: ""
aliases: /courses/
description: "Courses on statistics, microeconomics, and macroeconomics. For undergraduate students."
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
button.accordion {
  font:14px/1.5 Lato,"Helvetica Neue",Helvetica,Arial,sans-serif;
  cursor:pointer; padding:0; border:none; text-align:left; outline:none;
  font-size:100%; transition:0.3s; background-color:#f8f8f8;
}
button.accordion.active,button.accordion:hover{background-color:#f8f8f8;}
button.accordion:after{content:" [+] ";font-size:90%;color:#777;float:left;margin-left:1px;}
button.accordion.active:after{content:" [\2212] ";}
div.panel{padding:0 20px;margin-top:5px;display:none;background-color:white;font-size:100%;}
div.panel.show{display:block!important;}
.semester-item{margin-bottom:8px;}
.semester-label{font-weight:bold;color:#1976d2;}
</style>

<!-- ECON 1113 -->
<p style="margin:0"><a style="margin:0; font-size:100%; font-weight:bold">Principles of Macroeconomics (ECON 1113-201)</a> <br>
<i>University of Oklahoma - Norman | Summer 2023</i> <br>
<button class="accordion">Course Materials</button>
<div class="panel" style="background-color:#F1F1F1;color:#666;padding:10px;">
  <div class="semester-item">
    <span class="semester-label">Summer 2023:</span>
    <a href="/Syllabus_ECON_1113_Summer_2023.pdf">Syllabus</a> |
    <a href="/Eval_ECON_1113_Summer_2023.pdf">Course Evaluation</a>
  </div>
</div><br>

<!-- ECON 1123 -->
<p style="margin:0"><a style="margin:0; font-size:100%; font-weight:bold">Principles of Microeconomics (ECON 1123-851)</a> <br>
<i>University of Oklahoma - Norman | Fall 2023</i> <br>
<button class="accordion">Course Materials</button>
<div class="panel" style="background-color:#F1F1F1;color:#666;padding:10px;">
  <div class="semester-item">
    <span class="semester-label">Fall 2023:</span>
    <a href="/Syllabus_ECON_1123_Fall_2023.pdf">Syllabus</a> 
    <a href="/Eval_ECON_1123_Fall_2023.pdf">Course Evaluation</a>
  </div>
</div><br>

<!-- ECON 3113 -->
<p style="margin:0"><a style="margin:0; font-size:100%; font-weight:bold">Intermediate Microeconomic Theory (ECON 3113-300)</a> <br>
<i>University of Oklahoma - Norman | Summer 2024</i> <br>
<button class="accordion">Course Materials</button>
<div class="panel" style="background-color:#F1F1F1;color:#666;padding:10px;">
  <div class="semester-item">
    <span class="semester-label">Summer 2024:</span>
    <a href="/Syllabus_ECON_3113_Summer_2024.pdf">Syllabus</a> |
    <a href="/Eval_ECON_3113_Summer_2024.pdf">Course Evaluation</a>
  </div>
</div><br>

<!-- ECON 2843 -->
<p style="margin:0"><a style="margin:0; font-size:100%; font-weight:bold">Elements of Statistics (ECON 2843-851)</a> <br>
<i>University of Oklahoma - Norman | Fall 2024</i> <br>
<button class="accordion">Course Materials</button>
<div class="panel" style="background-color:#F1F1F1;color:#666;padding:10px;">
  <div class="semester-item">
    <span class="semester-label">Fall 2024:</span>
    <a href="Syllabus_ECON_2843_Fall_2024.pdf">Syllabus</a>
    <a href="/Eval_ECON_2843_Fall_2024.pdf">Course Evaluation</a>
  </div>
</div><br>

<script>
var acc=document.getElementsByClassName("accordion");
for (var i=0;i<acc.length;i++){
  acc[i].onclick=function(){
    this.classList.toggle("active");
    this.parentNode.nextElementSibling.classList.toggle("show");
  }
}
</script>
