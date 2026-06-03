# Blog Images Needed

Your blog structure now includes image placeholders ready for your images. Here's what you need to prepare:

## Image Files Needed

### 1. Featured Image for Article Page
**Location:** `blog/aigc-design-beyond-text-to-image/assets/aigc-design-hero.jpg`
**Size:** Recommended 1200x675px (16:9 aspect ratio)
**Purpose:** Main featured image at top of article
**Suggested content:** 
- Abstract illustration of AI-powered design workflow
- Modern, professional aesthetic
- Represents collaboration between human creativity and AI

### 2. Thumbnail Images for Blog Listing
**Location:** `blog/assets/` (or `../assets/`)
**Files needed:**
- `aigc-design-thumbnail.jpg` - 400x200px for AIGC Design article
- `brand-strategy-thumbnail.jpg` - 400x200px for Brand Strategy article  
- `design-systems-thumbnail.jpg` - 400x200px for Design Systems article

**Suggested content:**
- Small preview images representing each article topic
- Consistent style to match your portfolio branding
- Minimum 400x200px, but can be larger for quality

## Where These Images Go

```
portfolio/
├── blog/
│   ├── index.html (references: assets/aigc-design-thumbnail.jpg, assets/brand-strategy-thumbnail.jpg, assets/design-systems-thumbnail.jpg)
│   ├── assets/
│   │   ├── aigc-design-thumbnail.jpg
│   │   ├── brand-strategy-thumbnail.jpg
│   │   └── design-systems-thumbnail.jpg
│   └── aigc-design-beyond-text-to-image/
│       ├── index.html (references: assets/aigc-design-hero.jpg)
│       └── assets/
│           └── aigc-design-hero.jpg
```

## How the Images Will Display

**Blog Listing Page:**
- Each article card shows a 200px tall thumbnail above the title
- Thumbnails crop with object-fit: cover for consistent sizing
- On hover, cards lift slightly with shadow effect

**Article Page:**
- Featured hero image displays at top of article after title
- Image caption: "Featured image: AI-powered creative design workflow"

## Credits Section

A credits section has been added at the bottom of the article page with:
```
Credits
Featured image: Original illustration by Lucrezia Spapperi Gestri
All case studies, examples, and insights based on real brand projects and design experience.
```

You can edit this to include:
- Image source/attribution if using licensed images
- Designer credits if outsourcing illustrations
- Any stock photo sources used

## Recommendations for Images

### Option 1: Custom Design (Recommended for your brand)
- Create illustrations that match your portfolio's aesthetic
- Ensures brand consistency
- Original work strengthens your portfolio credibility

### Option 2: Stock Images (Budget-friendly)
- Free: Unsplash, Pexels, Pixabay
- Premium: Shutterstock, Adobe Stock, Envato Elements
- Search terms: "design workflow AI", "branding process", "design thinking"

### Option 3: AI-Generated (Fast & Unique)
- Can be generated once you have workspace credits
- Consistent style if using same model
- Must include attribution (e.g., "Generated with [AI service name]")

## File Format & Optimization

- **Format:** JPG (good compression) or PNG (if transparency needed)
- **Size:** Keep under 200KB per image for fast loading
- **Resolution:** 2x the display size for crisp display on high-DPI screens
  - 200px display → 400px actual
  - 1200px display → 2400px actual

## Next Steps

1. **Prepare your images** (design, find, or generate)
2. **Name them exactly** as listed above
3. **Create the assets folder** in blog/ and aigc-design-beyond-text-to-image/
4. **Place images in correct folders**
5. **Upload to GitHub** with your blog folder
6. **Test on live site** to verify images display correctly

Your HTML is ready—just add the images when you have them!
