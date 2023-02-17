# Real-Time Framework for Generating Next-Month Work Schedules for Road Inspection Workers 

This repository contains code for a real-time framework for generating next-month work schedules for road inspection workers.
The framework optimizes the schedules using road GPS data and Gurobi to balance workload, minimize travel distance,
and consider constraints such as roads that need inspections 2x p/week and others need 1x p/month.

# Folder Structure

**This repository has two folders:**

                                            Raw Data input & optimization

**road_gps_data.csv:** GPS data for the roads to be inspected.

**csv for original schdule inputs:** Original work schedule data for the road inspection workers.

**optimization_schedule.ipynb:** Jupyter notebook file that optimizes the schedules using the road GPS data.

                                            Data output & Visualization

**csvs for optimized schdules:** Optimized work schedule data for the road inspection workers.

**schedule_visualization.ipynb:** Jupyter notebook file that visualizes the optimized schedules and generates a user interface with controls for displaying schedules, routes, and route information.


# Project Background

The real-time framework was developed to generate next-month work schedules for road inspection workers. The schedules were optimized using Gurobi to balance workload and minimize travel distance while also considering constraints such as roads that need inspections 2x p/week and others need 1x p/month.

The project also automated compiling and cleaning of Excel inputs and created a user interface with controls for displaying schedules, routes, and route information using Python in Jupiter notebook and Google API. The framework generated next-month work schedules in real-time for road inspection workers, resulting in improved efficiency and cost savings for Downer.

# How to Use

To use this code, you can download or clone this repository to your local machine. You can then run the Jupyter notebook files to optimize the schedules and visualize the results.

For optimizing schedules, run optimization_schedule.ipynb.
For visualizing schedules, run schedule_visualization.ipynb and open the generated schedule_ui.html file in a web browser.
Dependencies

# This code requires the following dependencies:

1.Python 3

2.Jupyter Notebook

3.Gurobi optimizer

4.Pandas

5.Matplotlib

6.Seaborn

7.Plotly

9.Google Maps API
