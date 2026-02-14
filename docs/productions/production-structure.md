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

## Breakdown report

The breakdown report provides a summary of your production structure with character assignments. It shows which characters appear in which scenes and songs — useful for:

- Conflict checking (who's on stage at the same time)
- Costume quick-change tracking
- Technical cue placement
- Rehearsal scheduling
