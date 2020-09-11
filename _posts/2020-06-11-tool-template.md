---
layout: post
title:  "Tool Walkthrough Template"
author: storm
categories: [ R, tool, Template]
tags: [Intermediate]
image: assets/images/r.jpg
rating: 3
---

<!-- Quick Description:  -->
Maecenas volutpat blandit aliquam etiam erat. Imperdiet dui accumsan sit amet nulla facilisi morbi.

#### What is this Tool?
> Eu scelerisque felis imperdiet proin fermentum leo vel orci porta. Sit amet porttitor eget dolor. Egestas dui id ornare arcu odio. Fusce ut placerat orci nulla. Fermentum iaculis eu non diam phasellus vestibulum lorem sed. Tempus iaculis urna id volutpat lacus laoreet non. Phasellus faucibus scelerisque eleifend donec pretium vulputate sapien. Nunc congue nisi vitae suscipit tellus mauris a.

#### Why Use This Tool [Use Cases/Workflow Integration]?

Examples of Use Cases:
* Non curabitur gravida arcu ac tortor. Ut enim blandit volutpat maecenas volutpat blandit aliquam. Nam aliquam sem et tortor consequat id. Turpis massa tincidunt dui ut ornare.

Potential Integeration Possibilities:
* Magna ac placerat vestibulum lectus mauris ultrices eros. Ut sem nulla pharetra diam sit amet nisl. Ipsum a arcu cursus vitae. 

#### Limitations of Tool

Eros donec ac odio tempor orci dapibus ultrices in iaculis. Viverra nibh cras pulvinar mattis nunc sed blandit libero volutpat. Turpis egestas sed tempus urna. Sed enim ut sem viverra aliquet eget sit amet.

Egestas fringilla phasellus faucibus scelerisque eleifend donec pretium vulputate sapien. Egestas pretium aenean pharetra magna ac placerat vestibulum. Amet consectetur adipiscing elit ut aliquam purus sit amet luctus. 

#### Requirements to Run This Tool
Mauris in aliquam sem fringilla ut morbi. Phasellus egestas tellus rutrum tellus. Tincidunt vitae semper quis lectus. 
* Semper risus in hendrerit gravida rutrum quisque non tellus. 
* Elementum tempus egestas sed sed risus pretium quam. 
* Senectus et netus et malesuada. 
* Nulla aliquet enim tortor at auctor urna nunc.

-----
-----
-----

# Tool Walkthrough 

<br />

##### Step 1: Set up

```R
print("Hello World")
```
Lectus quam id leo in vitae turpis massa. Urna nunc id cursus metus aliquam eleifend mi in. 

##### Step 2: Import Datasets

```R
# Let's create some example data for the problem.
e1 <- runif(15)                         # Prices on exchange 1
e2 <- e1 + 0.05*rnorm(15)               # Prices on exchange 2.
cbind(e1, e2)
```
Euismod elementum nisi quis eleifend quam adipiscing vitae proin sagittis. Ultrices tincidunt arcu non sodales neque sodales. Lectus arcu bibendum at varius vel pharetra vel. Amet consectetur adipiscing elit ut aliquam purus sit amet. A cras semper auctor neque vitae.

Nunc eget lorem dolor sed viverra ipsum nunc. Arcu odio ut sem nulla pharetra diam sit. Ipsum consequat nisl vel pretium. Fringilla est ullamcorper eget nulla facilisi. Aliquam sem et tortor consequat id porta nibh venenatis cras. Massa tempor nec feugiat nisl pretium fusce. Dictumst vestibulum rhoncus est pellentesque elit.

##### Step 3: Run the First Graph Visual

```R
# Goal: To make a panel of pictures.
par(mfrow=c(3,2))                       # 3 rows, 2 columns.

# Now the next 6 pictures will be placed on these 6 regions. :-)
# Let me take some pains on the 1st
plot(density(runif(100)), lwd=2)
text(x=0, y=0.2, "100 uniforms")        # Showing you how to place text at will
abline(h=0, v=0)                        # All these statements effect the 1st plot.

x=seq(0.01,1,0.01)
par(col="blue")                         # default colour to blue.

# 2 --
plot(x, sin(x), type="l")
lines(x, cos(x), type="l", col="red")
```

![](/gis-cluster-test2/assets/images/r_graph.png)

<center>*Running this part of the code should yield a graph similiar to this*</center>

<br />

-----
-----
-----

#### Closing Remarks:

Euismod elementum nisi quis eleifend quam adipiscing vitae proin sagittis. Ultrices tincidunt arcu non sodales neque sodales. Lectus arcu bibendum at varius vel pharetra vel. Amet consectetur adipiscing elit ut aliquam purus sit amet. A cras semper auctor neque vitae.

#### Frequently Asked Questions:

***Q: Nunc eget lorem dolor sed viverra ipsum nunc?***  
***A:*** Arcu odio ut sem nulla pharetra diam sit. Ipsum consequat nisl vel pretium. 

***Q: Fringilla est ullamcorper eget nulla facilisi?***  
***A:*** Aliquam sem et tortor consequat id porta nibh venenatis cras. Massa tempor nec feugiat nisl pretium fusce.

***Q: Dictumst vestibulum rhoncus est pellentesque elit?***  
***A:*** Egestas fringilla phasellus faucibus scelerisque eleifend donec pretium vulputate sapien.  