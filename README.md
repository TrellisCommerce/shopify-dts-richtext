# Dawn TailWindCSS Starter Component - RichText with improvements

Improvement for Shopify's Dawn theme RichText section. New options added:

- Background Color
- Background Image
- Background Image Size (Contain / Cover)
- Background Overlay Color
- Background Overlay Opacity
- Color Picker for Heading text and RichText blocks

## How to Add to Your Theme

1. Add an `rich-text-trellis.liquid` file to the `sections` directory and copy in the file's code from this repo.

- If you are not using the [dawn-tailwind-starter-base](https://github.com/TrellisCommerce/dawn-tailwind-starter-base) as your theme, you will need to add the following styles to your liquid file:

```
.twcss-bg-center{
    background-position: center;
}

.twcss-bg-no-repeat{
    background-repeat: no-repeat;
}

.twcss-bg-cover{
    background-size: cover;
}

.twcss-bg-contain{
    background-size: contain;
}
```
