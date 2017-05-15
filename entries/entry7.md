

# Welcome Back

Hello all you wonderful people, this week I have been tinkering around with examples of plotly and I have been trying to breakdown what different lines of code do  before I start the framework for
my final project next week. I figured I would take a look of an example of code from the plotly tutorial together.



# Let's Learn Together

This is some code provided as a simple scatter plot from Plotly’s very own tutorial, let's go over what my interpretation of what everything does.


```python
import plotly.plotly as py
import plotly.graph_objs as go

# Create random data with numpy
import numpy as np

N = 1000
random_x = np.random.randn(N)
random_y = np.random.randn(N)

# Create a trace
trace = go.Scatter(
    x = random_x,
    y = random_y,
    mode = 'markers'
)

data = [trace]

# Plot and embed in ipython notebook!
py.iplot(data, filename='basic-scatter')

# or plot with: plot_url = py.plot(data, filename='basic-line')
```

Some parts are already commented but I will try to explain further. 

The first two lines tell python to import the plotly library which will allow the ability to make graphes. 
np or numpy is just used in this case to create random values to use for data points on the graph which is also what the next 3 lines of code do.
trace allows python to connect the points on the graph and the last two lines of code refer to different ways of displaying the graph. The first way is for a special program
that you can download for free, the other allows you to access your graph on a website address. 




# My final project

My goal is to make a plotly API where I can display a series of varying graphs in perhaps a form of infographic using python. Now this week I studied more on what Ploty is and how it works using the online web version of ploty. 
    Next week, I will be setting up my Api and then from there I will attempt to create some graphs  with the code that I create. 
    
    

# Takeaways

Do not be afraid to take a step in another direction than which you came because it may lead you to find a whole new world of possibilities. For example, I started with python about as simple as can be but wound up 
studying the field of making graphs with ploty. Just because you can not and should not give up studying your field of research does not mean you are restricted to only the limited first steps. 
 

