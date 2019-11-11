
# images-how_i_draw-process.md

Image work area is in:
- /art/images/projects/books/how_i_draw

# Work Area Directories

- `original`
  - Original portraits from the galleries at seeourminds.com
- `templates`
  - Starting points
- `fullsize`
  - 1800 x 1800
- `fullsize-name`
  - 1800 x 2155
- `fullsize-percentages`
  - 1800 x 2560
- ``

# Processes

## Create Templates

See `images-resolutions_and_aspect_ratios.md` in this directory.
- landscape - 3200 x 1800
- portrait - 1800 x 3200
- square - 1800 x 1800
- combo, pair - 1820 x 1280

Use these to create the cards

## Create Captioned Portraits

1. Create full-sized captioned portraits
2. Create required full-sized combo images with captions
3. Shrink as needed to make room for text
4. Post full-sized captioned images without text

### 1. Create full-sized captioned portraits

1. Create full-sized portraits - 1800 x 1800 - `fullsize`
2. Add name to each - 1800 x 2155 - `fullsize-name`
  - 2.1. Guide for name at 2052 px
  - 2.2. Font for name: 128 px, Bold
3. Add percentages captions to each - `fullsize-percentages`
  - 3.1. Font for percentages: 60 px
  - 3.2. Horizontal guides for bottoms of percentages lines at: 2194, 2336, 2478
  - 3.3. Vertical guides to help centering percentages lines at: 100, 250, 400, 1400, 1550, 1700

Calculations for Guides for Percentages values:
- Top of percentages area: 2052
- Bottom of percentages area: 2560
- Vertical space in percentages area: 2560-2052 = 508
- Font size: 60
  - Vertical space needed for text: 3*60 = 180
  - Vertical space left for margins: 508-180 = 328
- Height of each margin: 328/4 = 82
- Top and bottom of each line:
  - Top of line 1: 2052 + 82 = 2134
  - Bottom of line 1: 2134 + 60 = 2194 (*)
  - Top of line 2: 2194 + 82 = 2276
  - Bottom of line 2: 2276 + 60 = 2336 (*)
  - Top of line 3: 2336 + 82 = 2418
  - Bottom of line 3: 2418 + 60 = 2478 (*)
  - Final margin check: 2478 + 82 = 2560

### 2. Create required full-sized combo images with captions

Required combo images:
- Mulder & Scully
- Donald & Steve

Process:
1. Copy needed `fullsize-percentages` images to `halfsize-percentages` directory and rename files
2. Scale images to 900 x 1280
3. Export as jpg
4. Paste into combo template file - 20px horizontal margin

### 3. Shrink as needed to make room for text

### 4. Post full-sized captioned images without text

See how_i_draw sheet in `promotion_plans.ods` .

