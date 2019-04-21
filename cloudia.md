---
title: Web Speech API Demo
permalink: cloudia.html
---

<link href="/css/cloudia.css" rel="stylesheet">
<script src="/js/cloudia.js"></script>

## Cloudia Test

<div>
  <p id="info_message"></p>
</div>

<div class="right">
  <button id="start_button" onclick="startButton(event)">
    <img id="start_img" src="images/mic.gif" alt="Start"></button>
</div>

<div id="results">
  <span id="final_span" class="final"></span>
  <span id="interim_span" class="interim"></span>
  <p>
</div>

<div class="center">
  <div style="text-align:right">
    <button id="copy_button" class="button" onclick="copyButton()">
      Copy and Paste</button>
    <div id="copy_info" class="info">
      Press Control-C to copy text.<br>(Command-C on Mac.)
    </div>
  </div>
  <div id="div_language">
    <select id="select_language" onchange="updateCountry()"></select>
    &nbsp;&nbsp;
    <select id="select_dialect"></select>
  </div>
</div>
