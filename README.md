# <span style="font-family: 'Times New Roman', Times, serif;">MCGI</span> Nueva Ecija WaterMark Studio

This project is the property of MCGI Productions Nueva Ecija.

## Overview

MCGI NE WaterMark Studio is a browser-based application for adding a logo watermark to photos and videos. Processing runs in the browser. The application does not modify the original files or require an account or internet connection after the project files have been downloaded.

## Features

- Select multiple photos and videos or an image directory.
- Upload a watermark logo in PNG, JPEG, WebP, or SVG format.
- Adjust watermark size, opacity, and distance from the image edge.
- Preview watermark placement before processing.
- Automatically slide through photos and video thumbnails in the preview panel while batch processing.
- Apply the same watermark settings to photos and videos in one batch.
- Preview a still video thumbnail while each video is processed.
- Choose a global video output format: prefer MP4 with WebM fallback, MP4 only, or WebM only.
- Preserve video audio when supported by the browser.
- Export as JPEG, PNG, or WebP, or retain the source image format where supported.
- Download processed images individually or as a single ZIP archive.

## Use

1. Open `mcgiproductionsnewatermarkstudio.html` in a supported browser.
2. Select a watermark logo and the photos and videos to process.
3. Configure the watermark and output settings.
4. Choose the video output format if processing videos.
5. Preview the result and select **Apply watermark to all photos and videos**.
6. Download the processed files.

Output files are named with the `_watermarked` suffix. Photos use the selected photo output format; videos use the selected global video format. Video output is re-encoded in real time. Available video formats, video decoding, and audio preservation depend on browser support. The original files are not changed.

## Project Files

- `mcgiproductionsnewatermarkstudio.html` — application interface and image-processing code.
- `assets/` — stylesheets and fonts used by the interface.
- `.gitignore` — excludes image files from Git tracking.

## Ownership

The application, source code, and project assets are maintained by MCGI Productions Nueva Ecija and are intended for its authorized production use.
