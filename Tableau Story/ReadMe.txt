##### This folder contains files created for Tableau Story Capstone Project.

* Bokeh: https://bokeh.pydata.org/en/latest/docs/user_guide.html - for interactive plotting in python - can create an html or can be used in jupyter notebook too
    ```
    from bokeh.io import show, output_notebook
    from bokeh.plotting import figure

    output_notebook()
    fruits = ['Apples', 'Pears', 'Nectarines', 'Plums', 'Grapes', 'Strawberries']
    counts = [5, 3, 4, 2, 4, 6]

    p = figure(x_range=fruits, plot_height=350, title="Fruit Counts",
               toolbar_location=None, tools="")

    p.vbar(x=fruits, top=counts, width=0.9)

    p.xgrid.grid_line_color = None
    p.y_range.start = 0

    show(p)
    
    ```
    This displays a simple bar chart (tried it on colab)

* Tableau Wrangling Tips:
https://www.datasciencecentral.com/video/video/show?id=6448529%3AVideo%3A892105
