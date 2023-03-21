---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---

### An example interactive Bokeh chart

The following interactive chart displays normalized crime frequency per crime category per hour of the day (aggregated over the years 2004 - 2017) in San Francisco. 

Data is sourced from the [Police Department Incident Reports: Historical 2003 to May 2018](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry) data set, made available by the San Franciso Police Department.

{% include bokeh.html %}

### How this works

The Python Bokeh library can generate an output `.html` file for a given chart. The `.html` file is placed in the `/_includes` folder of the repository. The file can then be included in the markdown file for this page with `{{ '{' }}% include bokeh.html %}`.

### Test Katex

Here, have some $$\pi$$.

The greatest equation known to man is: 

$$e^{ix} = \cos{x} + i\sin{x}$$