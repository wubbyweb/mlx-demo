# MLX-Audio 🔊

**MLX-Audio** is a fast and efficient library for audio generation and processing, built using [Apple's MLX](https://github.com/ml-explore/mlx) framework. It supports Text-to-Speech (TTS), Speech-to-Text (STT), and Speech-to-Speech (STS) tasks, optimized for Apple Silicon (M1–M4).

## ✨ Features

- 🚀 Built on MLX for Apple Silicon acceleration
- 🗣️ Text-to-Speech (TTS)
- 🎧 Speech-to-Text (STT)
- 🔁 Speech-to-Speech (STS)
- 🌐 REST API and Web UI with 3D audio visualization
- 🧠 Quantized model support
- 📦 Local processing for privacy

## 🛠️ Installation

First, ensure Python 3.8+ is installed.

```bash
pip install mlx-audio
```

For optional features like web UI and REST API:

```bash
git clone https://github.com/Blaizzy/mlx-audio
cd mlx-audio
pip install -r requirements.txt
```

## 🚀 Usage

### Text-to-Speech from CLI

```bash
python -m mlx_audio.tts.generate --text "Hello, world" --output hello.wav
```

### Text-to-Speech from Python

```python
from mlx_audio.tts.generate import generate_audio

generate_audio(text="Hello, world", output_path="hello.wav")
```

### Running the Web UI

```bash
python app.py
```

Then open your browser at `http://localhost:7860`.

## 📄 License

MIT License

---

Made for Apple Silicon with ❤️ using [MLX](https://github.com/ml-explore/mlx).

