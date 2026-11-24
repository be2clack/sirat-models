# sirat-models

Model files downloaded on request by the Sirat app (Quran, prayer, sunnah) for checking
Quran recitation on the phone. Nothing here is code; audio never leaves the phone.

## whisper-quran-base-v1

[tarteel-ai/whisper-base-ar-quran](https://huggingface.co/tarteel-ai/whisper-base-ar-quran)
(Apache-2.0, © Tarteel AI) converted to Core ML for
[WhisperKit](https://github.com/argmaxinc/WhisperKit) (MIT) with whisperkittools, fp16, unchanged weights.
Tokenizer: openai/whisper-base (MIT). Files are release assets with `/` written as `__`;
the app pins the sha256 of every file.

Licence of the model files: Apache License 2.0 — see LICENSE.
