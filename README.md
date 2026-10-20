# Ín-Gờ-Lịt Mỗi Ngày: audio

Recordings the Ín-Gờ-Lịt Mỗi Ngày app downloads topic by topic. No app code lives here.

- `read/<topic>-<paragraph>.ogg`: the reading passage of each topic (Bài đọc), one file per paragraph, Opus mono.
  British voices bf_emma, bm_george and bf_isabella take turns by topic.
- `read/index.json`: a fingerprint of each paragraph's text.
- `manifest.json`: what the app can download, with sizes and fingerprints.

Made with the Kokoro-82M speech model (https://huggingface.co/hexgrad/Kokoro-82M), Apache License 2.0.
