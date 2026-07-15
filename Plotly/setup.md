# poltly introduction.

## what is plotly .

plotly is an open sourse projact modern and interactive visualizations for Pyhton and JavaScript.

open this [link](https://plotly.com/graphs/) to find more in there main page.

open this [link](https://github.com/plotly/plotly.py.git) to find more in there github page.

---

## setup 

###to install plotly .

put this in the terminal.

* for windows ` pip install plotly `.

* for linux ` pip3 install plotly `.

### to import 

`import plotly.express as px`

first code.

```python
import plotly.express as px

x = [1, 2, 3, 4, 5]
y = [2, 3, 4, 5, 6]

fig = px.line(x=x, y=y, title='Simple Line Chart')
fig.show() 
```
![example]()
