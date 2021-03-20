# Part 1

The first part has to do with calculating short time energy and stft of movement and heart rate signals.
By reading a file, we plot its components (acc, gyr, hrm) in all axis. Then we calculate and plot their short time energies, as well as their STFTs.
Lastly, we define the characteristics of a signal (mean, min, max, standard deviation) and, by comparing sleep_03.npz and step_03.npz, we see that what distinguishes a sleeping from an awake person is the 
1) standard deviation
2) min
3) max

If a person's heart rate has high maximums and low minimums, as well as high standard deviation, then the person is awake. Else, he is asleep.

# Part 2

The second part has to do with calculating Teager-Kaiser energy in multiple frequency layers by using Gabor filterbank.

# Part 3 

This part was optional.

# Part 4

The fourth part has to do with reducing the noise of movement signals by using Butterworth and Wiener filter.
