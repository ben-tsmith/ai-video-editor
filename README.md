# AI Video Editor

An AI-powered video editing tool that transforms natural language prompts into video edits using OpenShot.

## Status

**Early Development** - This project is just getting started!

## Vision

Instead of manually configuring video timelines, users will describe what they want:
- "Make this clip cinematic"
- "Add a fade transition between clips" 
- "Remove the background from this video"

The tool will interpret these prompts and use OpenShot's powerful video processing engine to make the edits.

## Development Setup

This project is being built step-by-step. Current focus: Setting up the core OpenShot integration.

```bash
# Clone the repository
git clone https://github.com/ben-tsmith/ai-video-editor.git
cd ai-video-editor

# Install in development mode (when ready)
pip install -e .
```

## Architecture

- **Core**: OpenShot/libopenshot integration for video processing
- **AI**: Natural language prompt interpretation  
- **CLI**: Command-line interface for users
- **Effects**: Modular video effects and filters

## Planned Features

This project is designed with extensibility in mind. Once the core AI-powered timeline editor is stable, the following capabilities are planned:

- **Generative Media Integration**
  - Use external models (e.g. Pika, Sora, Stability, MusicGen) to generate video, audio, or images on demand based on prompts
  - Automatically import these assets into the editing timeline

- **Prompt-Driven Scene Construction**
  - AI will interpret prompts like "add a sunset B-roll" and fetch/generate fitting content
  - Timeline edits (keyframes, transitions, effects) applied automatically

- **Automatic Asset Management**
  - Group assets by type and purpose (intro, B-roll, background music)
  - Reuse or regenerate media based on style or context

- **Multimodal Prompting**
  - Accept text, audio, or video prompts to drive edits or generate scenes

These features will make the tool a hybrid between a creative assistant and a full-featured programmatic video editor — bridging AI generation with structured editing logic.

---

Built with [OpenShot](https://www.openshot.org/) and Python.