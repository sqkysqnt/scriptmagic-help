# Uploading a Script

Scripts in ScriptMagic are uploaded as PDF files. Each page is processed into an image for fast viewing and annotation across all devices.

## Supported format

- **PDF files only** (.pdf)

## How to upload

1. Go to your [production's edit screen](../productions/creating-and-managing-productions.md#editing-a-production)
2. Click **Upload Script PDF** and select a file
3. You'll see a confirmation dialog — click to proceed
4. A progress indicator shows processing status (e.g., "Processing page 3 of 120...")
5. When complete, the script is ready for viewing and annotation

During processing, each page of your PDF is converted to a high-resolution image. All pages are automatically grouped into a "Default" [variant](script-variants.md).

!!! note
    You need **Production Admin** or **Company Admin** permissions to upload or replace a script. See [Roles & Permissions](../collaboration/roles-and-permissions.md).

## Page offset

If your PDF includes cover pages, a title page, or other front matter before the actual script begins, set the **pages before script page 1** value in your production settings.

For example, if the first 5 pages of your PDF are front matter, set the offset to 5. That way, "Page 1" in ScriptMagic refers to what's actually the 6th page of the PDF. Front matter pages can be accessed using Roman numerals (i, ii, iii, etc.) in the [page navigation](viewing-and-navigating-pages.md#page-navigation).

## Replacing a script

You can upload a new script PDF at any time from the production edit screen.

!!! warning
    Replacing the script PDF may break existing annotations, blocking, page references, and tags. This action cannot be undone. You'll see a confirmation warning before it's applied.
