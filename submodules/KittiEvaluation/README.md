# Usage

Build: run `make` to build the code <br>
Use: run `evaluate_object /path/to/prediction /path/to/gt` to run kitti evaluation <br>

The following output is expected:

```
Thank you for participating in our evaluation!
Starting to evaluate Results found in: val_pred
Loading detections...
  done.
PDFCROP 1.38, 2012/11/02 - Copyright (c) 2002-2012 by Heiko Oberdiek.
==> 1 page written on `car_detection.pdf'.
Evaluation Succesfull. Results can be found:
val_pred /results
```

GNUPLOT is required, if you want to see plots.
