# Image Compressor

A minimal, browser-based image compressor. Upload → Compress → Download.

- Supports JPG, PNG, WebP and AVIF
- Batch upload with drag and drop
- Low / Balanced / High quality control
- Per-file download and Download All (ZIP)
- 100% local: images never leave your browser

## Usage

Open `index.html` in a browser. No build step, no dependencies to install
(JSZip is loaded from cdnjs for the ZIP download).

## Notes

- PNG files are converted to WebP for real size savings.
- If a compressed file is not smaller than the original, the original is kept.
- Browsers that can't encode AVIF fall back to WebP.
