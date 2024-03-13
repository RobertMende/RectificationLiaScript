<!--
author:   Your Name

email:    your@mail.org

version:  0.0.1

language: en

narrator: US English Female

comment:  Try to write a short comment about
          your course, multiline is also okay.

link:     https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css

script:   https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js
          ./index.js

-->

# Course Main Title

## This is a rectification

<html>
<head>
        <title>Rectification Simulation Example</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">      
</head>
<body>
<div class="container" style="background-color: rgba(173, 216, 230, 0.1);">
    <!--contains everything-->
<div class="row">
<div class="col-lg-9">
<div class="d-flex  p-2 m-2 border flex-column" id="chartDiv" style="width: 50vw; height: 60vh">
    <!-- contains the chart-->
</div>
</div>
<div class="col-lg-3 p-2">
<div class="d-flex justify-content-center align-items-center border flex-column rounded" style="background-color: rgba(240, 128, 128, 0.35); height: 100%">
    <!-- contains the form-->
                    <h5 class="h5 text-center">Inputs: </h5>
                    <div class="d-flex flex-column align-items-center">
                    <form id="frm" class="form">
                        <label for="divisionFactor">Trennfaktor </label><br>
                        <input type="range" min="1.1" max="10" step="0.1" id="divisionFactor" name="divisionFactor" value="0" valuename="divisionFactor" ip="num"><br>
                        <label for="xFeed">xFeed </label><br>
                        <input type="range" min="0.01" max="0.99" step="0.01" id="xFeed" name="xFeed" value="0" valuename="xFeed" ip="num"><br>
                        <label for="xProduct">xProdukt </label><br>
                        <input type="range" min="0.01" max="0.99" step="0.01" id="xProduct" name="xProduct" value="0" valuename="xProduct" ip="num"><br>
                        <label for="xWaste">xSumpf: </label><br>
                        <input type="range" min="0.01" max="0.99" step="0.01" id="xWaste" name="xWaste" value="0" valuename="xWaste" ip="num"><br>
                        <label for="v">v: </label><br>
                        <input type="range" min="0" max="10" step="0.1" id="v" name="v" value="0" valuename="v" ip="num"><br>
                        <label for="q">q: </label><br>
                        <input type="range" min="0.1" max="10" step="0.1" id="q" name="q" value="0" valuename="q" ip="num"><br><br>
                        <input type="submit" class="btn bg-white mt-2" value="Submit">
                    </form> 
                </div>
</div>
</div>
</div>
</div>
</body>
</html>

## RNG

This is a random number: <script>Math.random()</script>

## html

<script>"HTML: <div style='border: 2px solid red'>Hello world</div>"</script>
