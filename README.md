# curvatureMeasure

**Note: Presently correcting a bug for circle Fit. Will update the correction in a few moments**

`curvatureMeasure.m` is a Mathematica script for calculating curvature along the boundary of an image object. Note: sensitive to boundary discretization and the bin selected for circle fits.  

#### image

![Alt text](https://github.com/alihashmiii/curvatureMeasure/blob/master/for%20ReadMe/inputImage.png)

## computing curvature


#### boundary discretized into equidistant points

![Alt text](https://github.com/alihashmiii/curvatureMeasure/blob/master/for%20ReadMe/mesh.png)

#### circle fits to a point P<sub>i</sub>, P<sub>i</sub> + N-left, P<sub>i</sub> + N-right

![Alt text](https://github.com/alihashmiii/curvatureMeasure/blob/master/for%20ReadMe/curvatureFitstoShape_cropped.png)

#### curvatures as colormap

![Alt text](https://github.com/alihashmiii/curvatureMeasure/blob/master/for%20ReadMe/curvatureFinal.png)
