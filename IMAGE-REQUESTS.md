# Image Requests for Arty - Roomio US Site

## REQUEST #1: Pricing Comparison Image (URGENT)

**File to replace:** `wp-content/uploads/2025/09/Features-carousel-v1.png`

**Current issue:** The existing pricing comparison image shows outdated pricing ($15) and was likely sourced from the Australian site (roomio.io). This needs to be recreated with current USD pricing.

### Design Specifications:

**Dimensions:** 1487 x 1956 pixels (same as current image)

**Overall Layout:**
- Title at top: "Price comparison"
- Subtitle: "Roomio offers a lower cost compared to other competitors."
- Three pricing cards arranged horizontally (bar chart style)
- Footnote text at bottom
- Clean, modern design with gradient backgrounds

### Pricing Cards (Left to Right):

**Card 1: BoxBrownie**
- Logo: "bb." in white on dark background
- Price: **$35** (in large, bold white text)
- Background: Dark rounded rectangle (tallest bar)
- Height should be proportionally tallest

**Card 2: Cubicasa**
- Logo: Cubicasa play-button-style icon
- Price: **$30** (in large, bold white text)
- Background: Dark rounded rectangle (medium height)
- Height should be proportionally medium

**Card 3: Roomio** ⭐ **(THIS IS THE KEY CHANGE)**
- Logo: Roomio house/roof icon in white
- Price: **$11** (in large, bold white text) ← **CHANGED FROM $15**
- Background: Vibrant purple-to-blue gradient (make this pop visually)
- Height should be proportionally shortest (emphasizing affordability)
- This should be the most visually prominent/attractive card

### Footer Text:
"*Based on publicly listed rates as of September 2025 and may change; Roomio pricing reflects a **$11 package** including a custom 2D floor plan, site plan, and property report."

**Important:** Change both instances of the price in the footnote from $15 to $11

### Style Notes:
- Modern, clean design
- Use gradients for visual interest (especially on Roomio card)
- Make Roomio card stand out as the preferred option
- Maintain professional appearance
- Font should be clean, sans-serif, modern
- Adequate white space around elements

### Color Palette:
- Roomio card: Purple to blue gradient (#7C3AED to #3B82F6 or similar)
- Competitor cards: Dark gray/charcoal (#2D3748 or similar)
- Text: White for all prices and logos
- Background: Clean white or very light gray

### Output Requirements:
- Format: PNG with transparency support
- Resolution: 1487 x 1956 pixels
- File size: Optimize for web (aim for under 500KB)
- Save as: `Features-carousel-v1.png`

---

## Additional Notes:

The US Roomio price is **$11 USD** (not $9, not $13, not $15). This needs to be consistent across all materials.

If you need reference to the original image, it's currently located at:
`/home/node/.openclaw/workspace-webdev/sites/roomio-us/wp-content/uploads/2025/09/Features-carousel-v1.png`

Please replace that file once the new version is created.

---

**Priority:** HIGH - This is the only image blocking US site deployment.

**Created:** 2026-02-18  
**Requested by:** Devon (webdev agent)  
**For:** Roomio US site localization

---

## IMAGE VISUAL INSPECTION NEEDED (Added 2026-02-18)

The following images should be manually reviewed to check if they contain any Australian English text, AUD pricing, or AU-specific references. If issues are found, detailed specs should be added to this file for recreation.

### "How It Works" Step Graphics

**1. roomio-how-1.png**
- Path: `wp-content/uploads/2025/09/roomio-how-1.png`
- Size: 797KB
- Context: Step 1 of "How it works" section
- Likely contains: Text describing "Scan with your iPhone" step
- Check for: AU spelling (colour, organise, etc.)

**2. roomio-how-2.png**
- Path: `wp-content/uploads/2025/09/roomio-how-2.png`
- Size: 170KB  
- Context: Step 2 of "How it works" section
- Likely contains: Text describing "Customise & submit" step
- Check for: AU spelling (particularly "Customise" vs "Customize")

**3. roomio-how-3.png**
- Path: `wp-content/uploads/2025/09/roomio-how-3.png`
- Size: 198KB
- Context: Step 3 of "How it works" section
- Likely contains: Text describing "Receive & share" step
- Check for: AU spelling

### Content Images (Unknown Text Content)

**4-7. Image-*.png series**
- Image-34.png, Image-1.png, Image-2.png, Image.png
- Path: `wp-content/uploads/2025/09/`
- Context: Used in original-homepage.html
- Unknown content - needs visual review
- Check for: Any text, pricing, or AU-specific content

---

## AUDIT STATUS SUMMARY (2026-02-18)

✅ **Completed:**
- All HTML files checked for AU English → **No issues found**
- All HTML pricing references verified → **All show $11 USD**
- All missing image files downloaded from live site
- All video files downloaded (.webm, .mp4)
- All image size variants downloaded
- IMAGE-AUDIT.md created with comprehensive image inventory

⚠️ **Requires Manual Review:**
- 7 images need visual inspection for embedded text (see above)
- Features-carousel-v1.png needs Arty's updated version ($15 → $11)

🎯 **Blockers for Launch:**
- Only 1: Features-carousel-v1.png update (Arty is working on it)

