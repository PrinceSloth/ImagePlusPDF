ImagePlusPDF

A simple, privacy-friendly, browser-based tool to insert images as new pages at the start and/or end of an existing PDF.

## What it does

ImagePlusPDF allows you to:

- Upload an existing PDF document
- Add one or more images (PNG or JPG) **before** page 1 (great for covers, title pages, front matter)
- Add one or more images **after** the last page (perfect for appendices, photos, signatures, back matter)
- Automatically create properly sized PDF pages from your images
- Download the modified PDF instantly — original file remains untouched

Everything happens **client-side** in your browser using [pdf-lib](https://pdf-lib.js.org/). No files are uploaded to any server.

## How to use

1. Select your base PDF file
2. (Optional) Choose one or more images to insert at the **beginning**
3. (Optional) Choose one or more images to insert at the **end**
4. Click **Merge and Download**
5. Your new PDF (`modified_...`) will download automatically

## Features

- Supports multiple images in both positions (order preserved)
- Works with PNG and JPEG images
- Dark mode modern interface
- No registration, no server uploads — fully offline-capable after loading
- Automatic filename prefix (`modified_`) so you don't overwrite originals

## Limitations

- Images are placed full-page at their native resolution (no scaling/cropping/positioning options yet)
- Only PNG and JPEG images are supported
- Very large PDFs or many high-resolution images may be slow in the browser

## Technologies

- [pdf-lib](https://pdf-lib.js.org/) — powerful client-side PDF manipulation
- Vanilla JavaScript + modern CSS (dark theme)
- No build tools or frameworks required

## Why this tool?

Many people need to quickly add a cover photo, signature page, or a few extra images to PDFs without installing heavy software or using online services that raise privacy concerns. ImagePlusPDF solves exactly that use-case in the simplest possible way.

Enjoy!
