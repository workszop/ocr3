# Document OCR (LightOnOCR-3, WebGPU)

Drop a scan, photo or PDF and read it into Markdown with LightOnOCR-3-0.8B, running entirely in your browser on the GPU. Nothing is uploaded.

**Live:** https://workszop.github.io/ocr3/

## Requirements

- A recent Chrome or Edge with WebGPU enabled.
- About 850 MB of download on first use, cached by the browser afterwards.

## Choosing the model

On first use the page offers two sources:

- **Load from Hugging Face:** downloads the model from [andrzej/LightOnOCR_webGPU](https://huggingface.co/andrzej/LightOnOCR_webGPU). The choice is remembered.
- **Choose model folder:** uses a local copy of the `LightOnOCR-3-0.8B-ONNX` folder.

## Credits

The model is [LightOnOCR-3-0.8B](https://huggingface.co/lightonai/LightOnOCR-3-0.8B) by LightOn (Apache-2.0). The browser build uses [transformers.js](https://github.com/huggingface/transformers.js) and [pdf.js](https://mozilla.github.io/pdf.js/).
