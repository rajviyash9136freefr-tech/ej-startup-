# Luxury Real Estate & Architectural Residences

A modern, high-performance static website for showcasing luxury real estate and architectural properties with integrated multi-language translation for major Indian languages.

## Project Structure

```text
├── images/             # All project images (property views, architectural galleries, hero)
├── index.html          # Main HTML, styling, interactive components, and translation engine
├── vercel.json         # Vercel deployment configuration
├── .gitignore          # Git ignore rules
└── README.md           # Documentation & language support guide
```

## Multi-Language Support (Top Indian Languages)

The website features an Obsidian & Ivory themed luxury language switcher in both desktop navigation and the mobile drawer, supporting 12 major languages with instant neural translation:

| # | Language | Script / Local Name | Code | Region / Primary Coverage |
|---|----------|---------------------|------|---------------------------|
| 1 | **English** | English | `en` | Pan-India / International |
| 2 | **Hindi** | हिन्दी | `hi` | Northern & Central India |
| 3 | **Punjabi** | ਪੰਜਾਬੀ | `pa` | Punjab & Northern India |
| 4 | **Bengali** | বাংলা | `bn` | West Bengal & Eastern India |
| 5 | **Gujarati** | ગુજરાતી | `gu` | Gujarat & Western India |
| 6 | **Marathi** | मराठी | `mr` | Maharashtra & Western India |
| 7 | **Tamil** | தமிழ் | `ta` | Tamil Nadu & Southern India |
| 8 | **Telugu** | తెలుగు | `te` | Andhra Pradesh & Telangana |
| 9 | **Kannada** | ಕನ್ನಡ | `kn` | Karnataka & Southern India |
| 10 | **Malayalam** | മലയാളം | `ml` | Kerala & Southern India |
| 11 | **Urdu** | اردو | `ur` | Pan-India |
| 12 | **Odia** | ଓଡ଼ିଆ | `or` | Odisha & Eastern India |

### How Translation Works
- **Zero-Flicker Preference Memory**: The selected language is saved in `localStorage` and synchronized with cookies.
- **Full-Site Neural Translation**: Translates all property descriptions, architecture details, modal popups, enquiry form fields, and footer elements.
- **Native Luxury Styling**: Google's default translation widgets, banners, and tooltips are concealed to preserve the strict Obsidian (`#171717`) and Ivory (`#F3EFE6`) aesthetic.

## Deployment on Vercel

Configured for zero-config deployment on [Vercel](https://vercel.com):
- Every push to the `main` branch of this repository automatically triggers a deployment on Vercel.
