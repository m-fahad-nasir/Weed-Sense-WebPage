# Weed-VLM GitHub Pages package

This folder is ready to publish as a static GitHub Pages site.

## Files
- `index.html` - main Weed-VLM frontend
- `assets/samples/` - 50 soybean field images extracted from the Excel workbook
- `assets/visualizers/` - 50 corresponding weed visualizer images extracted from the Excel workbook

## Publish from GitHub web UI
1. Create a new public GitHub repository.
2. Upload everything in this folder to the repository root.
3. Go to Settings -> Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select branch main and folder /(root), then click Save.
6. Wait for GitHub Pages to finish deployment. Your site URL appears on the Pages settings screen.

## Local preview
Run this inside the folder:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.


## Final update notes

- The upload-your-own-image feature is shown as coming soon and is disabled in this static demo.
- The Crop Type Dataset selector is scrollable and shows four crop options at a time.
- The results panel displays the original image and ground-truth visualization below the model responses.
- Two Khalifa University Weed Sense models are included in the model selector.
