# Lucy Edit Dev - Gradio WebUI

This repository provides a Jupyter Notebook that creates a Gradio web interface for the Lucy-Edit-Dev model, an open-source instruction-guided video editing tool. It allows users to perform edits such as clothing changes, character replacements, object insertions, and scene transformations via text prompts.

Note: This is only a web interface; the original model is available at https://huggingface.co/decart-ai/Lucy-Edit-Dev.

## Installation

Install dependencies:
```
pip install git+https://github.com/huggingface/diffusers
pip install gradio torch torchvision torchaudio
pip install pillow opencv-python imageio-ffmpeg
pip install accelerate transformers
```

## Usage

1. Run the notebook in a Jupyter environment (e.g., Google Colab).
2. Upload a video and provide an edit prompt.
3. Adjust settings like number of frames, resolution, and guidance scale.
4. Click "Edit Video" to generate the output.

For best results, use detailed prompts (20-30 words) with trigger words like "Change", "Replace", or "Transform to".

## Requirements

- Python 3.12+
- CUDA-enabled GPU recommended for performance (falls back to CPU).

## License

MIT License.
