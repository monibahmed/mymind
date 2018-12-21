+++
title = "Linear Regression"
author = ["Monib Ahmed"]
draft = false
toc = true
type = "docs"
linktitle = "Section 1"
[menu.mlai]
  weight = 1001
  identifier = "linear-regression"
+++

## 1-Dimension {#1-dimension}

We'll start with a basic example of linear regression. Suppose you
did an experiment where the car starts at a distance 0 and travels
some known time. You want to find the speed of the car. What would
you do? You would measure the distance travelled and divide it by
the measured time and get an accurate speed:

\\[ v = d/t \\]
\\[ d = vt  \\]

Now suppose you had some measurement errors. This could cause the
speed to be inaccurate. By taking more measurements, you can get
closer to the actual speed of the car.

< Get plot of \\(y=mx\\) showing some variance in measured \\(y\\) >

Linear regression is a method that can help approach a close
approximation of the speed. Linear Regression