# Aria Development Repository

> 🚧 **Development Branch** - main development repository for Aria

## About Aria

Aria provides audio feature extraction and speech utilities.

## 🔧 Development Status

This repository is under active development. Many features are TODO.

### 🔴 High Priority TODOs

- Core functionality is still being implemented across modules.

### 📝 Complete TODO List

- [ ] **aria/features/mfcc.py:2** - cache mel filterbanks per sample rate
- [ ] **aria/features/mfcc.py:3** - support delta and delta-delta coefficients
- [ ] **aria/features/spectrogram.py:2** - add windowing function selection
- [ ] **aria/features/spectrogram.py:6** - vectorize the mel projection loop
- [ ] **aria/features/spectrogram.py:7** - expose configurable number of mel bands
- [ ] **aria/io/loader.py:2** - auto-resample to a target sample rate
- [ ] **aria/io/loader.py:3** - handle multi-channel downmixing
- [ ] **aria/models/asr.py:3** - integrate beam search decoding

## 🤝 Contributing

1. Pick a TODO item from the list above
2. Implement the functionality
3. Update this README when TODOs are completed
