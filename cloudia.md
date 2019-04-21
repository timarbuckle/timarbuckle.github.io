---
title: Web Speech API Demo
permalink: cloudia.html
---

<link href="/css/cloudia.css" rel="stylesheet">

## Cloudia Test

<div>
  <p id="info_message"></p>
</div>

<div class="right">
  <button id="start_button" onclick="startButton(event)">
    <img id="start_img" src="/images/mic.gif" alt="Start"></button>
</div>

<div id="results">
  <span id="final_span" class="final"></span>
  <span id="interim_span" class="interim"></span>
</div>

<div class="center">
  <div id="div_language">
    <select id="select_language" onchange="updateCountry()"></select>
    &nbsp;&nbsp;
    <select id="select_dialect"></select>
  </div>
</div>

<div style="text-align:right">
    <button id="hari_button" class="button" onclick="sendHari()">Send to HARI</button>
</div>

<p></p>

<div id="response">
  <span id="hari_response_span" class="final"></span>
</div>

<p></p>

<div style="text-align:right">
    <button id="cloudia_button" class="button" onclick="sendCloudia()">Send to Cloudia</button>
</div>
<script src="/js/cloudia.js"></script>
