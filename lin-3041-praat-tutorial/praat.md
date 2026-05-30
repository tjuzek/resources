Download Praat from https://www.fon.hum.uva.nl/praat/ and install it. 

Run Praat. In the Objects window, under menu "Open", select "Read from file". Open the vowel recordings file. 

A new window opens. In your first session, go through the menus. Go to Pitch > uncheck "Show Pitch", same for Intensity and Pulses. However, make sure that under Spectrum and Formants, you do check the respective show options. 

Now you should see something like this: 

![praatoverview](https://github.com/tjuzek/introduction_linguistics/blob/main/praat_overview.jpg?raw=true)

The top half of the screen is the wave form. Each black 'blob' represents a word. The bottom half is the spectrogram and will become visible once we zoom in. 

You can left-click, hold, and drag an area to make a selection. At the top of the selection is a number, roughly around 0.6 - 0.8, that is the duration of the selection in seconds. If you click on it, you listen to the selection. 
If you have problems with your sound, look here under Section 4: https://www.fon.hum.uva.nl/praat/download_mac.html 

To zoom into your selection, press the "sel" button at the bottom left corner. You should now see something like this: 

![closeup](https://github.com/tjuzek/introduction_linguistics/blob/main/close_up.jpg?raw=true)

The first step of taking your measurements is always the same: 

- Identify the vowel
- Identify the strong and stable signal from which you want to measure

What does "strong and stable" mean? 

Strong: You can hear the vowel (select and play the selection) and there is some amplitude in the wave representation. 

Stable: Praat is able to take reasonable measurements. To understand this, we need to understand what we wish to measure. 

We wish to measure the resonance frequencies of the vowels. The vocal cords are flapping, resonating air flows through the vocal tract, and other articulators will begin to resonate. 
The lowest resonant frequency is called F1 / first formant, the second lowest F2 / second formant, etc. For our purposes, we wish to measure F1 and F2. 

Praat takes measurements at intervals. In each batch of measurements, F1 is represented by the lowest red dot, and F2 by the lowest white dot. The following picture illustrates this. 

![measurements](https://github.com/tjuzek/introduction_linguistics/blob/main/measurements.jpg?raw=true)

Some of Praat's measurements are better than others (for various reasons). This brings us back to to 'stable' measurements. 'Stable' means that changes in frequency between one measurement and the next are limited. For F1, a delta beyond 100Hz for F1 is already large. For F2, the delta should not exceed 200Hz, max. 250Hz. 

The following image illustrates some stable vs some jittery measurements. We want to avoid jitter. 

![goodbad](https://github.com/tjuzek/introduction_linguistics/blob/main/good_bad_signal.jpg?raw=true)

We can start taking measurements. In doing so, we need to distinguish two cases: monophtongs and diphtongs. 

For monophtongs, the syllable / word we measure contains a single vowel, e.g. \<beat\> as /bi:t/. We can take a manual measurement from the middle of the strong and stable signal. We take a measurement by left-clicking on a good F1 and/or F2 dot, this will give us a Hz value (in red) on the left hand site; "good" dots to measure from are illustrated below. 

![monogood](https://github.com/tjuzek/introduction_linguistics/blob/main/mono_good_region.jpg?raw=true)

Or we select the entire strong and stable signal and use the option: Formants > Get First/Second Formant. 

For diphtongs, the syllable / word we measure contains two vowels, e.g. \<bait\> as /bejt/. For the first vowel, e.g. /e/, we take a measurements from the first four dots of the strong and reliable signal. For the second vowel /j/, we take a measurement from the last four dots. Alternatively, we make a selection of a few dots and use the Formant menu again. 
  
![digood](https://github.com/tjuzek/introduction_linguistics/blob/main/diph_good_region.jpg?raw=true)

Collect the measurements for the different words and submit your findings. 
