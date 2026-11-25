# Cullet Size Identifier & Area Analyzer (`1 cm` Grid Model)

A single-file, offline-ready web application (**[index.html](file:///D:/Cullet/index.html)**) calibrated around your **`16 × 25` (`1 cm × 1 cm = 1 cm²`)** grid sheet and **[IMG_5468.HEIC](file:///c:/Users/mfadl/Downloads/IMG_5468.HEIC)** (also saved as **[D:\Cullet\IMG_5468.jpg](file:///D:/Cullet/IMG_5468.jpg)**).

---

## Step-by-Step Tutorial: How to Use the Cullet Scanner

### Option A — Instant Automatic Mode (1-Click on Your `16 × 25` 1 cm Grid Sheet)
1. **Open the App**: Double-click **[D:\Cullet\index.html](file:///D:/Cullet/index.html)**.
   - Your **[IMG_5468](file:///D:/Cullet/IMG_5468.jpg)** model photo loads, calibrates to the `1 cm` grid (`34.50 px/cm` = `3.450 px/mm`), masks out the dark outer table and `1..16` / `1..25` number margins, and analyzes all **21 glass pieces (`233.28 cm²`)** automatically on startup.
2. **Upload Any New Photo on the Same 1 cm Grid Sheet**:
   - Drag and drop your photo onto **1. Upload Photo** (or click to browse).
   - *Tip for iPhone `.HEIC` files*: Chrome/Edge on Windows cannot decode raw `.HEIC` files natively, except for `IMG_5468.HEIC` which is built in. For new iPhone photos, either save/convert as `.JPG` or set iPhone Camera → Formats → **Most Compatible (JPEG)**.
   - As soon as you drop a photo, the app **automatically applies the 1 cm Grid Setup (`10 cm` scale + margin exclusion boxes)** and runs the calculation immediately!
3. **Re-Apply 1 cm Grid Anytime**:
   - Click **Auto 1 cm Grid Setup (16×25 Sheet)** under **2. Ruler Calibration** to snap the calibration and margin exclusions to the `16 × 25` grid sheet in 1 click.

---

### Option B — Manual Calibration Mode (If Using a Different Ruler or Camera Distance)
1. **Calibrate the Ruler / Grid**:
   - Under **2. Ruler Calibration**, click **Click 2 Ruler Marks**.
   - Click two grid lines on the canvas that are **`10 cm` apart** (for example, line `1` and line `11` on your `1 cm` grid).
   - Keep the distance set to **`10`** and unit set to **`Centimeters (cm)`**.
2. **Exclude Outer Table & Numbers (Optional)**:
   - If any dark table edges or ruler numbers are being detected as glass, click **Clear Boxes** → **Draw Exclusion Box**, and drag boxes over the outer table / number headers.
3. **Calculate & Export**:
   - Click **Calculate Cullet Area & Size**.
   - View **Total Area (`cm²`)**, **Mean Piece Area (`cm²`)**, **Median Sieve (`D50` in `cm`)**, and the per-piece table in **`cm²`** and **`cm`**.
   - Click **CSV**, **JSON**, or **PNG** to download your results.
