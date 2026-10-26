# tsuzuna-models

Offline translation model files for Tsuzuna's translator mode. Nothing here is original work of
this repository: the release assets are a CTranslate2 (int8) conversion of
[staka/fugumt-ja-en](https://huggingface.co/staka/fugumt-ja-en) (FuguMT, Japanese to English),
licensed [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) by its author.
The converted files are shared under the same licence.

| release | files |
| --- | --- |
| `fugumt-ja-en-ct2-v1` | `model.bin`, `shared_vocabulary.json`, `source.spm`, `target.spm`, `config.json` |

Tsuzuna downloads these on first use and verifies each file's SHA-256.
