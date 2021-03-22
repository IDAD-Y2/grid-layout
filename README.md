
# Grid layout

See the three example pages to figure out how this works:

* example-content-columns.html
* example-layout-columns.html
* example-push-columns.html

## Instructions

Before starting with anything please make sure to include this snippet of code in your <head> tag so that the grids will be responsive on mobile devices: <meta name="viewport" content="width=device-width, initial-scale=1" >

Starting out, you need to wrap your grid in a div class named grid. If you want a 20px padding around your grid, add the class grid-pad to the div wrapper. Next, all you have to do is decide what size you want your grid to be and add the appropiate classes. For example, if you want a grid with a left sidebar and main content area you would do:

<div class="grid">
  <div class="col-3-12">
  </div>
  <div class="col-9-12">
  </div>
</div>

If you have a page and would like four columns of content, you would do:

<div class="grid">
  <div class="col-1-4">
  </div>
  <div class="col-1-4">
  </div>
  <div class="col-1-4">
  </div>
  <div class="col-1-4">
  </div>
</div>

The first column of content in your grid will always be floated left. If you would like to float a column to the right, all you have to do is add the class push-right.

## Push-Classes

To push a column to the right, you can use the push-X-X classes:

<div class="grid">
  <div class="col-1-3 push-1-3">
  </div>
  <div class="col-1-3 ">
  </div>
</div>

## Mobile

If you don't want to stack all columns on mobile and tablet you can simply add a extra class to each column:

<div class="grid">
  <div class="col-1-3 mobile-col-1-2">
  </div>
  <div class="col-1-3 mobile-col-1-2">
  </div>
  <div class="col-1-3 hide-on-mobile">
  </div>
</div>

To hide a element (column, div, a, etc.) on mobile and tablets you can add the class hide-on-mobile to it.


This repository is reworked from https://github.com/ThisIsDallas/Simple-Grid
