# Publishing This Repository on GitHub

## Before uploading

- [ ] Obtain the host laboratory's permission to publish internal equipment photos and identify the facility.
- [ ] Verify the specific model names, especially the dry etcher and NANOVAK suffix. Confirm whether the microscope-assisted station is actually a laser micro-soldering system.
- [ ] Edit the experience statement to match your true level: observed, demonstrated, supervised hands-on, or independently operated.
- [ ] Do not post the original class PDF without checking privacy, image rights, and institutional policies. It contains a student ID and course/staff information.
- [ ] Remove any photograph that the facility does not authorize for public sharing. There are 10 photographs in `assets/equipment/`.

## Browser upload (simplest)

1. Sign into [github.com](https://github.com).
2. Choose **New repository** and name it `MEMS-Cleanroom-Lab-Exposure`.
3. Add this description: `Documented MEMS cleanroom exposure: lithography, spin coating, PVD, dry etching, cleaning and wafer processing.`
4. Choose **Public** only once the photo-sharing and institutional permissions have been checked; otherwise start **Private**.
5. Do **not** add an auto-generated README if uploading this folder's existing README.
6. Select **Add file → Upload files** and upload the contents of this directory, preserving `assets/` and `docs/` subfolders. Drag-and-drop a folder's contents or use Git if nested folders don't upload reliably.
7. Commit the files. Confirm that images and internal Markdown links work.
8. Add repository topics: `mems`, `microfabrication`, `cleanroom`, `photolithography`, `pvd`, `semiconductor`, `lab-exposure`.
9. Pin the repository on your GitHub profile only if it represents a meaningful part of your learning portfolio.

## Git CLI alternative

From the unpacked `MEMS-Cleanroom-Lab-Exposure` folder, after creating an empty repository on GitHub:

```bash
git init
git add .
git commit -m "Document MEMS lab exposure and equipment overview"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/MEMS-Cleanroom-Lab-Exposure.git
git push -u origin main
```

Replace `YOUR-USERNAME`; do not paste GitHub credentials or access tokens into this repository.

## LinkedIn project entry (adapt after publishing)

**Project:** MEMS Cleanroom & Microfabrication Laboratory Exposure

**Description:** Documented an educational exposure to MEMS cleanroom practices and microfabrication equipment, including the Heidelberg MLA 150 maskless aligner, Laurell spin coater, NANOVAK PVD system, ultrasonic cleaning, and dry-etching concepts. Organized equipment notes, process-function comparisons, verified technical references, and photographs into a structured GitHub repository. This was equipment familiarization, not an independently fabricated device.
