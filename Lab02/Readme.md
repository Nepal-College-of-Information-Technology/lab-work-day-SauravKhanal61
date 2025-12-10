# Lab 02
## Title: Basic sound processing and manipulation using Python

---

## Objectives: 
1. Load and play a sample sound clip(drum.wav)
2. Process and manipulate audio signal
3. Perform audio synthesis using sine wave
4. Visualize audio waveform and spectrum properties

---

## Background Theory
* Sound and audio representation: 
Sound is a natural physical vibration that travels through air or other mediums, while audio is the electronic or digital representation of that sound. Sound becomes audio when microphones convert vibrations into electrical signals, and speakers turn audio signals back into sound we can hear. Simply put, sound is what we hear, and audio is how technology captures, stores, and reproduces that sound.

* Sampling and Quantization: Sampling is the process of taking regular snapshots of a continuous sound wave to capture its overall shape, while quantization converts those sampled values into fixed numerical levels so a computer can store them. Together, sampling and quantization transform real-world sound into digital audio that devices can process and save.

* PyDub: Pydub is a simple and easy-to-use Python library for audio processing tasks such as cutting, joining, converting, and editing sound files. It lets you work with audio almost like editing text, making it beginner-friendly and ideal for quick audio manipulation.

* Librosa: Librosa is a powerful Python library used for analyzing and processing audio, especially in music and speech applications. It provides tools for extracting features, visualizing sound, and performing advanced audio analysis, making it popular in machine learning and multimedia projects.

---

## Procedure
* Import the required libraries such as Pydub, Librosa, NumPy, and Matplotlib.
* Load the sample audio file (drum.wav) using either Pydub or Librosa.
* Then play it in Python to verify that it loaded correctly.
* After that, process and manipulate the audio by performing tasks like adjusting the volume, cutting or trimming sections, adding simple effects, or resampling and changing the playback speed.
* Analyze the audio signal by converting it into a waveform (time-domain plot).
* Compute and display the spectrogram using Librosa to observe its frequency content.
* Synthesize a simple audio signal—such as a sine wave—using NumPy and save it as a WAV file.
* Visualize the synthesized signal in both waveform and spectrogram form.
* Finally, save or export the processed audio using Pydub or Librosa.

---

## Output
* The audio file drum.wav was successfully loaded and played using Pydub/Librosa.
* The waveform plot displayed the time-domain representation of the audio signal clearly.
* A spectrogram was generated, showing the frequency distribution of the sound over time.
* A synthetic sine wave was created using NumPy and saved as a WAV file.
* Both the waveform and spectrogram of the synthesized signal were visualized successfully.
* The processed audio (trimmed, volume-adjusted, or resampled) was exported correctly using Pydub/Librosa.

---

## Conclusion
Basic sound processing and manipulation in Python allow us to load, edit, analyze, and transform audio using libraries like Pydub and Librosa. We can perform tasks such as trimming, merging, changing volume, extracting features, and converting audio formats, making it easy to handle sound in multimedia and machine-learning projects.
