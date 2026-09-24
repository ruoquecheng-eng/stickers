# Sticker Library

A public collection of chat stickers with a small JSON index for searching by meaning and context.

## Structure

```text
stickers.json
images/
  001.jpg
  002.png
```

## Add a sticker

1. Upload the image to `images/` using a short, stable numeric filename such as `001.jpg`.
2. Add the same ID to `stickers.json` with a short description, emotion tags, and suitable contexts.
3. Keep filenames and IDs stable so existing links do not break.

## Image URLs

Once a file is on the `main` branch, its jsDelivr URL has this form:

```text
https://cdn.jsdelivr.net/gh/ruoquecheng-eng/stickers@main/images/001.jpg
```

Use the file's actual extension in the URL. CDN updates may take a short time to appear after a change.

## Public repository

Files in this repository are public. Only upload images you have permission to share publicly.
