# zcuts-models

Download files for ZCuts. ZCuts fetches optional speech models from this
repo's Releases (Settings > Models) and checks every file's SHA-256 before
keeping it. The models that come with the installer (base, small) are not
here.

| Release tag | What | Source (pinned) |
|---|---|---|
| whisper-tiny | Whisper tiny for faster-whisper | Systran/faster-whisper-tiny @ d90ca5fe26 |
| whisper-medium | Whisper medium for faster-whisper | Systran/faster-whisper-medium @ 08e178d487 |
| whisper-large-v3-turbo | Whisper large-v3-turbo for faster-whisper | dropbox-dash/faster-whisper-large-v3-turbo @ 0a363e9161 |

Licence of the Whisper models: MIT (licenses/LICENSE-whisper.txt), copyright
OpenAI; converted to CTranslate2 by their Hugging Face publishers.

To publish or refresh: Actions > Publish models > Run workflow.
