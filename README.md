# Hyper Sliced AI — "Stickman vs Giant Eraser"

Production repo for a ~45s hand-drawn pencil-sketch animated Short (no dialogue, pure pantomime + sound effects), in the style of pencil-gag channels.

## Pipeline
1. `01-concept/` — premise, character, rules of the world
2. `02-storyboard/` — shot-by-shot list with timing, hooks and on-screen text
3. `03-ai-prompts/` — copy-paste prompts for frames and motion
4. `04-sound/` — SFX and music cue sheet
5. `05-edit/` — edit guide, export settings
6. `06-upload/` — titles, thumbnail, description, tags, pinned comment
7. `07-growth/` — hook bank, next 5 episodes, posting schedule
8. `checklists/` — approval + upload checklist (final gate)

## Media
Put generated media in `assets/` (frames, clips, audio, thumbnails, exports). Large files stay out of git (see `.gitignore`).

## Workflow
Concept -> Storyboard -> Generate frames -> Animate -> Sound -> Edit -> Approve (`checklists/approval.md`) -> Upload (`06-upload/upload-package.md`).
