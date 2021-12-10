# 子div有体积，父div没有体积

[div has no height](https://stackoverflow.com/questions/19354845/div-has-no-height-even-if-it-has-content/19354969)

## float后要使用clear：both;
float doesn't take its parent height

[float-clear](https://www.w3schools.com/css/css_float_clear.asp)

.clearfix::after {
  content: "";
  clear: both;
  display: table;
}


## display : how
## visibility : whether or not
## overflow : how
## float-clear 
