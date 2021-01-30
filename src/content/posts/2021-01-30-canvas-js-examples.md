---
template: blog-post
title: Canvas JS examples
slug: /canvas-js-examples
date: 2021-01-30 09:00
description: Here are some Canvas JS examples 
featuredImage: /assets/bench-accounting-nvzvopqw0gc-unsplash.jpg
---
# Canvas JS examples

<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.5.0/Chart.min.js"></script>
<canvas id="bar-chart" width="800" height="450"></canvas>
<script>
// Bar chart
new Chart(document.getElementById("bar-chart"), {
    type: 'bar',
    data: {
      labels: ["Africa", "Asia", "Europe", "Latin America", "North America"],
      datasets: [
        {
          label: "Population (millions)",
          backgroundColor: ["#3e95cd", "#8e5ea2","#3cba9f","#e8c3b9","#c45850"],
          data: [2478,5267,734,784,433]
        }
      ]
    },
    options: {
      legend: { display: false },
      title: {
        display: true,
        text: 'Predicted world population (millions) in 2050'
      }
    }
});
</script>

## Miaow miaow miaow

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin lacinia lobortis est, sed euismod nibh tempus sed. Maecenas faucibus ac ligula vel aliquam. Ut vitae convallis tortor. Sed ultricies nec tellus quis euismod. Suspendisse id faucibus dolor, sit amet dignissim velit. Mauris quis neque tristique, congue ante at, rutrum sem. Integer tortor ipsum, consequat ut ligula a, auctor efficitur massa. Suspendisse dapibus purus vitae suscipit commodo.

