# Sight Buddy - on-device speech model files

Model files downloaded at runtime by the [Sight Buddy](https://www.drophouse.uk/products/sightbuddy) Android accessibility app for fully local, offline speech-to-text. No audio ever leaves the device.

## Contents (release assets)

| File | Purpose | Source | License |
|------|---------|--------|---------|
| `base.en-encoder.int8.onnx` / `base.en-decoder.int8.onnx` / `base.en-tokens.txt` | Whisper base.en (int8 quantized) | [OpenAI Whisper](https://github.com/openai/whisper), ONNX export by [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) | MIT (Whisper), Apache-2.0 (export) |
| `silero_vad.onnx` | Voice activity detection | [Silero VAD](https://github.com/snakers4/silero-vad) | MIT |

These files are unmodified redistributions of the sherpa-onnx published conversions, hosted here for stable download URLs and versioning.