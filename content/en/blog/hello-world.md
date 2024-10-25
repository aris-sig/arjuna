---
author: caniszczyk
date: "2023-08-01"
description: ""
title: Halo dunia
---

selamat datang to our first blog post. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula get dolor. Aenean massa. 

Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate get, arcu. In enim justo, rhoncus ut imperdiet a.
## Interactive Data Visualization

One of the most exciting parts of web development for me has been creating interactive charts. Below is an example of an interactive Plotly chart generated in Python. 

<script src="https://cdn.plot.ly/plotly-latest.min.js"></script>
<div>
  <div id="my-python-plot" class="plotly-graph-div" style="height: 500px; width: 100%;"></div>
  <script type="text/javascript">
    var trace1 = {
      x: [1, 2, 3, 4, 5],
      y: [10, 15, 13, 17, 22],
      mode: 'lines+markers',
      type: 'scatter',
      name: 'Data Points'
    };

    var data = [trace1];

    var layout = {
      title: 'Interactive Line Chart',
      xaxis: {
        title: 'X Axis'
      },
      yaxis: {
        title: 'Y Axis'
      }
    };

    Plotly.newPlot('my-python-plot', data, layout);
  </script>
</div>

## Conclusion

Thank you for reading my first blog post! I look forward to sharing more insights, projects, and tutorials in the future. If you have any questions or topics you’d like me to cover, feel free to reach out.

Stay tuned for more posts, and happy coding!
