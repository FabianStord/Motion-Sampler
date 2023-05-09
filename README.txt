The files hg_fftPlayback, hg_fftRecord and SpectralFreeze might not be needed but they are included just in case.

Within the app use the "game"-sensor rate and connect using port 30000
The project uses the Sensors2OSC app available for android
Enable these sensors:
	Accelerometer
	Orientation	
	Light
Enable send data

HOW TO USE:
The samplers main functions are all turned on or off using the multi touch  page
1 tap with 1 finger: Enables the orientation data to be sent to the sequencer
	If you are using a large amount of steps it might take some time before the sequencer starts moving since it has to collect values for all steps before sequencing
2 taps with 1 finger: Functions as the systems on and off switch. Also enables record for the spectral freeze
3 taps with 1 finger: Starts recording the LFO data. Tap 3 times again to save the LFO and assign it to a parameter of choice.
1 tap and hold: Tap and drag your finger around to change the pitch, if nothing changes press with a second finger while still holding to enable and disable the pitch shifting.

Tempo: Tempo is the original tempo of your sample. A higher tempo will result in a slower sample and vice versa.

Segment smoothing: Creates a small envelope between sample segements, use this if you hear a lot of clicking noises. 

Steps: The amount of steps in a sequence

Filter: Pressing the light filter control will use your front camera light sensor to control the filter cutoff
	Filter types and resonance have to be changed manually.

Spectral freeze: The FFT window decides how much audio should be recorded. A larger window will mean more data is recorded to the spectrogram.
	The playback speed is controlled the same way as the pitch shift by dragging 1 finger around.
	The volume of the spectral freeze can be controlled using orientation data. Simply tap once with 3 fingers to enable or disable it.
