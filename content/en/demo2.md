---
description: A demo page for the various markup elements in the Dot Org theme.
images:
- https://via.placeholder.com/250x200/d9d9d9/000000
title: demo 2
---



## Cards

Use the cards shortcode to display highlighted content on your page.

{{< cards >}}
{{< card >}}
## Something special
![Alt text](https://github.com/imfing/hextra/assets/19806136/f22f0710-23a0-430b-8bad-616283b8a3e5 "Optional title")
{{< spacer >}}
[Get our app](#)
{{< /card >}}
{{< card >}}
## Our special feature
![Alt text](https://cellar-c2.services.clever-cloud.com/documentation/doc-screenshot.png "Optional title")
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