# Snapshots & History

Snapshots capture the current state of your production's cues and highlights so you can compare changes over time or restore a previous state. This is especially useful during tech rehearsals when cue positions change frequently and you may need to roll back.

## What's in a snapshot?

A snapshot records:

- All cues and highlights across selected layers
- Cue comments
- Layer configuration data

Each snapshot stores counts of layers, highlights, and cues so you can quickly see the scope of what was captured.

## Creating a snapshot

Open the **History** panel from the side panels in the script view. To save a snapshot:

1. Optionally enter a **label** to describe this snapshot (e.g., "End of Thursday rehearsal")
2. Optionally click the **layers** icon to choose which layers to include — by default, all configured layers are included
3. Click **Save Snapshot**

The snapshot is saved immediately and appears in the history list.

!!! tip
    Give snapshots descriptive labels so your team can quickly find the right one to compare or restore from later.

## Manual vs. automatic snapshots

There are two types of snapshots:

- **Manual** — Created explicitly by clicking Save Snapshot. Shown with a camera icon and amber "Manual" badge.
- **Automatic** — Created by the system on a schedule when auto-snapshots are enabled. Shown with a clock icon and blue "Auto" badge.

Both types can be compared and restored from.

## Comparing a snapshot with the current state

Click the **compare** button on any snapshot in the history list to open a side-by-side diff view. The comparison shows:

- Which layers have changed
- Cue and highlight counts per layer (snapshot vs. current)
- Individual cue and highlight differences

Use the diff view to decide whether to restore specific items or an entire layer.

## Restoring from a snapshot

From the comparison view, you can restore:

- **Individual cues** — Bring back a single cue to its snapshot state
- **Individual highlights** — Restore a specific highlight
- **Entire layers** — Restore all cues and highlights on a layer at once

Restored items are written back to the live production immediately. The restore is recorded in the activity log.

!!! warning
    Restoring overwrites the current state of the restored items. Make sure to save a new snapshot first if you want to preserve the current state before restoring.

## Snapshot layer configuration

Production admins can configure which layers are included in snapshots from the **Snapshots** section of the [production admin dashboard](../getting-started/navigating-the-app.md#production-admin-dashboard):

- Toggle individual layers on or off
- Use **Include All** / **Exclude All** for bulk changes
- Layers with "Me" visibility are excluded by default
- Each layer shows its creator and visibility level

This configuration applies to both manual and automatic snapshots.

!!! note
    Snapshot configuration cannot be changed on [frozen productions](creating-and-managing-productions.md#production-freeze).

## Permanent archives

Some snapshots may be marked as **permanent archives** (shown with a lock icon). These are protected from automatic pruning and cannot be deleted. Use permanent archives for milestone captures like "Opening Night" or "Final Dress."

## Deleting a snapshot

Click the **delete** button on a snapshot to remove it. Permanent archives cannot be deleted.

## Related

- [Production Admin Dashboard](../getting-started/navigating-the-app.md#production-admin-dashboard) — Configure snapshot settings and view analytics
- [Understanding Layers](../annotations/understanding-layers.md) — How layers organize your annotations
- [Cues](../annotations/cues.md) — Technical cue management
