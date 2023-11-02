Sound Signal Denoising using Wavelet Transform
Overview
This MATLAB application is designed for denoising audio signals using wavelet transform. It provides a user-friendly interface for loading audio files, adding various types of noise, and applying denoising techniques. The implemented denoising methods include:

White Gaussian Noise: Add white Gaussian noise to the original audio signal.
Uniform Noise: Add uniform noise to the original audio signal.
Impulsive Noise: Add impulsive noise to the original audio signal.
How it Works
The application loads an audio file (in formats like .wav, .mp3, .ogg, .flac) and displays the original waveform. Users can then choose to add different types of noise, visualize the noisy waveforms, and denoise using wavelet transform.

Components
Original Voice: Load an audio file and play the original sound.
White Gaussian Noise: Add white Gaussian noise to the original audio and denoise.
Uniform Noise: Add uniform noise to the original audio and denoise.
Impulsive Noise: Add impulsive noise to the original audio and denoise.
Denoising Techniques
Wavelet Transform: Utilizes the Coiflet 5 wavelet and applies a 10-level wavelet packet decomposition. Thresholding is used for denoising.
Usage
Click on "Load Voice" to select an audio file.
Use the respective buttons to add different types of noise.
Click "Denoise" to apply the denoising technique.
Getting Started
To get started with this project, simply clone the repository and run the MATLAB application. Ensure you have MATLAB installed on your system.

Additional Notes
The denoised waveforms are displayed in real-time, allowing users to hear the effects of denoising.
The project utilizes various signal processing techniques for denoising, providing a practical demonstration of wavelet transform.
