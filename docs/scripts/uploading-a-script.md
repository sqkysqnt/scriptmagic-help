# Uploading a Script

Scripts in ScriptMagic are uploaded as PDF files. Each page is processed into an image for fast viewing and annotation across all devices.

## Supported format

- **PDF files only** (.pdf)

## How to upload

1. Go to your [production's edit screen](../productions/creating-and-managing-productions.md#editing-a-production) or create a new production
2. Click **Upload Script PDF** and select a file
3. You'll see a confirmation dialog — click to proceed
4. The PDF is processed and each page is converted to a high-resolution image

All pages are automatically grouped into a "Default" [variant](script-variants.md).

### Cloud import vs. device processing

Depending on your company's plan, the PDF may be processed in one of two ways:

- **Cloud import** — the PDF is uploaded to ScriptMagic's servers and processed there. A progress dialog tracks the status in real time. You can close the dialog and continue working — processing continues in the background, and you'll receive a [notification](../getting-started/navigating-the-app.md#notifications) when it's complete.
- **Device processing** — the PDF is processed directly on your device. A progress indicator shows page-by-page status (e.g., "Processing page 3 of 120...").

Both methods produce the same result.

!!! note
    You need **Production Admin** or **Company Admin** permissions to upload or replace a script. See [Roles & Permissions](../collaboration/roles-and-permissions.md).

## Page offset

If your PDF includes cover pages, a title page, or other front matter before the actual script begins, set the **pages before script page 1** value in your production settings.

For example, if the first 5 pages of your PDF are front matter, set the offset to 5. That way, "Page 1" in ScriptMagic refers to what's actually the 6th page of the PDF. Front matter pages can be accessed using Roman numerals (i, ii, iii, etc.) in the [page navigation](viewing-and-navigating-pages.md#page-navigation).

## Replacing a script

You can upload a new script PDF at any time from the production edit screen.

!!! warning
    Replacing the script PDF may break existing annotations, blocking, page references, and tags. This action cannot be undone. You'll see a confirmation warning before it's applied.
