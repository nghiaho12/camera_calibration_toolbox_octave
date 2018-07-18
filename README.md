# camera_calibration_toolbox_octave
An Octave port of Camera Calibration Toolbox for Matlab (1st June 2017) (http://www.vision.caltech.edu/bouguetj/calib_doc/)

There is surprisingly very little code modification required to make the origina Matlab code work in Octave (tested with 4.4.0). I only had to comment out usage of BackingStore

```
set(fig_number,'Units','points', ...
    %'BackingStore','off', ...
```

I've tested with single camera and stereo calibration. The GUI elements in Octave are usable, though rendering isn't 100% perfect. I found Octave GUI can be a bit quirky at times, might be related to my choice of using the i3 tiling windows manager.
