# Cues

Cues are specialized annotations designed for tracking technical and performance cues on a script. Each cue is made up of two linked parts: a **moment** marking where something happens in the script, and a **cue text box** describing what the cue is.

## Parts of a cue

- **Moment** — A highlight on the script page marking the exact point where the cue occurs
- **Cue text box** — A text label describing the cue (e.g., "LX 42 GO", "SFX Thunder")
- **Connector line** — A line linking the moment to the cue text box

The cue text box can appear on the left or right side of the moment, and the connector can attach to the top or bottom.

## Creating a cue

1. Make sure your active [layer](understanding-layers.md) is a **cue layer** (configured in layer settings)
2. Place a moment highlight on the script page where the cue occurs
3. Add the cue text box with the cue description
4. The connector line links the two parts automatically

## Cue list panel

The cue list panel provides an overview of all cues across your cue layers. From here you can:

- **View all cues** in a sortable list
- **Edit cue text** directly from the list
- **Navigate to a cue** by clicking it — the script jumps to that page
- **Filter by layer** to focus on specific cue types
- **Sort** by page, text, or modification date
- **Export / Import** cues as CSV for external tracking

## Cue layers

A layer must be marked as a "cue layer" in its settings for its cues to appear in the cue list panel. This lets you separate different types of cues (lighting, sound, video, etc.) into their own layers while still seeing them all together in the cue list.

## Cue styling

Cue appearance is configured per layer:

- **Moment color** — the highlight color and opacity for the moment marker
- **Text box** — background color, text color, font, and size for the cue label
- **Connector** — attachment point (top or bottom of the moment)
- **Line-only mode** — show the moment as a line instead of a filled highlight
