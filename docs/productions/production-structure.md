# Production Structure

Production structure defines how your show is organized — its acts, scenes, songs, transitions, and intermissions. This structure is used throughout ScriptMagic for [character](characters.md) tracking, page references, and [cue](../annotations/cues.md) organization.

## Structure types

### Acts

The top-level divisions of your show. Each act includes:

- Act number
- Page number (links to the script)
- Duration
- Production team notes
- Characters involved

### Scenes

Sections within acts, typically representing a location or unit of action. Each scene includes:

- Scene number and name (e.g., "Scene 2 — The Emerald City")
- Page number
- Location
- Duration
- Production team notes
- Characters involved

### Songs / Music numbers

Individual musical pieces, either standalone or nested within scenes. Songs include:

- Music number and title
- Page number and vocal score page
- Music link (for audio playback)
- Choreography videos
- Duration
- Production team notes
- Characters involved

### Intermissions

Breaks between acts. Include page number and duration.

### Transitions

Technical moments like set changes or blackouts. Each transition includes:

- Name and description
- Page number
- Duration
- Departments involved
- Cue trigger
- Notes

## Creating structure items

Click the **Create** button for the type you want (act, scene, song, etc.). Items are auto-numbered when created (Act 1, Scene 1, etc.) and can be renamed.

Structure items support parent-child relationships:

- **Acts** can contain scenes
- **Scenes** can contain songs and transitions

## Page links

Each structure item can have a **page number** that links directly to that page in your script. Click the page number to jump there.

!!! tip
    If your PDF has cover pages or front matter, set the **pages before script page 1** offset in your [production settings](creating-and-managing-productions.md) so page numbers align correctly.

## Team notes

Production team notes on structure items are visible to production admins and team members. They're useful for coordination notes, technical requirements, or reminders.

## Breakdown reports

The Reports button in the script view toolbar opens a multi-tab reporting dialog. Reports are available to Production Team and Admin roles.

### By Character

A grid showing characters (rows) vs. scenes and songs (columns). The header follows your production hierarchy with acts, scenes, and songs grouped together. Useful for conflict checking and tracking who's on stage at the same time. Exportable to CSV.

### By Cast Member

The same breakdown organized by person rather than character — shows all the characters each cast member plays and which scenes they're in. Exportable to CSV.

### Cue List

A spreadsheet view of all [cues](../annotations/cues.md) with sortable columns, column-based filtering, and inline editing. Columns include cue number, text, page, layer, associated cue number, notes, moment, and author info. Exportable to CSV.

### Cut Cues

Lists all [cut cues](../annotations/cues.md#cut-cues) across the production. You can remove individual cut cues or use "Remove All" to clear them in batch.

### Cast Sheets

Per-person script excerpts showing each cast member's scenes with page numbers, entrance/exit notes, and structure context. Exportable as individual PDFs or a batch PDF of all cast sheets.
