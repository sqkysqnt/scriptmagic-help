# Understanding Layers

Layers are the organizational backbone of annotations in ScriptMagic. Every highlight, note, cue, and tag belongs to a layer. Layers control who can see and edit annotations, and let you keep different types of markup separate.

## How layers work

Think of layers like transparent sheets stacked on top of your script. Each layer holds its own set of annotations, and you can show or hide individual layers to control what's visible.

Your **active layer** determines where new annotations are placed. When you create a highlight, note, or cue, it goes on whichever layer is currently selected.

## Layer visibility types

Each layer has a visibility setting that controls who can see and edit it:

| Visibility | Who can see it | Who can edit it |
|---|---|---|
| **Me** | Only you | Only you |
| **Production** | Everyone in the production | Production team members |
| **Design** | Production team only | Production team members |
| **Personal** | Production team only | Only the creator |

- **Me** layers are private — perfect for personal notes that no one else needs to see.
- **Production** layers are shared with everyone — use these for information the whole cast and crew should see.
- **Design** layers are visible to the production team only — useful for technical notes that don't need to go to the cast.
- **Personal** layers let team members see your work without being able to edit it.

## System layers

Every production has three built-in system layers:

- **Music** — Contains music tags
- **Videos** — Contains video tags
- **Blocking** — Contains blocking tags

System layers cannot be renamed, deleted, or used for highlights. They're always at the production visibility level.

## Showing and hiding layers

Toggle the eye icon next to any layer to show or hide it. This only affects your view — other users' visibility preferences are independent.

Hidden layers and their annotations won't appear on the script or in exports.

## Creating a layer

1. Open the Layers panel in the script view
2. Click the add button to create a new layer
3. Set the layer name, visibility, and styling options

## Layer styling

Each layer has configurable styling that applies to all annotations on that layer:

- **Highlight color and opacity** — the default color for new highlights
- **Border** — optional border color and width
- **Text styling** — font, size, bold/italic/underline for text notes
- **Cue styling** — moment color, cue text appearance, connector position (for cue layers)

## Cue layers

Any layer can be marked as a **cue layer** in its settings. When enabled, cues on that layer appear in the [cue list panel](cues.md), making it easy to track cues across the script.

## Permissions

- You can always edit layers you created
- Production team members can edit **Production** and **Design** visibility layers
- **Me** and **Personal** layers can only be edited by their creator
- If you don't have edit access to a layer, you can still view its annotations (if the visibility allows it) but you can't modify them
