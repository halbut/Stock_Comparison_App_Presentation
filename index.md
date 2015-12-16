---
title       : Stock Comparison App
subtitle    : Presentation
author      : Alper Halbutogullari
job         : Data Scientist
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
github      :
   user: halbut
   repo: Stock_Comparison_App_Presentation
--- .class #id

## Interactive Stock App with Shiny Controls
<BR>  

# Why another App?
   <BR>   <BR>

> 1. Vanilla stock graphs usually present one stock at a time
   <BR>   <BR>
   
> 2. But for investment you usually need to compare two stocks
   <BR>   <BR>
   
> 3. This App plots two stocks at the same time over a given period so that you can make a good comparison.
   <BR>   <BR>
   
> 4. Bonus: You also have the option to view the quotes one stock at a time.

---

## Original Stock App


<div class="row-fluid">
  <div class="container-fluid">
    <div class="row">
      <div class="col-sm-4">
        <img src="assets/img/Stock_Comparison_App_screenshot_single_stock_original_small.png" align="right"/>
      </div>
      <div class="col-sm-2">
        <span class="help-block">Select a stock to examine. 
        Information will be collected from yahoo finance.</span>
        <br/>
        <br/>
        <div class="form-group shiny-input-container">
          <label for="symb">Symbol</label>
          <input id="symb" type="text" class="form-control" value="SPY"/>
        </div>
        <br/>
        <br/>
        <span class="help-block">Date range: </span>
        <br/>
        <br/>
        <div class="form-group shiny-input-container">
          <label for="start">start</label>
          <input id="start" type="text" class="form-control" value="2015-05-30"/>
        </div>
        <br/>
        <div class="form-group shiny-input-container">
          <label for="end">end</label>
          <input id="end" type="text" class="form-control" value="2015-12-13"/>
        </div>
        <br/>
        <br/>
        <button id="get" type="button" class="btn btn-default action-button">Get Stock</button>
        <br/>
        <br/>
      </div>
    </div>
  </div>
</div>

---

## Interactive Stock Comparison App

# Single stock view
<BR>

![Stock Comparison App screenshot](assets/img/Stock_Comparison_App_screenshot_single_stock.png)

---

## Interactive Stock Comparison App

# Double stock view
<BR>

![Stock Comparison App screenshot](assets/img/Stock_Comparison_App_screenshot_double_stock.png)


