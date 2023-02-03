---
weight: 3
title: Test
authors: Lenny Lin
categories: 
tags: []
description: 
draft: false
date: "2023-02-02"
lastmod: "2023-02-02"
series: null
toc: true
---

<meta name="viewport" content="width=device-width, initial-scale=1">

# Hydro Quebec Lab

<button type = "button" class = "collapsible"> Hydro Quebec Lab</button>
<div class = "content">
<p>The Hydro Lab is an open innovation laboratory where inventive ideas take root. It is a co-creative space designed to accelerate the company’s innovative projects and to find new ways of meeting the expectations of the public and of Hydro‑Québec employees.</p>
</div>

<style>
.collapsible {
  background-color: #777;
  color: white;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
}

.active, .collapsible:hover {
  background-color: #555;
}

.collapsible:after {
  content: '\002B';
  color: white;
  font-weight: bold;
  float: right;
  margin-left: 5px;
}

.active:after {
  content: "\2212";
}

.content {
  padding: 0 18px;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
  background-color: #f1f1f1;
}
</style>



<script>
// for collapsible text
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.display === "block") {
      content.style.display = "none";
    } else {
      content.style.display = "block";
    }
  });
}
</script>