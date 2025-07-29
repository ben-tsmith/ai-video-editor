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

## Architecture (Planned)

- **Core**: OpenShot/libopenshot integration for video processing
- **AI**: Natural language prompt interpretation  
- **CLI**: Command-line interface for users
- **Effects**: Modular video effects and filters

---

Built with [OpenShot](https://www.openshot.org/) and Python.