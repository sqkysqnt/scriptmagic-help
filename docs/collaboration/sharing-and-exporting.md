# Sharing & Exporting

ScriptMagic lets you export your annotated script as a PDF to share with others or print for rehearsals. The export includes your annotations, cues, and blocking maps based on your selected layers and variant.

## Exporting a script

1. Open the export dialog from the script view
2. Configure your export settings:

**Variant:**

Select which [script variant](../scripts/script-variants.md) to export. This determines the page order and which pages are included.

**Layers:**

Choose which [layers](../annotations/understanding-layers.md) to include in the export. Only layers you have permission to view are available. Hidden layers are excluded by default.

**Page range:**

Export the entire script (default) or specify a custom page range.

**Annotations:**

Toggle which annotation types to include:

- **[Highlights](../annotations/highlights.md)** — colored overlays with their configured colors and opacity
- **[Text notes](../annotations/notes.md)** — text boxes with styling preserved
- **[Cues](../annotations/cues.md)** — moment markers and cue text boxes with connector lines (available to Production Team and Admin roles)
- **Author info** — optionally include created by / modified by information on cues

**Blocking maps:**

Choose how [blocking maps](../blocking/the-blocking-editor.md) are included in the export:

- **None** — no blocking content
- **Inline thumbnail** — small [thumbnails](../blocking/blocking-thumbnails.md) drawn on script pages at their tag positions
- **Insert after page** — full blocking pages inserted after each script page that has blocking tags
- **All at end** — all blocking pages appended at the end of the export

3. Generate the export — a progress dialog shows the rendering status

## Sharing

After the PDF is generated:

- On **mobile** (iOS/Android), the system share sheet opens so you can send via email, messaging, AirDrop, or save to files
- On **desktop** (web, macOS, Windows, Linux), the PDF is saved to your downloads

ScriptMagic doesn't have built-in sharing links — you share the exported PDF through whatever channel works best for your team (email, cloud storage, messaging, etc.).

## What's included in the export

The exported PDF respects the same [layer permissions](../annotations/understanding-layers.md#permissions) as the in-app view:

- You'll only see layers your [role](roles-and-permissions.md) has access to
- **Me** layers include only your own private annotations
- **Design** layers are only available to production team members
- **Production** layers are available to everyone

!!! tip
    To create a clean export for the cast (without technical cues), hide your cue and design layers before exporting, or only select Production-visibility layers.
