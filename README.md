# Mandelbrot Set Visualization

This Python script generates visualizations of the Mandelbrot set using the Numba library for just-in-time compilation, which enhances performance. The Mandelbrot set is a famous mathematical set of complex numbers, and this script creates visual representations by determining which complex numbers belong to the set.

## Dependencies
Make sure you have the following libraries installed:

- Numpy
- Matplotlib
- Numba

You can install these libraries using the following:

```bash
pip install numpy matplotlib numba
```

## How to Use

1. **Run the Script:**
   Execute the script in a Python environment.

2. **Zoom into the Mandelbrot Set:**
   The script includes a function called `plot_mandelbrot` that visualizes the Mandelbrot set for a specified range of axes. Feel free to modify the parameters in the function calls to zoom into different regions of the Mandelbrot set.

3. **Adjust Parameters:**
   You can modify parameters such as `max_iter` (maximum number of iterations), colormap (`cmap`), and the range of axes to explore different aspects of the Mandelbrot set.

4. **View and Explore:**
   The script will generate and display visualizations of the Mandelbrot set. Experiment with different parameter values to explore various sections of the set.

Feel free to use, modify, and experiment with the script to gain insights into the fascinating world of fractals and the Mandelbrot set.

**Note:** Ensure that you have an environment that supports the execution of Python scripts with the specified libraries.