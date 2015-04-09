---
title: Getting Started
page_title: Getting Started
description: Getting Started
slug: rangeselector-getting-started
tags: getting,started
published: True
position: 0
---

# Getting Started



## 

This tutorial demonstrates how to use __RadRangeSelector__ to get a fine grain view of the data represented in __RadChartView__.
      

1. Place a __RadRangeSelector__ and __RadChartView__ controls on a form.
          

1. Setup your __RadChartView__ with some data.
          

1. Associate the __RadChartView__ control to __RadRangeSelector__ by setting its __AssociatedControl__ property. You can do that by one of the following ways:
          

* Set in code:
              

#### __[C#] __

{{region set associatedControl}}
	
	            this.radRangeSelector1.AssociatedControl = this.radChartView1;
	
	{{endregion}}



#### __[VB.NET] __

{{region set associatedControl}}
	            Me.radRangeSelector1.AssociatedControl = Me.radChartView1
	{{endregion}}



* Set in Property Builder at design time:
              ![rangeselector-getting-started 001](images/rangeselector-getting-started001.png)

* Set it by using the control’s SmartTag at design time:
              ![rangeselector-getting-started 002](images/rangeselector-getting-started002.png)

1. Press F5 to run the project.
          ![rangeselector-getting-started 003](images/rangeselector-getting-started003.png)