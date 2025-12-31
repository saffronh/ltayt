# CSS Customization Guide

Your site now has a refined, literary aesthetic with elegant typography and subtle colors.

## Design Philosophy

**Colors:** Muted, sophisticated palette
- Off-white background (#fdfbf7)
- Warm taupe borders (#d4c9bd)
- Rich brown text (#2b2b2b)
- Subtle brown links (#6b5947)

**Typography:** Classic book-style fonts
- Libre Baskerville for headings (elegant serif)
- Source Serif 4 for body text (readable, refined)

## Quick Customization

### Color Palette
```css
/* Lines 10-14: Main colors */
background: #fdfbf7;        /* Off-white - try #ffffff for pure white */
color: #2b2b2b;             /* Dark brown text */

/* Line 17: Border color */
border-right: 1px solid #d4c9bd;  /* Taupe border */

/* Line 70: Link color */
color: #6b5947;             /* Brown links - try #2c5f2d for green, #4a5568 for gray */
```

### Alternative Color Schemes

**Pure Minimalist:**
```css
background: #ffffff;
color: #000000;
border: #e0e0e0;
links: #333333;
```

**Warm Cream:**
```css
background: #faf8f3;
color: #3d3d3d;
border: #d9cfc0;
links: #8b6f47;
```

**Cool Gray:**
```css
background: #f8f9fa;
color: #2d3748;
border: #cbd5e0;
links: #4a5568;
```

### Fonts

**Current fonts (line 1):**
- Libre Baskerville (headings)
- Source Serif 4 (body)

**Try these alternatives:**
```css
/* Classic Editorial */
@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;700&family=Crimson+Text&display=swap');
font-family: 'Crimson Text', Georgia, serif;  /* body */
font-family: 'Cormorant Garamond', serif;     /* headings */

/* Modern Serif */
@import url('https://fonts.googleapis.com/css2?family=Newsreader:wght@400;700&family=Spectral&display=swap');
font-family: 'Spectral', Georgia, serif;
font-family: 'Newsreader', serif;

/* Contemporary */
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap');
font-family: 'Inter', -apple-system, sans-serif;
```

### Spacing & Sizes

```css
/* Line 66: Main title */
font-size: 42px;            /* Make bigger (48px) or smaller (36px) */

/* Line 96: Body text */
font-size: 17px;            /* Standard is 16-18px */
line-height: 1.75;          /* 1.6-1.8 is comfortable */

/* Line 11: Sidebar width */
width: 380px;               /* Also change line 62! */
```

## What Makes This Design Classy

1. **Restrained color palette** - Only browns and taupes, no bright colors
2. **Generous whitespace** - Lots of breathing room
3. **Classic typography** - Book-style serif fonts
4. **Subtle details** - Delicate borders, gentle underlines
5. **Refined hierarchy** - Clear but not overwhelming

## Testing Your Changes

1. Edit `styles.css`
2. Save
3. Refresh browser (Cmd+R or Ctrl+R)
4. All pages update instantly!

No need to touch the HTML files - ever!
