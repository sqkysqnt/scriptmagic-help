# Cues

Cues are specialized annotations designed for tracking technical and performance cues on a script. Each cue is made up of two linked parts: a **moment** marking where something happens in the script, and a **cue text box** describing what the cue is (e.g., "LX 42 GO", "SFX Thunder").

## Parts of a cue

- **Moment** — A highlight on the script page marking the exact point where the cue occurs
- **Cue text box** — A text label describing the cue
- **Connector line** — A line linking the moment to the cue text box

The cue text box can appear on the left or right side of the moment, and the connector can attach to the top or bottom.

## Creating a cue

1. Make sure your active [layer](understanding-layers.md) is a **cue layer** (configured in layer settings)
2. Place a moment highlight on the script page where the cue occurs
3. Add the cue text box with the cue description
4. The connector line links the two parts automatically

!!! note
    A layer must be marked as a "cue layer" in its settings before you can create cues on it. See [Cue layers](#cue-layers) below.

## Cue prefixes

When you create a cue layer, ScriptMagic automatically derives a **cue prefix** from the layer name. The prefix is used to auto-number cues (e.g., "LX 1", "LX 2" for a lighting layer, "SQ 1" for a sound layer).

Built-in keyword mappings:

| Layer name keyword | Prefix |
|---|---|
| Lights, Lighting, Lamp | LX |
| Sound, SFX | SQ |
| Video, Projection, Screen | VID |
| Fly, Flying, Rigging, Rail | FLY |

If no keyword matches, the default prefix **Q** is used. These mappings can be customized by site administrators.

## Cue view modes

Cues can be displayed in two view modes:

- **Design mode** — Shows the full cue text box with connector line, ideal for editing and placement
- **Summary mode** — A compact view for reviewing cues alongside the script

## Cue list panel

The cue list panel provides an overview of all cues across your cue layers. From here you can:

- **View all cues** in a sortable list
- **Edit cue text** directly from the list
- **Navigate to a cue** by clicking it — the script jumps to that page
- **Filter by layer** to focus on specific cue types (e.g., just lighting cues)
- **Sort** by page, text, or modification date
- **Export / Import** cues as CSV for external tracking

!!! tip
    The cue list is a great way to review all your cues in order without scrolling through every page of the script.

## Cue layers

A layer must be marked as a "cue layer" in its settings for its cues to appear in the cue list panel. This lets you separate different types of cues (lighting, sound, video, etc.) into their own layers while still seeing them all together in the cue list.

See [Understanding Layers](understanding-layers.md#cue-layers) for more on how cue layers work.

!!! tip
    Create separate cue layers for each department (e.g., "Lighting Cues", "Sound Cues", "Video Cues"). The layer name is matched against keywords to auto-assign the correct cue prefix.

## Cue styling

Cue appearance is configured per layer:

- **Moment color** — the highlight color and opacity for the moment marker
- **Text box** — background color, text color, font, and size for the cue label
- **Connector** — attachment point (top or bottom of the moment)
- **Line-only mode** — show the moment as a line instead of a filled highlight

## Permissions

Cues follow the same permission model as other annotations. You need edit access to a layer to create or modify cues on it. Cue export is available to **Production Team** and **Production Admin** roles. See [Roles & Permissions](../collaboration/roles-and-permissions.md).
