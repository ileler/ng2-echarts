
# 0.0.1

1. Exports the directive object, so you can interact with the directive inside the template without having to write code [see it better explained here](http://blog.thoughtram.io/angular/2016/03/21/template-driven-forms-in-angular-2.html)
	1. `ng2-echarts` is exported as `ng2Echarts`
- The directives now have the getter `chart` method. It returns the current chart object. Note that if you change the `options`, the chart will be destroyed and you will need to call chart again to get the new chart created again to interact with it.
- Readme.md was updated with an example on how to use this library with Webpack.
- Changelob.md was created.
