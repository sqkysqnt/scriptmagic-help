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

If the layer has a **default cue side** set to Left or Right, the text box is placed on that side automatically. If set to "Choice", you'll be prompted to choose the side when creating the cue.

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

Cues can be displayed in two view modes, selectable from the cue list panel toolbar:

- **Design mode** — Shows the full cue text box with the prefix, number, and description on separate lines. Ideal for editing and placement. Text boxes auto-resize to fit their content.
- **Summary mode** — Shows only the prefix and number in a compact view. Useful for reviewing cues without the description text taking up space on the page.

## Cut cues

Cues can be marked as **cut** to indicate they've been removed from the show without permanently deleting them. Cut cues are visually distinct:

- The moment marker is shown at 50% opacity with a red diagonal strikethrough
- The cue text gets a red strikethrough
- An orange "CUT" badge appears in the cue list

To mark a cue as cut, click the scissors icon next to it in the cue list panel. Cut cues can be toggled back to active at any time. Use the **Hide Cut Cues** toggle in the cue list toolbar to hide them from the list view.

The **Cut Cue Report** (available from the [Reports](#reports) button) shows all cut cues across your production, with the option to remove them all at once.

## Linked and unlinked cues

Cues can be **linked** (placed on a specific page) or **unlinked** (created but not yet positioned on a page). Unlinked cues appear in the cue list with a red indicator and a "drag to place" instruction.

A single cue can appear on **multiple pages** — each page location stores its own position for the moment and text box independently. The cue list shows page badges for each location.

Use the **Hide Unlinked Cues** toggle in the cue list toolbar to focus only on cues that have been placed on pages.

## Cue list panel

The cue list panel provides an overview of all cues across your cue layers. From here you can:

- **View all cues** in a sortable list
- **Edit cue text inline** — double-tap a cue's text to edit it directly in the list
- **Edit cue numbers inline** — double-tap a cue number to change it
- **Navigate to a cue** by clicking it — the script jumps to that page
- **Filter by layer** to focus on specific cue types (e.g., just lighting cues)
- **Sort** by page number, cue number, cue text, layer, or modification date
- **Group by page** — toggle between a flat list and a page-grouped view
- **Toggle view mode** — switch between Design and Summary display
- **Hide unlinked cues** — show only cues that have been placed on pages
- **Hide cut cues** — show only active (non-cut) cues
- **Import / Export** cues as CSV — see [CSV import and export](#csv-import-and-export)

!!! tip
    The cue list is a great way to review all your cues in order without scrolling through every page of the script.

## CSV import and export

### Importing cues

Import cues from a CSV file into a selected layer. If the CSV includes a **Page Number** column, ScriptMagic will automatically link the imported cues to the matching script pages. After import, a summary shows how many cues were linked vs. unlinked.

### Exporting cues

Export cues to CSV with a customizable column selection. Available columns include:

- Cue Number, Text, Is Cut, Page Numbers, Layer, Notes, Moment, Associated Cue Number, Created By, Modified By, and more

Choose to export all layers or a single layer, and preview the output before downloading.

## Cue layers

A layer must be marked as a "cue layer" in its settings for its cues to appear in the cue list panel. This lets you separate different types of cues (lighting, sound, video, etc.) into their own layers while still seeing them all together in the cue list.

See [Understanding Layers](understanding-layers.md#cue-layers) for more on how cue layers work.

!!! tip
    Create separate cue layers for each department (e.g., "Lighting Cues", "Sound Cues", "Video Cues"). The layer name is matched against keywords to auto-assign the correct cue prefix.

## Cue styling

Cue appearance is configured per layer, with the option to override settings on individual cues:

### Layer defaults

- **Moment color** — the highlight color and opacity for the moment marker
- **Moment style** — show the moment as a filled highlight or a line
- **Moment border** — optional border with configurable color and strength
- **Text box** — background color, opacity, text color, font, size, and bold/italic/underline
- **Connector** — attachment point (top or bottom of the moment)
- **Default cue side** — whether new cues default to left, right, or prompt the user to choose

### Per-cue overrides

Individual cues can override their layer's default styling. Click the format button on a selected cue to adjust color, opacity, border, and text properties for just that cue. Overrides are shown with a badge count, and can be reset individually or all at once.

## Reports

The **Reports** button in the script view toolbar opens a multi-tab dialog with production reports:

- **By Character** — Grid showing which characters appear in which scenes and songs
- **By Cast Member** — Breakdown organized by person, showing all characters each person plays
- **Cue List** — Spreadsheet view of all cues with sortable columns, inline editing, and column filtering. Exportable to CSV.
- **Cut Cues** — Lists all cut cues with the option to remove them
- **Cast Sheets** — Per-person script excerpts with their scenes, exportable as individual or batch PDFs

## Permissions

Cues follow the same permission model as other annotations. You need edit access to a layer to create or modify cues on it. Cue export is available to **Production Team** and **Production Admin** roles. See [Roles & Permissions](../collaboration/roles-and-permissions.md).
