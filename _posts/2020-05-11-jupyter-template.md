---
layout: post
title:  "Jupyter Notebook Based Tool Template"
author: jim
categories: [ jupyter, python, tool, Template ]
tags: [Advanced]
image: assets/images/jupyter.png
rating: 5
---

<!-- Quick Description:  -->
Maecenas volutpat blandit aliquam etiam erat. Imperdiet dui accumsan sit amet nulla facilisi morbi.

#### What is this Tool?
Eu scelerisque felis imperdiet proin fermentum leo vel orci porta. Sit amet porttitor eget dolor. Egestas dui id ornare arcu odio. Fusce ut placerat orci nulla. Fermentum iaculis eu non diam phasellus vestibulum lorem sed. Tempus iaculis urna id volutpat lacus laoreet non. Phasellus faucibus scelerisque eleifend donec pretium vulputate sapien. Nunc congue nisi vitae suscipit tellus mauris a.

#### Why Use This Tool [Use Cases/Workflow Integration]?

Examples of Use Cases:
> Non curabitur gravida arcu ac tortor. Ut enim blandit volutpat maecenas volutpat blandit aliquam. Nam aliquam sem et tortor consequat id. Turpis massa tincidunt dui ut ornare.

Potential Integeration Possibilities:
> Magna ac placerat vestibulum lectus mauris ultrices eros. Ut sem nulla pharetra diam sit amet nisl. Ipsum a arcu cursus vitae. 

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

# Notebook Walkthrough

* For a live version of the Jupyter Notebook, click here: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/CmdrKerfy/python-binder-directory/master)

You may also see below for a step by step guide on how to use this tool, if you prefer. 

##### Step 1: Set up

```python
print("Hello World")
```
Lectus quam id leo in vitae turpis massa. Urna nunc id cursus metus aliquam eleifend mi in. 

##### Step 2: Import Datasets

```python
import geopandas as gpd

c = 'p'
print("The ASCII value of '" + c + "' is", ord(c))
```
Euismod elementum nisi quis eleifend quam adipiscing vitae proin sagittis. Ultrices tincidunt arcu non sodales neque sodales. Lectus arcu bibendum at varius vel pharetra vel. Amet consectetur adipiscing elit ut aliquam purus sit amet. A cras semper auctor neque vitae.

Nunc eget lorem dolor sed viverra ipsum nunc. Arcu odio ut sem nulla pharetra diam sit. Ipsum consequat nisl vel pretium. Fringilla est ullamcorper eget nulla facilisi. Aliquam sem et tortor consequat id porta nibh venenatis cras. Massa tempor nec feugiat nisl pretium fusce. Dictumst vestibulum rhoncus est pellentesque elit.

##### Step 3: Run the First Graph Visual

```python
import geopandas
import geoplot

world = geopandas.read_file(
    geopandas.datasets.get_path('naturalearth_lowres')
)
boroughs = geopandas.read_file(
    geoplot.datasets.get_path('nyc_boroughs')
)
collisions = geopandas.read_file(
    geoplot.datasets.get_path('nyc_injurious_collisions')
)
```

![](/gis-cluster-test2/assets/images/jupyter_graph.jpg)

*Running this part of the code should yield a graph similiar to this*

* **Line 1-2, 'Import':** 
    * Eu scelerisque felis imperdiet proin fermentum leo vel orci porta. Sit amet porttitor eget dolor. Egestas dui id ornare arcu odio. 

* **Line 4-6, 'World':**
    * Fusce ut placerat orci nulla. Fermentum iaculis eu non diam phasellus vestibulum lorem sed. Tempus iaculis urna id volutpat lacus laoreet non. Phasellus faucibus scelerisque eleifend donec pretium vulputate sapien. Nunc congue nisi vitae suscipit tellus mauris a.

-----
-----
-----

#### Closing Remarks:

Euismod elementum nisi quis eleifend quam adipiscing vitae proin sagittis. Ultrices tincidunt arcu non sodales neque sodales. Lectus arcu bibendum at varius vel pharetra vel. Amet consectetur adipiscing elit ut aliquam purus sit amet. A cras semper auctor neque vitae.

Nunc eget lorem dolor sed viverra ipsum nunc. Arcu odio ut sem nulla pharetra diam sit. Ipsum consequat nisl vel pretium. Fringilla est ullamcorper eget nulla facilisi. Aliquam sem et tortor consequat id porta nibh venenatis cras. Massa tempor nec feugiat nisl pretium fusce. Dictumst vestibulum rhoncus est pellentesque elit.

Cursus turpis massa tincidunt dui. Imperdiet sed euismod nisi porta lorem mollis. Habitant morbi tristique senectus et netus et malesuada fames. Semper eget duis at tellus at urna. Odio facilisis mauris sit amet massa.

#### Frequently Asked Questions:

***Q: Nunc eget lorem dolor sed viverra ipsum nunc?***  
***A:*** Arcu odio ut sem nulla pharetra diam sit. Ipsum consequat nisl vel pretium. 

***Q: Fringilla est ullamcorper eget nulla facilisi?***  
***A:*** Aliquam sem et tortor consequat id porta nibh venenatis cras. Massa tempor nec feugiat nisl pretium fusce.

***Q: Dictumst vestibulum rhoncus est pellentesque elit?***  
***A:*** Egestas fringilla phasellus faucibus scelerisque eleifend donec pretium vulputate sapien.  