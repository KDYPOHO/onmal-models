# Onmal optional model packs

Versioned, optional offline text translation assets for Onmal. The Onmal app is distributed separately through Steam.

## M2M100 418M INT8 1.0.0

This experimental pack contains M2M100 weights converted to INT8, a SentencePiece tokenizer, and 22 unmodified Noto font files. A compatible native CTranslate2 worker is required; end users do not need Python or an API key.

- Download: 477,535,844 bytes.
- Installed files: 518,690,560 bytes. The app requires additional temporary download and extraction space.
- SHA256: `d20724adde0110ca151a41bf73904271da4dd9a2e3dca11fd648d29e0cb01a38`.
- Model revision: `55c2e61bbf05dfb8d7abccdc3fae6fc8512fd636`.
- Model license: MIT. Font licenses: SIL OFL 1.1. Full notices and source provenance are included.

Download only from the versioned [release](https://github.com/KDYPOHO/onmal-models/releases/tag/m2m100-418m-int8-1.0.0). Onmal checks the archive and each declared file before atomically activating a pack. It preserves the previous installation on failure.

**Translation quality is not yet validated.** Selectable languages are not a promise of voice recognition support or quality. Korean-English Marian translation remains the default. Regional language variants may require a personal API. This repository does not contain user audio, personal API keys or application signing credentials.
