My take on creating a network graph using networkx and Dash/plotly functionality.

The Dash application will run within Jupyter, so here are some instructions on running it smoothly:

1. Run every cell of the Jupyter notebook
2. If you hit a "404 Error: Page not Found" error at the very bottom of the notebook, proceed with the following steps in a Terminal:
  a. Type the following lines on the terminal:
          <i> pip uninstall jupyter_server_proxy </i>
          <i> pip install jupyter_server_proxy </i>
          <i> jupyter serverextension enable jupyter_server_proxy </i>
  b. Re-start your Jupyter Notebook and run everything. 
