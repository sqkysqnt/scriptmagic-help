# Blocking Thumbnails

Blocking thumbnails are small preview images that give you a quick visual reference of each blocking map without opening the [editor](the-blocking-editor.md).

## Where thumbnails appear

- **Blocking list** — In the blocking panel's sidebar, each blocking map shows a thumbnail alongside its title and page number
- **Blocking tags** — When a blocking map is placed on a script page as a [tag](../annotations/tags.md#blocking-tags), the thumbnail appears as a clickable preview card
- **Exports** — Thumbnails can be included in [exported PDFs](../collaboration/sharing-and-exporting.md#exporting-a-script) as inline thumbnails or full blocking pages

## How thumbnails are generated

Thumbnails are created automatically every time you save a blocking map. The system captures a snapshot of the canvas — including all visible [character stickers](character-stickers.md) and the background image — and saves it as a preview image.

You don't need to do anything to generate or update thumbnails. They refresh automatically with each save.

## What's included

Thumbnails show:

- All character stickers on visible layers
- The background image (if present) with any transformations applied

Thumbnails do **not** include the editor's toolbar, sidebar, or metadata fields — just the canvas content.

## If a thumbnail doesn't appear

If a blocking map shows a gray placeholder instead of a thumbnail, it means the thumbnail hasn't been generated yet (for example, if the map was just created). Make an edit and save, and the thumbnail will appear.
