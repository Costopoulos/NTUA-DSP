# Part 1

The first part had to do with tracking telephone touch-tones.
Each digit can be described as the sum of two sines so we write them this way and we record a sequence in a .wav file.
We then plot the recorded signal using hamming and rectangular windows.
After that, we calculate the coordinates of the peak of each digit by calculating the frequency from crossings.
Lastly, with two different signals as input, we have to decode the digits in them and print them.

# Part 2

The second part has to do with Short Time Fourier Transform (STFT) and Wavelets Transform (Discrete Time CWT).
We first plot the stft of a signal and then its absolute CWT in the fields of both time and frequency and compare the analysis quality of each transform.
By adding some white noise and dirac deltas we perform the same tasks and we see that DTCWT is inferior to the STFT due to the noise.

# Part 3

The third part has to do with short term energy and crossing rate of voice and music signals.
Using a hamming window we calculate the above from the speech_utterance.wav file and compare them with the respective results from the music.wav file.
We came to the conclusion that wider window means less precise short term energy and that gaussian noise reduces the crossing rate of the silent spots. This is why we cannot distinguish loud(periodical and wide) from silent noises(aperiodical).
