---
name: Preset Submission
about: Submit your custom preset to be featured in the community collection.
title: 'Preset Submission: [Your Preset Name]'
labels: 'preset-submission'
assignees: ''

---

### Thank you for your interest in adding a preset to the community collection.

I've created this template to make the submission process as smooth as possible. Following these steps ensures I have everything needed to review and add your work quickly.

---

### Submission Checklist

1.  **Export Your Preset from RapidRAW**
    *   In the app's "Presets" panel, right-click on the preset you want to share.
    *   Select **"Export Preset"**.
    *   Save the `.rrpreset` file to your computer.

2.  **Add Your Creator Name**
    *   **Important:** GitHub doesn’t allow uploading files with custom extensions like `.rrpreset`.  
        To work around this:
        *   Rename your exported file from `MyPreset.rrpreset` -> `MyPreset.rrpreset.txt`.
        *   Open the `MyPreset.rrpreset.txt` file with any text editor (like VS Code, Notepad, or TextEdit).
    *   Find the line that says `"creator": "Anonymous"`.
    *   Replace `"Anonymous"` with your name or GitHub handle. This is how you will be credited.

    **Before:**
    ```json
    "creator": "Anonymous",
    ```

    **After:**
    ```json
    "creator": "YourCoolName",
    ```

3.  **Attach the Preset File**
    *   Return to this issue page.
    *   **Drag and drop your edited file (still named with `.rrpreset.txt` at the end)** into the text box below (upload preset).

---

### Final Confirmation

- [ ] I have followed all the steps above.
- [ ] I have attached my edited `.rrpreset.txt` file to this issue.

### (Optional) Preset Description

Please tell me a little about your preset. What kind of photos does it work best on? (e.g., "Great for moody landscapes," "A warm, vintage look for portraits," etc.)