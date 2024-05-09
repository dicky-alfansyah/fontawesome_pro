# Font Awesome Pro
## v6.5.2 For The Web

**Use a Kit :**

```html
<link href="https://cdn.jsdelivr.net/gh/dicky-alfansyah/fontawesome_pro@main/6.5.2/css/all.min.css" rel="stylesheet" crossorigin="anonymous">
```

**or :**
```bash
npm i myfontawesome-pro-web@6.5.2 
```

**Example :**

<https://example-fontawesome.pages.dev>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Example</title>
    <link href="https://cdn.jsdelivr.net/gh/dicky-alfansyah/fontawesome_pro@main/6.5.2/css/all.min.css" rel="stylesheet" crossorigin="anonymous">
    <style>
        .fa-duotone.fa-puzzle {
            font-size: 100px;
        }
    </style>
</head>
<body>
    <i class="fa-duotone fa-puzzle"></i>
</body>
</html>
```
## Changelog v6.5.2 For The Web
Released April 1, 2024

###  Added
- Crowned our new Web Awesome brand icon
- Waved our new Font Awesome brand icon
- Finally added the new Bluesky brand icon
- Added a new commissioned JXL for Jira brand icon
- A batch of new icons, including: caduceus, gluten-free, and reflect-both icons
- Signaled a new circle-wifi and commissioned circle-wifi-group icons
- New commissioned file-cad, ant, and baby bottle icons
- Locked in some table-related icons, including: table-cells-lock, table-cells-column-lock, and table-cells-row-lock
  
###  Changed
- Updated the Kickstarter brand icon
- Updated the Upwork brand icon

### Fixed
- Fixed an issue where calendar-lines in Sharp Regular wasn't actually sharp
- Fixed the duotone styling of printer, fax, and shredder
- Fixed spacing in the location-check icon
- Fixed an issue with the SVG of face-kiss-beam
- Filled in some missing icons in the arrow-to/from-bracket icon series
- Update the TypeScript definition for Library.add() to allow an array of icon defintions
- Animation CSS custom property --fa-rotate-by now has a correct default value of 0
- Fixed some Less variable issues with --fa-bounce
