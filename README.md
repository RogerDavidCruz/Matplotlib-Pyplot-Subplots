# Guided Lab 386.5.6 – Matplotlib Pyplot: Subplots

## Overview

This lab introduces Matplotlib's subplot functionality for displaying multiple charts within a single figure. It demonstrates different subplot layouts, including horizontal, vertical, and grid arrangements, while showing how to customize each subplot independently and improve figure organization with automatic layout adjustments.

## Objectives

* Create multiple plots in a single figure
* Use `plt.subplot()` and `plt.subplots()`
* Arrange subplots in different layouts
* Customize individual subplot titles and labels
* Share axes between subplots
* Improve figure readability using `plt.tight_layout()`

## Technologies Used

* Python 3
* Matplotlib
* NumPy
* Google Colab / Jupyter Notebook

## Methods & Concepts

* `plt.subplot()` – Create individual subplot positions
* `plt.subplots()` – Generate a figure and multiple axes objects
* `fig` – The overall figure containing all subplots
* `axs` / `axes` – Individual subplot (Axes) objects
* `.plot()` – Plot data on a specific subplot
* `.set_title()` – Set subplot titles
* `.set_xlabel()` – Set x-axis labels
* `.set_ylabel()` – Set y-axis labels
* `plt.tight_layout()` – Automatically adjust subplot spacing
* `sharex=True` – Share the x-axis across subplots
* `sharey=True` – Share the y-axis across subplots
* `np.linspace()` – Generate evenly spaced values for plotting mathematical functions

## Key Points

* A **Figure (`fig`)** is the top-level container that holds one or more plots.
* Each **Axes (`axs` or `axes`)** object represents an individual subplot.
* `plt.subplot()` is useful for creating simple subplot layouts.
* `plt.subplots()` is the preferred approach for creating multiple subplots because it returns both the figure and axes for easier customization.
* `plt.tight_layout()` automatically prevents overlapping titles, labels, and tick marks.
* Subplots can be arranged horizontally, vertically, or in a grid depending on the visualization needs.
* Shared axes (`sharex` and `sharey`) improve readability by using common scales across multiple plots.

## Topics Covered

* Creating subplots
* Horizontal subplot layouts
* Vertical subplot layouts
* 2×2 subplot grids
* Figure and Axes objects
* Custom subplot titles
* Axis labels
* Shared x-axis and y-axis
* Automatic layout adjustment
* Visualizing multiple datasets in one figure

## Dataset

The lab uses sample datasets generated in Python, including:

* Linear data
* Polynomial sequences
* Trigonometric functions (`sin`, `cos`, `tan`)
* Exponential function

## Learning Outcome

By completing this lab, I gained hands-on experience creating and organizing multiple visualizations within a single Matplotlib figure. I learned how to build different subplot layouts, customize each subplot independently, share axes for consistent comparisons, and use `plt.tight_layout()` to create clean, professional, and easy-to-read visualizations.
