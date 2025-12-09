Per installare gemini-cli:
- per macos:
```bash
brew install gemini-cli
```
- per windows:
```bash
choco install gemini-cli
```

Se vuoi poter anche creare immagine
```bash
gemini extensions install https://github.com/gemini-cli-extensions/nanobanana
```
dovrai seguire questi step per autenticarti:
https://github.com/google-gemini/gemini-cli/blob/main/docs/get-started/authentication.md#use-gemini-api-key

1. ottieni una API key da https://aistudio.google.com/app/apikey
2. esegui il comando:
```bash
export GEMINI_API_KEY="YOUR_GEMINI_API_KEY"

```