Run:

python mandelbrot.py
and check "mandelbrot.png":


Generate the Julia set:
Run:

python julia.py
and check "julia.png":


Modify the settings in julia.py to get a differnt Julia Set. The variable "c" is corresponding to the c of a Julia Set. The variable "bg_ratio" and "ratio" is used to set the colors.

Use the setting:

c = -0.8 * 1j
bg_ratio = (1, 3.5, 3.5)
ratio = (0.9, 0.9, 0.9)

Use the setting:

c = 0.285 + 0.01 * 1j
bg_ratio = (4, 2.5, 1)
ratio = (2, 2, 0.1)

Try more settings by yourself!

In addition, you can make an animation with Julia Set, Run:

python julia_gif.py
Then check out "julia_gif.gif":


Explore the Mandelbrot Set:
To get a local area image of Mandelbrot Set, run:

python mandelbrot_area.py
Check "mandelbrot.png":

Modify the varibales "start_x", "end_x", "start_y", "end_y" in mandelbrot_area.py to get a different area of the Mandelbrot Set. To get a different color, adjust the variables "ratio1, ratio2, ratio3".

For example, the following setting:

start_x = -0.090  # x range
end_x = -0.086
start_y = 0.654  # y range
end_y = 0.657
width = 1000
ratio1, ratio2, ratio3 = 0.2, 0.6, 0.6

Setting:

start_x = -0.750  # x range
end_x = -0.747
start_y = 0.099  # y range
end_y = 0.102
width = 1000
ratio1, ratio2, ratio3 = 0.1, 0.1, 0.3