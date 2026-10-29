# Spectrum Bench

A live FFT spectrum analyzer that runs in the browser. Open it at https://drdraxi.github.io/spectrum-analyzer/

- Sources: microphone (with device picker and raw-input option), audio files, and test signals (sine, square, saw, triangle, two-tone, log sweep, white and pink noise)
- Views: spectrum (log or linear frequency, dBFS), scrolling spectrogram, waveform
- Freeze and scrub back through recent frames; zoom and pan both axes with wheel, drag or pinch
- Cursor readout of frequency, level, note and cents; A/B markers with interval and level difference
- Peak detection with note names, peak hold with decay, pitch estimate with a tuner gauge
- Raw sample table for the current frame
- Settings for FFT size, window, smoothing, dB range, peak threshold and prominence, A4 reference
- Export the frame as spectrum, samples or peaks CSV, or as a PNG

Everything is one self-contained `index.html`; audio never leaves the browser.
