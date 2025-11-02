# Code conventions I'm using for this site

## CSS

Overall order:

```css
/* || GENERAL STYLES */
/* || UTILITIES (unused for now) */
/* || SITE-WIDE */
/* || MORE SPECIFIC */
```

Order of declarations inside a block:

```css
<block> {
    /* Color & Background:
        background, color */

    /* Text & Typography:
        font-family, font-size, line-height, text-align */

    /* Display & Box Model:
        width, height
        padding, border, margin 
        display, overflow, box-sizing */

    /* Positioning:
        position, z-index, top, right, bottom, left */

    /* Other:
        cursor, opacity, transform, transition */
}

```