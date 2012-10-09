sndfile2fft
===========

Take a wav file an generates FFT data.

This is a simple application I hacked together while testing USB Audio Interfaces.

It takes a wav file, runs an FFT, plots the output (using gnuplot), just some simple checks for glitches (expects sine waves)

Requirements
-------------
  * Gnuplot for generating plots
  * libsndfie (Version used 1.0.25)
  * fftw

TODO
----
  * Only for stereo really
  * Could do with command line options for the various options
  * Very hacky! 