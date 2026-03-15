# Volume Modifier

## 📖 Description
This program modifies the volume of a `.wav` audio file by multiplying or dividing each audio sample by a scaling factor. It preserves the original hesader and outputs a new `.wav` file with the adjusted volume.

## ⚙️ How to Run
```bash
make volume
./volume input.wav output.wav factor

- input.wav: original audio file
- output.wav: new audio file
- factor: scaling factor (e.g., 0.5 to halve volume, 2.0 to double volume)

## 🧪 Example
```bash
./volume song.wav louder.wav 2.0

This doubles the volume of song.wav and saves it as louder.wav

## 🎯 Skills Learned
- File I/O in C
- Understanding WAV file structure
- Command-line arguments
- Audio data manipulation
