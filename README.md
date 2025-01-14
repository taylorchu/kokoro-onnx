# Kokoro TTS ONNX

ONNX optimized version of [hexgrad/Kokoro-82M](https://huggingface.co/hexgrad/Kokoro-82M), a frontier Text-to-Speech model with only 82 million parameters.

## Features

- Cleaner ONNX exports through PyTorch module rewrites
- Optimized model size using [inisis/OnnxSlim](https://github.com/inisis/OnnxSlim)
- Standardized input/output tensor names for compatibility with official ONNX exports

## Model Files

| Filename            | Description                        |
| ------------------- | ---------------------------------- |
| `kokoro.onnx`       | FP32 precision model               |
| `kokoro-quant.onnx` | Mixed precision model (uint8/int8) |

## Usage

This optimized ONNX version is currently being used by [thewh1teagle/kokoro-onnx](https://github.com/thewh1teagle/kokoro-onnx).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Links

- Original Model: [hexgrad/Kokoro-82M](https://huggingface.co/hexgrad/Kokoro-82M)
- ONNX Optimization Tool: [inisis/OnnxSlim](https://github.com/inisis/OnnxSlim)
- Implementation Example: [thewh1teagle/kokoro-onnx](https://github.com/thewh1teagle/kokoro-onnx)
