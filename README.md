<p align="center">
  <img src="./assets/icon.png" alt="Replicator app icon" width="112" height="112">
</p>

<h1 align="center">Replicator</h1>

<p align="center">
  <strong>Codex for physical products.</strong>
</p>

<p align="center">
  Turn a hardware idea into prototype-ready mechanical, electrical, and manufacturing work.
</p>

<p align="center">
  <a href="./README.md">English</a> |
  <a href="./README.zh-CN.md">简体中文</a> |
  <a href="./README.ja.md">日本語</a>
</p>

<p align="center">
  <a href="https://github.com/XONAR-LABS/replicator-release/releases/latest">Download the latest macOS release</a>
</p>

> [!IMPORTANT]
> Current public builds target **macOS Apple Silicon**.
> Windows, Linux, Intel macOS, and Universal macOS builds are not published yet.

<br>

## What Is Replicator?

Replicator is an AI workspace for people building physical products.

Describe what you want to make, and Replicator helps move the work forward:
from a rough idea to a structured product plan, parts decisions, mechanical
design outputs, electrical and PCB work, manufacturing handoff files, and the
next fabrication steps.

It is designed for founders, makers, hardware teams, and product builders who
want to spend less time jumping between separate design tools, vendor portals,
spreadsheets, and device workflows.

## Screenshots

<p>
  <img src="./assets/screenshots/replicator-cad-model.png" alt="Replicator CAD model workspace" width="100%">
</p>

<p>
  <img src="./assets/screenshots/replicator-pcb-placement.png" alt="Replicator PCB placement review" width="100%">
</p>

<p>
  <img src="./assets/screenshots/replicator-gerber-preview.png" alt="Replicator Gerber preview" width="100%">
</p>

## What Replicator Helps You Do

- Turn a product idea into a clear build plan.
- Explore components, constraints, product decisions, and next steps with an AI
  product engineer.
- Work through mechanical structure, electrical design, PCB planning, and
  prototype constraints in one flow.
- Prepare design, electrical, and manufacturing handoffs for prototype work.
- Organize generated files, decisions, and iterations inside one local project.
- Prepare work for manufacturing services such as JLCPCB and Huaqiu, where
  supported.
- Move suitable fabrication tasks toward desktop manufacturing devices such as
  Bambu Lab printers, where supported.

Replicator is not just a drawing tool. It helps with the practical work between
"I want to build this" and "I have something I can prototype, order, or make."

## Install

1. Open the
   [latest release](https://github.com/XONAR-LABS/replicator-release/releases/latest).
2. Download the `.dmg` asset.
3. Open the disk image and drag **Replicator** into **Applications**.
4. Launch Replicator and create or open a project folder.

Release pages may also include `.zip`, `.blockmap`, and `latest-mac.yml` files.
Most users should install from the `.dmg`; the other files support packaged
updates and release metadata.

> [!NOTE]
> The first launch may take longer because Replicator prepares its local
> fabrication runtime. Keep the app open until setup finishes.

## Requirements

- Mac with Apple Silicon
- Internet access for download, first-run setup, and AI model calls
- A configured model provider or connected Codex app, depending on the workflows
  you use

For best results, use a strong reasoning model where available.

## Privacy and Local Files

Replicator stores project files in the project folder you choose. Generated
files, artifacts, and project logs remain on your machine unless you share or
sync that folder yourself.

AI model requests are sent to the model provider you configure.

## Support

Found a bug or need help with a release? Open an issue in the
[Replicator release repository](https://github.com/XONAR-LABS/replicator-release/issues)
with your app version, macOS version, what you were trying to do, and any
relevant error message.

## Release Notes

Each GitHub release includes the versioned app assets and generated release
notes. For changes, fixes, and known limitations, read the notes attached to the
specific version you download.
