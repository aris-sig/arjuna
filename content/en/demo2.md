---
description: A demo page for the various markup elements in the Dot Org theme.
images:
- https://via.placeholder.com/250x200/d9d9d9/000000
title: 
---



## Cards

Use the cards shortcode to display highlighted content on your page.

{{< cards >}}
{{< card >}}
## Something special
Lorem ipsum dolor sit amet consectetuer adipiscing elit aenean commodo
{{< spacer >}}
[Get our app](#)
{{< /card >}}
{{< card >}}
## Our special feature
Lorem ipsum dolor sit amet consectetuer adipiscing elit aenean commodo
{{< spacer >}}
[See our special feature](#)
{{< /card >}}
{{< /cards >}}

## Plotly Chart

<div id="chart"></div>

<script src="https://cdn.plot.ly/plotly-latest.min.js"></script>
<script>
    document.addEventListener("DOMContentLoaded", function() {
        var data = [{
            x: [1, 2, 3],
            y: [4, 5, 6],
            type: 'scatter'
        }];
        Plotly.newPlot('chart', data);
    });
</script>