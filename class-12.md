# CHART.JS
```

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <title>Chart.js demo</title>
        <script src='Chart.min.js'></script>
    </head>
    <body>
    </body>
</html>

````
There are three common types of charts :
## 1. line chart
```
<canvas id="buyers" width="600" height="400"></canvas>

//Next, we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element:

<script>
    var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
</script>

//Then :

var buyerData = {
	labels : ["January","February","March","April","May","June"],
	datasets : [
		{
			fillColor : "rgba(172,194,132,0.4)",
			strokeColor : "#ACC26D",
			pointColor : "#fff",
			pointStrokeColor : "#9DB86D",
			data : [203,156,99,251,305,247]
		}
	]
}
```

## 2. pie chart 
```

<canvas id="countries" width="600" height="400"></canvas>

//Next, we need to get the context and to instantiate the chart:

var countries= document.getElementById("countries").getContext("2d");
new Chart(countries).Pie(pieData, pieOptions);

then:

var pieData = [
	{
		value: 20,
		color:"#878BB6"
	},
	{
		value : 40,
		color : "#4ACAB4"
	},
	{
		value : 10,
		color : "#FF8153"
	},
	{
		value : 30,
		color : "#FFEA88"
	}
];

//Now, immediately after the pieData we’ll add our options:

var pieOptions = {
	segmentShowStroke : false,
	animateScale : true
}

```

## 3. bar chart
```
<canvas id="income" width="600" height="400"></canvas>

//Next, we retrieve the element and create the graph:

var income = document.getElementById("income").getContext("2d");
new Chart(income).Bar(barData);

// And finally, we add in the bar chart’s data:

var barData = {
	labels : ["January","February","March","April","May","June"],
	datasets : [
		{
			fillColor : "#48A497",
			strokeColor : "#48A4D1",
			data : [456,479,324,569,702,600]
		},
		{
			fillColor : "rgba(73,188,170,0.4)",
			strokeColor : "rgba(72,174,209,0.4)",
			data : [364,504,605,400,345,320]
		}

	]
}
```

# ```</canvas>``` tag

```
<canvas id="tutorial" width="150" height="150"></canvas>
```


