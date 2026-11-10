# DocView

A private document viewer that runs in your browser and can be installed on an iPhone home screen. Files are opened on the device and are never uploaded anywhere. It also works offline after the first visit.

**Opens:** LibreOffice/OpenOffice (.odt .ods .odp), Word (.docx .doc .rtf), Excel (.xlsx .xls .csv), PowerPoint (.pptx .ppt), PDF, images and text files.

## Put it online with GitHub Pages (free)

1. Create a new **public** repository on GitHub, for example `docview`.
2. Click **Add file → Upload files** and upload all of these files: `index.html`, `manifest.json`, `sw.js`, `icon-180.png`, `icon-192.png` and `icon-512.png`. Then commit.
3. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, then branch **main** and folder **/ (root)**, and click **Save**.
4. Wait a minute or two. Your app will be at `https://YOUR-USERNAME.github.io/docview/`.

## Add it to your iPhone home screen

1. Open that link in **Safari**.
2. Tap **Share** (the square with an arrow), then tap **Add to Home Screen**, then **Add**.
3. Open **DocView** from your home screen and tap **Open a document → Choose File** to pick a file from the Files app (iCloud Drive, Downloads, etc.).

## Good to know

- iPhone doesn't let home-screen web apps show up in the **Share → Open in…** list. Open DocView first, then choose the file.
- Use **Print** to save any document as a PDF. In the print screen, pinch out on the preview, then tap Share and choose **Save to Files**.
- Word files show **Page view** (the real page layout) or **Fit text** (text reflowed to fit your screen). Use the button at the top to switch.
- Older **.doc** and **.ppt** files show the text only. Password-protected Office files can't be opened. Password-protected PDFs will ask for the password.
- Built with open-source libraries: JSZip, docx-preview, SheetJS and PDF.js.
