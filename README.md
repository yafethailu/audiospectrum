<H1>AUDIO SPECTRUM VISUALIZER</H1>

<h2>Theory</h2>
Humans can hear sound from approximately 20 Hz to 20 kHz. The frequencies from 20 Hz to
20 kHz comprise the human auditory spectrum. An example of a spectrum visualization is shown
in Fig. 1. It basically shows the prevalence of a specific range of frequencies in the audio that it
hears. If you are listening to a song with strong bass, you would expect larger bars on the left of
the display. If the song has strong treble, you would expect larger bars on the right of the display.
Often, the spacing of the frequency bands is non-uniform, because the human auditory system is
nonlinear in its perception of frequencies. Fig. 2 shows this perceptual nonlinearity. Also, see this
page for a practical discussion

<img width="369" alt="Screenshot 2024-12-17 at 3 57 25 PM" src="https://github.com/user-attachments/assets/6be40ebc-33ff-4e00-a7e5-e8b2b483d0e2" />

<h2>Project Overview</h2>
Designed an analog filter bank in order to split the audio spectrum into discrete(ish) bins. Then, created a larger LED matrix and connect it to the ESP32 to display an audio spectrum visualization
