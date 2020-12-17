# Structure-from-motion

- Implemented a dense depth reconstruction from a sequence of images captured using a calibrated smartphone camera.
- Used `scipy.optimize.least squares` to minimize reprojection error during bundle adjustment.
- The sparse reconstruction through bundle adjustment was not very accurate but it was able to give rough estimation of the objects in the image in the 3D space.
- Used Plane Sweep Stereo algorithm to make a dense depth reconstruction. The results weren't satisfactory because of some implementation mistakes.
