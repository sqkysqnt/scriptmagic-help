# Understanding Layers

Layers are the organizational backbone of annotations in ScriptMagic. Every [highlight](highlights.md), [note](notes.md), [cue](cues.md), and [tag](tags.md) belongs to a layer. Layers control who can see and edit annotations, and let you keep different types of markup separate.

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

- **Music** — Contains [music tags](tags.md#music-tags)
- **Videos** — Contains [video tags](tags.md#video-tags)
- **Blocking** — Contains [blocking tags](tags.md#blocking-tags)

System layers cannot be renamed, deleted, or used for highlights. They're always at the production visibility level.

## Showing and hiding layers

Toggle the eye icon next to any layer to show or hide it. This only affects your view — other users' visibility preferences are independent.

!!! tip
    Hidden layers and their annotations won't appear on the script or in [exports](../collaboration/sharing-and-exporting.md). Use this to control exactly what appears in your exported PDFs.

## Creating a layer

1. Open the Layers panel in the script view
2. Click the add button to create a new layer
3. Set the layer name, visibility, and styling options

## Layer styling

Each layer has configurable styling that applies to all annotations on that layer:

- **Highlight color and opacity** — the default color for new highlights
- **Border** — optional border color and strength (0.5–5.0)
- **Text styling** — font, size, bold/italic/underline, and text color for text notes
- **Cue styling** — moment color, moment style (highlight or line), cue text appearance, connector position, and default cue side (for cue layers)

Individual annotations can override their layer's styling — see [per-cue overrides](cues.md#per-cue-overrides) and [per-highlight overrides](highlights.md#per-highlight-format-overrides).

## Cue layers

Any layer can be marked as a **cue layer** in its settings. When enabled:

- Cues on that layer appear in the [cue list panel](cues.md#cue-list-panel)
- A **cue prefix** is auto-derived from the layer name (e.g., "LX" for "Lighting Cues")
- You can set a **default cue side** (left, right, or choice) to speed up cue placement
- You can configure a **default text** template for new cues

!!! tip
    Create separate cue layers for each department (e.g., "LX Cues", "SFX Cues", "Video Cues") to keep things organized while still seeing all cues together in the cue list.

## Sound DCA layers

A layer can be marked as a **Sound DCA layer** to enable sound mixing markers. When active, a DCA toolbar appears above the script view showing:

- **16 numbered DCA circles** (1–16) that you drag onto the script page to mark channel assignments
- A **Mic Cue (MC) marker** for placing microphone change points
- A **Clear page** button to remove all DCA markers from the current page

DCA layer settings let you configure:

- **Circle fill style** — filled or outline
- **Circle color and size**
- **Mic cue badge color and size**
- **Snap lane position** — the default horizontal position where DCA markers align

## Permissions

- You can always edit layers you created
- Production team members can edit **Production** and **Design** visibility layers
- **Me** and **Personal** layers can only be edited by their creator
- The **My Notes** layer is always locked to "Me" visibility and cannot be changed
- If you don't have edit access to a layer, you can still view its annotations (if the visibility allows it) but you can't modify them

See [Roles & Permissions](../collaboration/roles-and-permissions.md) for more on how roles affect what you can do.
