# Toy Matplotlib layout manager

To run you need matplotlib and kiwi solver.  `pip install git+https://github.com/nucleic/kiwi.git` is needed to use the latest `python3` version.  

This is just lightly modified from https://github.com/Tillsten/MplLayouter

See https://github.com/matplotlib/matplotlib/issues/1109

To run `python layout.py`

Status: its pretty messy, but does what I want.  Todo: clean up methods, and come up with clean way to link axes.

Figure out how to add subsidiary axes like colorbars.

Figure out why top and right text labels are sticky to the right instead of sticky to the AxesTick object.  (i.e. title2 below, and "right" below).  

Long term, turn into a MEP

<img width="645" alt="example" src="https://user-images.githubusercontent.com/1562854/28897939-03043d40-7798-11e7-8925-a7fbcca004a6.png">
