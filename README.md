## DIGITAL SIGNAL PROCESSING and DEEP-LEARNING
--------------------------------------------------------

### Basics
- DSP/Audio Features for ML: Valerio Velardo
- DSP: Basics - Aliasing, Nyquist Freq.,lowest detectable frequency
- A signal sampled with a 32 KHz SR, any freq. components > 16 KHz (N.F.), we get an aliasing
- Nyquist Frequency and the relation between sampling-rate and max. frequency
  $F_{max} = Sampling Rate/2$
  $F_{max}$ is called Nyquist Frequency
- Wav length (size) of np array = SR * duration of clip
- Sound perception: - link, link

We perceive sound lograthimically
Weber-Fechner law: Above a minimal threshold of perception $S_0$, perceived intensity $P$ is logarithmic to stimulus intensity $S$: $P = K. log (\frac{S}{S_0})$
Time domain features
Amplitude Envelope
RMS Energy
FFT
$s(t) = A_1.sin(2\pi.f_1.t + \phi_1) + A_2.sin(2\pi.f_2.t + \phi_2) + \ldots{}$
FFT: Y-axis: Magnitude, X-Axis: Freq.
Plotting a sine wave using freqs. link
When plotted - it shows a reflection around Nyquist Frequency = SR/2.
Reflection = aliasing
STFT
Compute FFT at several intervals
Interval = Frame length
Preserves time domain even though it is a freq. transformation!!
SSFT gives Spectorgram
3 axes
Y: Freq., X: Time, Color variation: Magnitude
Mel Frequency Cepstral Coefficients (MFCC)
Timbral/textural features of sound
Frequency domain feature
Approx. human auditory system
13-40 coeffs.
Calc. at each frame
Humans are able to detect piano vs violin playing same pitch/freq.
