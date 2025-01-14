Very roughly, 

1. Take a long moving mic measurement of a single speaker with good directivity. This is using a measurement microphone, not your DIY PIRATE.  
2. Very strictly EQ the speaker to flat. Limit your measuring position very tightly, only slightly larger than the expected space of your own head as you rotate and look up and down. If possible consider hanging a marker above the intended listening position. 
----> EQ is best done by creating a equalizer APO graphic EQ via AutoEQ which functionally is the same as a convolution filter. You will likely need to raise Max Gain and Max Slope quite substantially, on the order of 75/35.
3. Remeasure the speaker to validate the eq results. Ideally remeasure using the capsule to validate the calibration.     
4. Enable the generator in REW and calibrate the capsule mic while in ear using an external SPL meter.
5. In a rotating chair take a moving mic measurement. Aim to move slowly and evenly while looking fully up and down from all positions while repeatedly rotating 360. Repeat this until the measurement has become stable, likely in the range of 600-1000 avgs.
6. Repeat for the second ear. Your ears are not identical and while they should broadly track you should not expect them to be identical. Take an average of both results. 
7. Using the measurement window in REW find the best point of agreement around 2khz against one of the targets provided on my [graphtool](). Remember to remove any adjustments.
8. Smooth as required and merge the results. 

I recommend standing up your own instance of Haruto's [PublicGraphTool](https://github.com/HarutoHiroki/PublicGraphTool) since the tilts and Harman filters are *incredibly* useful in finding your preference. It's a pain in ass but you're already this far.  
