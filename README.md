# Bezier_Curve
Create Bezier curves in Python3, which is forked from [repo](https://github.com/torresjrjr/Bezier.py)

## Preview plots with _matplotlib_
![An assortment of Bezier curves plotted with matplotlib.pyplot](https://i.imgur.com/lAXdYWS.png)

_14-point 3D Bezier curve:_  

![14-point 3D Bezier curve](https://i.imgur.com/Yw2u2FX.gif)

## Usage
Save the main file Bezier_Curve into your local directory to import into your python code.
Import **Bezier** and **numpy** and use. Bezier only has 1 class for now, so you can use this commend:

```
python examples.py
```

You can plot your creations with matplotlib.

```Python
import matplotlib.pyplot as plt

plt.figure()
plt.plot(
	curve1[:, 0],   # x-coordinates.
	curve1[:, 1]    # y-coordinates.
)
plt.plot(
	points1[:, 0],  # x-coordinates.
	points1[:, 1],  # y-coordinates.
	'ro:'           # Styling (red, circles, dotted).
)
plt.grid()
plt.show()
```
The result:

![The resulting plot](https://i.imgur.com/DWjxns7.png) 

See `examples.py` for more.
