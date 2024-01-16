# Welcome

On this page, we have added an interactive chart.
It will show you a tooltip as you hover over a point and fade out the points that do not belong to the species you're currently hovering over.
This means that you cannot really interact with the chart or the table.

All of that was made possible by adding elements from `{ggiraph}` to the previous plot.
The only thing one has to be careful with it the `z-index` of the tooltip.
It needs to be set higher than that of the cards (1000).
Otherwise the tooltip won't be visible.
