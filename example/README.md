## The example code in this repository demonstrates a problem with the Flutter ECharts library.

The chart used in this repository is the exact copy of this example code from the ECharts website: [Multiple Y-Axis Chart](https://echarts.apache.org/examples/en/editor.html?c=multiple-y-axis)

The main problem is that the third (GREEN) axis is not actually visible in the app.
This is probably caused by the offset on that axis, which in this case is not avoidable, since we have so many axes on this chart.

Resizing the parent Flutter container in any possible way didn't help.
Please contact me if you know how to fix this issue.

<table border="0">

<tr>
<th>Desired result (a screenshot from the ECharts website):</th>
<th>How it actually appears in the application:</th>
</tr>

<tr>
<td><img src="https://raw.githubusercontent.com/dJani97/flutter_echarts_overflow/master/how_it_should_look_like.png" alt="How it should look"></td>
<td><img src="https://raw.githubusercontent.com/dJani97/flutter_echarts_overflow/master/how_it_actually_looks_like.png" alt="How it looks"></td>
</tr>
	
</table>


