Dr Patil Digital OPD V25 — Flattened PDF integration

Included:
- Original DrPatil_Digital_OPD_V25_Final.html (unchanged; checksum verified)
- Updated .github/workflows/build-apk.yml using html2canvas + jsPDF to rasterize the complete A4 letterhead page and embed it as one image in a PDF.

The physical print route remains the Android native print route. The V25 HTML source is unchanged.

Validation completed here:
- Workflow YAML parses successfully.
- Original V25 HTML SHA-256 matches the workflow's pinned checksum.
- The standalone flattened A4 PDF test already confirmed one A4 page with one embedded image and a non-blank render.

Important:
The GitHub connection rejected the workflow update with HTTP 403 (Resource not accessible by integration). Therefore this workflow has NOT been pushed to the repository and no APK has been built from it. Replace the repository's .github/workflows/build-apk.yml with the included file to trigger the CI integration test and APK build.
