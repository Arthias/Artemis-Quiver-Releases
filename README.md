# Artemis Quiver — Extension Releases

Downloadable builds of the **Artemis Quiver** Chrome extension (MV3). This repo holds packaged zips only — the source stays private.

Each release tag (`vX.Y.Z`) has a [GitHub Release](https://github.com/Arthias/Artemis-Quiver-Releases/releases) with a downloadable `Artemis_Quiver_extension-vX.Y.Z.zip` and changelog notes.

## What it does

Paste/import job postings → AI-powered match score against your profile, CV optimization, and cover letter drafts. All data stays in your browser (IndexedDB) unless you export.

## Install

1. Download the latest `Artemis_Quiver_extension-vX.Y.Z.zip` from [Releases](https://github.com/Arthias/Artemis-Quiver-Releases/releases).
2. Unzip it. You'll get an `Artemis_Quiver_extension/` folder.
3. Open Chrome → `chrome://extensions` → enable **Developer mode** (top-right).
4. Click **Load unpacked** → select the `Artemis_Quiver_extension/` folder.
5. The extension (and its companion web app) are now installed. Pin the extension to the toolbar.

## First-run requirements

- **Open the Artemis Quiver web app once** in a tab and leave it open. The extension needs the app tab for profile fingerprint generation and error reporting.
- **Configure an LLM** in the app's Settings — pick one of:
  - **Local**: LM Studio / Ollama on your machine, or
  - **WebLLM**: download a model that runs entirely in-browser (WebGPU), or
  - **Cloud**: OpenAI / Anthropic / Gemini API key.
- The overlay works on LinkedIn and other configured job sites.

## Updating

- Re-download the newest zip from [Releases](https://github.com/Arthias/Artemis-Quiver-Releases/releases), unzip, and **Remove** the old extension at `chrome://extensions`, then **Load unpacked** the new folder again. (There is no auto-update for Load-unpacked builds.)

## Feedback

Beta — expect rough edges. Report issues with steps to reproduce.
