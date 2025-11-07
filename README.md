# 🔄 Bulk Image Flipper (GUI)

A simple, multi-threaded desktop application built with Python and Tkinter for batch processing image flips and mirrors. Perfect for quickly filpping large sets of images!

*(Disclaimer: This entire utility was purely vibe coded.)*

---

✨ Features

* **Bulk Processing:** Select and process dozens or hundreds of images at once.
* **Multi-Threaded:** Processing is handled in a background thread, preventing the GUI from freezing.
* **Two Flip Modes:**
    * **Mirror (Horizontal):** Flips the image left-to-right (`ImageOps.mirror`).
    * **Flip (Vertical):** Flips the image top-to-bottom (`ImageOps.flip`).
* **Progress Tracking:** Includes a progress bar and status updates for the currently processed file.
* **Wide Format Support:** Supports all image formats readable by Pillow (`.jpg`, `.png`, `.webp`, `.tiff`, etc.).

🖼️ How to Use the App
Choose Images: Click "Choose Images..." to select the input files you want to flip (you can select multiple files at once).

Choose Output Folder: Click "Choose Output Folder..." to select where the newly flipped images will be saved.

Select Flip Option: Choose between "Mirror (Horizontal)" or "Flip (Vertical)".

Start: Click "Start" to begin the background processing.

Cancel: The "Cancel" button becomes active, allowing you to stop the job at any time.

Reset: The "Reset" button clears all selected files, folders, and resets the UI state.

The script saves the processed images in the output folder, keeping the original file names.

If you select the same Input/Output folder it will replace the images with flipped versions

Enjoy!
