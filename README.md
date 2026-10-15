# odyn-editor-assets

Espelho de arquivos públicos usados pelo editor de vídeo do Odyn, para máquinas
cuja rede só libera gerenciadores de pacote (GitHub, PyPI, npm).

Nenhum código ou conteúdo do Odyn está aqui — só cópias exatas de arquivos de
terceiros, nos releases.

## Releases

### `faster-whisper-medium-08e178d`

Modelo de transcrição Whisper *medium* convertido para CTranslate2, cópia exata de
[Systran/faster-whisper-medium](https://huggingface.co/Systran/faster-whisper-medium)
na revisão `08e178d48790749d25932bbc082711ddcfdfbc4f`.

| Arquivo | SHA-256 |
|---|---|
| `model.bin` | `9b45e1009dcc4ab601eff815b61d80e60ce3fd8c74c1a14f4a282258286b51ae` |
| `config.json` | `3622a2ddc41ec0e0fd4e68c13c6830f03b90c38d89aaad184de02c8c642cf807` |
| `tokenizer.json` | `fb7b63191e9bb045082c79fd742a3106a12c99513ab30df4a0d47fa6cb6fd0ab` |
| `vocabulary.txt` | `34ce3fe1c5041027b3f8d42912270993f986dbc4bb34cf27f951e34a1e453913` |

Créditos: pesos do [Whisper](https://github.com/openai/whisper) (OpenAI, licença
MIT); conversão para CTranslate2 por [Systran](https://huggingface.co/Systran)
(licença MIT). Ver `LICENSE`.
