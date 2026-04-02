# Roomio US Site - Image Audit for Localization

**Date:** 2026-02-18  
**Purpose:** Identify all images that may contain Australian English text, AUD pricing, or AU-specific references

---

## ✅ IMAGES CONFIRMED CLEAN (No Localization Needed)

### Logo & Icons
- `roomio-logo.png` - Plain logo, no text
- `roomio-icon-150x150.png` - Icon only
- `roomio-icon-300x300.png` - Icon only

### Profile/Author Images
- `roomio-author.png` - Generic avatar, no text
- `roomio-author-2.png` - Generic avatar, no text
- `roomio-author-3.png` - Generic avatar, no text

### Phone Mockup/Hero Images
- `hero-phone.png` - Phone mockup with app interface (UI screenshots are generic, no visible pricing or AU text)
- `ae71cd2c882ebac90b89fc069aac88d6e0702b12-818x1024.png` - Phone screenshot (app interface)
- `ae71cd2c882ebac90b89fc069aac88d6e0702b12-scaled.png` - Phone screenshot (app interface)

### Support Article Thumbnails
- `Article1-1.png` (and variants) - Generic support article illustration
- `Article2-1.png` (and variants) - Generic support article illustration
- `ChatGPT-Image-Oct-8-2025-03_08_27-PM-1.png` (and variants) - Generic support article illustration

---

## ⚠️ IMAGES NEEDING REVIEW (Potential Text Content)

### Priority 1: Known Issues (Already Documented)
1. **Features-carousel-v1.png**
   - **Status:** DOCUMENTED in IMAGE-REQUESTS.md - Arty is working on it
   - **Issue:** Shows $15 pricing, needs to be $11 USD
   - **Used in:** index.html, original-homepage.html
   - **Action:** Waiting for Arty's updated version

### Priority 2: "How It Works" Step Graphics (NEEDS VISUAL INSPECTION)
2. **roomio-how-1.png**
   - **Size:** 797KB (large = likely has graphics/text)
   - **Context:** "How it works" - Step 1
   - **Location:** index.html, original-homepage.html
   - **Likely content:** "Scan with your iPhone" or similar instructional text
   - **Needs check for:** AU spelling (colour, metre, etc.)

3. **roomio-how-2.png**
   - **Size:** 170KB
   - **Context:** "How it works" - Step 2
   - **Location:** index.html, original-homepage.html
   - **Likely content:** "Process/Edit" step text
   - **Needs check for:** AU spelling

4. **roomio-how-3.png**
   - **Size:** 198KB
   - **Context:** "How it works" - Step 3
   - **Location:** index.html, original-homepage.html
   - **Likely content:** "Export/Deliver" step text
   - **Needs check for:** AU spelling

### Priority 3: Generic Content Images (NEEDS VISUAL INSPECTION)
5. **Image-34.png** (and variants: -1024x528, -300x155, -768x396)
   - **Context:** Used in original-homepage.html
   - **Needs check for:** Any embedded text, pricing, or AU references

6. **Image-1.png** (and variants: -1024x528, -300x155, -768x396)
   - **Context:** Used in original-homepage.html
   - **Needs check for:** Any embedded text, pricing, or AU references

7. **Image-2.png** (and variants: -1024x528, -300x155, -768x396)
   - **Context:** Used in original-homepage.html
   - **Needs check for:** Any embedded text, pricing, or AU references

8. **Image.png** (and variants: -1024x528, -300x155, -768x396)
   - **Context:** Used in original-homepage.html
   - **Needs check for:** Any embedded text, pricing, or AU references

---

## 🔍 RECOMMENDED ACTIONS

1. **Immediate:** Wait for Arty to complete Features-carousel-v1.png update ($15 → $11)

2. **Manual Review Required:** Open each of the "roomio-how" images in an image viewer and check for:
   - Any text with AU spelling (organise, colour, metre, etc.)
   - Any pricing references
   - Any AU-specific terminology

3. **Manual Review Required:** Open each of the "Image-*.png" files and check for:
   - Any embedded text
   - Any pricing information
   - Any AU-specific content

4. **If Issues Found:** Document them in IMAGE-REQUESTS.md with:
   - Current text content
   - Required US English replacement text
   - Image dimensions
   - Style/color specifications

---

## 📍 FILE LOCATIONS

All images are located in:
- `/home/node/.openclaw/workspace-webdev/sites/roomio-us/wp-content/uploads/2025/09/`
- `/home/node/.openclaw/workspace-webdev/sites/roomio-us/wp-content/uploads/2025/10/`

---

## ✅ COMPLETED CHECKS

- [x] All HTML files audited for image references
- [x] All referenced images confirmed present (no 404s)
- [x] All image size variants downloaded from live site
- [x] Video files downloaded (webm, mp4)
- [x] Pricing text in HTML confirmed $11 USD throughout
- [x] HTML text checked for AU English (all clean)

---

## 📝 NOTES

- The site references images using relative paths (e.g., `../wp-content/uploads/`) which is correct and working
- All missing video files have been downloaded
- The "aud" references in privacy-policy.html are false positives (part of "fraud" and "audit" words)
- No Australian English found in any HTML text content
