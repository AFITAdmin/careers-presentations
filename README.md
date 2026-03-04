## Careers Lessons Resource System

## Overview

This is a single-page interactive Careers Lessons Resource System designed for use within a school environment.

The system provides structured navigation across:

* Personal Development Stages (PDS 2, 3 and 4)
* Six Learning Areas per stage
* Six Learning Elements per area

The final level opens HTML-based presentations in kiosk/fullscreen mode.

---

## Features

* Card-based navigation system
* Smooth animated transitions between levels
* Hover-based progression information panel
* Dark mode toggle
* Responsive layout (desktop, tablet, mobile)
* Structured presentation folder system

---

## Folder Structure

```
/ (root)
│
├── index.html
├── README.md
├── /images
│   └── /icons
│
└── /presentations
    ├── Element_1.html
    ├── Element_2.html
    └── ...
```

Images for cards are stored in:

```
/images/icons/
```

Presentation files must be stored in:

```
/presentations/
```

---

## Naming Conventions

Learning Area card images:

```
images/icons/GrowThroughoutLife.jpg
images/icons/ExplorePossibilities.jpg
```

Presentation filenames are automatically generated from element titles by replacing spaces with underscores:

Example:

```
"Work Life Balance"
```

Becomes:

```
presentations/Work_Life_Balance.html
```

---

## Development Workflow

Recommended branch structure:

* `main` → Stable live version
* `development` → Working draft

Only merge into `main` once testing is complete.

---

## Future Improvements

Planned improvements:

* JSON-based external data structure
* Admin editing mode
* Analytics tracking
* Additional PDS levels

---

## Author

Developed for school careers provision and structured personal development pathways.

---

## Licence

Internal school use.
 careers-presentations