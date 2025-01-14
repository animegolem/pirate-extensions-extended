Very broadly in REW; 

1. Measure a single speaker with a long moving mic measurement using a measurement mic.
2. Repeat using the capsule. Match position as closely as possible. It may be helpful to hang a marker, you want to limit it to barely larger than the size of your head. 
3. Select each measurement alone and take an RMS avg. The resulting measurement will get the prefix "Magn" to show it's magnitude only. 
4. Select arithmetic and divide A/B with the Uncalibrated Mic over the Calibrated Mic. Consider adjusting the boundaries in the trace arithmetic window based on speaker roll off, e.g. the speaker rolls off at 60hz and you cut off everything below this. 
5. Save with a 20,20k cut off and 1/3rd-1/6th smoothing.

This calibration file can now be applied in REW under Preferences ---> Cal Files.  
