---
layout: default
title: Linear Interpolation Calculator
stylesheets:
  - href: "linearinterpolation/css/linearinterpolation.css"
javascript: 
  - src: "linearinterpolation/js/linearinterpolation.js"
---

<div id="linear-interp" class="tool">
    <div style="display: flex; flex-direction: row;">
      <div style="display: flex; flex-direction: column;">
        <span>
          <label for="x1-input">X1</label>
          <input id="x1-input" type="float">
        </span>
        <span>
          <label for="x2-input">X2</label>
          <input id="x2-input" type="float">
        </span>
        <span>
          <label for="x3-input">X3</label>
          <input id="x3-input" type="float">
        </span>
      </div>
      <div style="display: flex; flex-direction: column;">
        <span>
          <label for="y1-input">Y1</label>
          <input id="y1-input" type="float">
        </span>
        <span>
          <label for="interp-result">Y2</label>
          <b id="interp-result"></b>
        </span>
        <span>
          <label for="y3-input">Y3</label>
          <input id="y3-input" type="float">
        </span>
      </div>
    </div>
    <button id="linear-interp-result" style="width: 90%; margin: 10px">Get Results
    </button>
  </div>