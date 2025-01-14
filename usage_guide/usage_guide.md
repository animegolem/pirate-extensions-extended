It's important to understand going in that In-Ear Mics are finnicky and complicated, while your measured result will likely be a *very* good starting point some work will still be required to understand your preferences and any issues in your specific measurement setup. Additionally blocked canal mics will not pick up any canal effects and you should expect notable variation from 2-3k in particular. 

Some familiarity with basic audio science concepts is likely required to use these mics and is well beyond the scope of this guide. Read the original papers and proceed with caution. 

The basic steps required are as follows; 

1. [Create a compensation file for the electret capsule.](microphone_compensation.md) 

2. [Create your personal DF HRTF target.](personal_target.md) This is the preferred but significantly more complicated option. It will also requires a speaker with sufficient directivity to be EQ'd flat in the listening position.
   
      or

3. EQ using the "ISO 11904" or "ARI, HUTUBS, RIEC, SONICOM AV" targets. This should be more than sufficient to improve in-situ bass response and midrange up to 1-2k. The treble may vary more widely but in practice this should be similar to EQing using rig results. Since you are capturing the correct HPTF effects you will likely find your results more repeatable from headphone to headphone, however. 

4. Measure headphones with compensation file in place. Your results will only be comparable to other measurements taken in your ear, with the same cal file, with the same microphone. 

If you do not wish to stand up your own graphtool the best option will be be using [Listener's Playground](https://listener800.github.io/eqplayground) or my [graphtool](https://animegolem.github.io/)
