The following packages were used in this project:

Tensorflow
OpenCV2
tifffile
shapely.geometry
shapely.wkt
numpy
sklearn
time
csv
os
pandas

The datasets are too large to upload as well. All the necessary data will be found here: https://www.kaggle.com/c/dstl-satellite-imagery-feature-detection/data
All files are necessary.

(Furthermore, I will also submit a folder with the prediction masks and the submission.csv that reached the highest score.) I tried to implement the saving and loading weights for a neural net, but unfortunately there were issues with the tensorflow library that I could not solve. The statement in brackets is unfortunately not true. The prediction masks have a size of 23.8GB and can therefore also not be uploaded. The only thing uploaded will be the polygon csv. Theoretically one can then again construct the predction masks from the csv if wanted. This should be easily possible by putting snippets of my code together.

I would like to point out that part of the routine for making polygons from masks and vice versa was gratefully provided in this great kaggle kernel: https://www.kaggle.com/lopuhin/dstl-satellite-imagery-feature-detection/full-pipeline-demo-poly-pixels-ml-poly. This had to be manipulated for using it in my context, but the functions are the same. This is still only a part of the preprocessing.
