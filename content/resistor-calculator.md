---
Title: Resistor Calculator
Date: 2019-06-24
Template: calc
---

<h3 class="step-header">Resistor Calculator</h3>
<p> Resistor sorting made easy! Enter a value to find the color bands, or enter your color bands to find the resistor’s value.
Type in the value of the resistor you need and this tool will show you the corresponding color code.</p>

<div id="resistor-tool-wrapper">
  <div>
    <form id="r-value">
      <label for="value"><strong>ENTER A VALUE:</strong></label>
      <input
        style="height: 28px;"
        name="r-value"
        placeholder=""
        required=""
        type="text"
        maxlength="5"
      />
    </form>
  </div>
  <div class="resistor-dropdown-wrapper">
    <div id="dd1" class="resistor-dropdown">
      <span>Color</span>
      <ul class="dropdown">
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="brown">Brown</a>
        </li>
        <li><a href="https://maps.diy.re/res-calc/#" class="red">Red</a></li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="orange">Orange</a>
        </li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="yellow">Yellow</a>
        </li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="green">Green</a>
        </li>
        <li><a href="https://maps.diy.re/res-calc/#" class="blue">Blue</a></li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="purple">Purple</a>
        </li>
        <li><a href="https://maps.diy.re/res-calc/#" class="gray">Gray</a></li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="white">White</a>
        </li>
      </ul>
    </div>
    <div id="dd2" class="resistor-dropdown">
      <span>Color</span>
      <ul class="dropdown">
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="black">Black</a>
        </li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="brown">Brown</a>
        </li>
        <li><a href="https://maps.diy.re/res-calc/#" class="red">Red</a></li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="orange">Orange</a>
        </li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="yellow">Yellow</a>
        </li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="green">Green</a>
        </li>
        <li><a href="https://maps.diy.re/res-calc/#" class="blue">Blue</a></li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="purple">Purple</a>
        </li>
        <li><a href="https://maps.diy.re/res-calc/#" class="gray">Gray</a></li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="white">White</a>
        </li>
      </ul>
    </div>
    <div id="dd3" class="resistor-dropdown">
      <span>Color</span>
      <ul class="dropdown">
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="black">Black</a>
        </li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="brown">Brown</a>
        </li>
        <li><a href="https://maps.diy.re/res-calc/#" class="red">Red</a></li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="orange">Orange</a>
        </li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="yellow">Yellow</a>
        </li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="green">Green</a>
        </li>
        <li><a href="https://maps.diy.re/res-calc/#" class="blue">Blue</a></li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="purple">Purple</a>
        </li>
        <li><a href="https://maps.diy.re/res-calc/#" class="gray">Gray</a></li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="white">White</a>
        </li>
      </ul>
    </div>
    <div id="dd4" class="resistor-dropdown">
      <span>Color</span>
      <ul class="dropdown">
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="black">Black</a>
        </li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="brown">Brown</a>
        </li>
        <li><a href="https://maps.diy.re/res-calc/#" class="red">Red</a></li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="orange">Orange</a>
        </li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="yellow">Yellow</a>
        </li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="green">Green</a>
        </li>
        <li><a href="https://maps.diy.re/res-calc/#" class="blue">Blue</a></li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="purple">Purple</a>
        </li>
        <li><a href="https://maps.diy.re/res-calc/#" class="gold">Gold</a></li>
        <li>
          <a href="https://maps.diy.re/res-calc/#" class="silver">Silver</a>
        </li>
      </ul>
    </div>
    <div id="dummy" class="brown resistor-dummy">
      <span>N/A</span>
      <ul class="dropdown"></ul>
    </div>
  </div>
  <div id="resistor-svg-wrapper">
    <!--?xml version="1.0" encoding="utf-8"?-->
    <!-- Generator: Adobe Illustrator 21.1.0, SVG Export Plug-In . SVG Version: 6.00 Build 0)  -->
    
  </div>
</div>
<script>mainResSort()</script>
