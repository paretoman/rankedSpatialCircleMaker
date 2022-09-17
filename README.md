# rankedSpatialCircleMaker
Makes a spatial model of an election, using ranked ballots for three candidates.

Just download the circleMaker.ipynb file and run in your Jupyter installation.

See the svg file for an example output:

![alaskaCircle](https://user-images.githubusercontent.com/29388117/190836368-c583c95a-a908-498e-9411-0e62a3a122e1.svg)

There is an optimizer to choose the best offset for the place where the lines cross. Ideally, the boundary lines, if extended, would end up between the gray and white dots. The white dots represent equal distribution of bullet votes and the grey dots represent proportional distribution of bullet votes according to votes with 2nd preferences.
