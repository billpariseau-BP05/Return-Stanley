# 🐶 Return-Stanley
## QR Code Pet Recovery Tag System

A simple, reliable QR-code-based pet identification system designed to help reunite lost pets with their owners.

This project creates a lightweight webpage hosted on GitHub Pages that is linked to a QR code printed into a durable 3D-printed dog tag.

The QR code does not store personal information directly. Instead, it points to a webpage where current contact information can be updated at any time without replacing the physical tag.

---

# Project Purpose

Stanley is a Yellow Labrador Retriever puppy whose tag uses this system to provide:

- Fast identification if found
- One-touch owner contact
- Home location access
- Future updates without replacing the QR code
- A durable 3D-printable TPU dog tag solution

---

# How It Works

```
Stanley TPU Dog Tag

        ↓

QR Code Scan

        ↓

GitHub Pages Website

        ↓

Owner Contact Information
```

A person who finds Stanley can scan the QR code using any modern smartphone camera.

No app installation is required.

---

# Live Website

After GitHub Pages is enabled, this project will be available at:

```
https://YOURUSERNAME.github.io/Return-Stanley/
```

Replace:

```
YOURUSERNAME
```

with your GitHub username.

---

# Repository Structure

```
Return-Stanley/

│
├── index.html
│
├── README.md
│
└── images/
    │
    └── stanley.jpg

```

---

# Updating Stanley's Information

To update contact information:

1. Open this repository on GitHub.
2. Open:

```
index.html
```

3. Click the pencil icon:

```
Edit this file
```

4. Update the information.
5. Click:

```
Commit Changes
```

The webpage will automatically update.

The physical QR code does not need to be replaced.

---

# Current Information

## Pet

**Name**

Stanley

**Breed**

Yellow Labrador Retriever

**Birth Date**

July 3, 2026

---

## Owner

**Name**

Bill Pariseau

**Phone**

651-246-2969

**Email**

bill.pariseau@gmail.com

---

## Home Location

23290 Itasca Ave N

Forest Lake, MN 55025

---

## Future Information

The following fields can be added later:

- Microchip number
- Veterinarian information
- Vaccination records
- Medical notes
- Emergency contacts
- Additional photos

---

# QR Code Specifications

The QR code used for this project should be created with:

| Setting | Recommendation |
|---|---|
| Format | SVG |
| Error Correction | High (H) |
| Minimum Size | 30 mm |
| Color | Black and White |
| Quiet Zone | Required |
| URL | GitHub Pages address |

High error correction is recommended because the tag may experience:

- Scratches
- Dirt
- Water exposure
- Wear from daily use

---

# 3D Printed Tag Specifications

Designed for:

## Snapmaker U1

Recommended material:

```
TPU Flexible Filament
```

Recommended dimensions:

```
Width:
45 mm

Height:
45 mm

Thickness:
3 mm

QR Area:
30 mm

Split Ring Hole:
5 mm

```

---

# Recommended Print Settings

```
Material:
TPU

Layer Height:
0.20 mm

Walls:
4

Top Layers:
6

Bottom Layers:
6

Infill:
100%

Supports:
None

Print Speed:
30-40 mm/s

```

---

# Recommended Physical Design

Front:

```
-----------------

      STANLEY


     QR CODE


     SCAN ME

-----------------
```

Back:

```
-----------------

Bill Pariseau

651-246-2969

Reward If Found

-----------------
```

---

# Testing Procedure

Before attaching the tag to Stanley:

## Test 1 — Digital QR Test

1. Display the QR code on a computer.
2. Scan it using a phone.
3. Confirm the website opens.

---

## Test 2 — Printed Tag Test

After printing:

1. Scan under bright lighting.
2. Scan indoors.
3. Scan at an angle.
4. Confirm the webpage loads.

---

## Test 3 — Durability Test

Cover approximately 10% of the QR code.

Confirm the QR code still scans.

High error correction should allow partial damage.

---

# Privacy Considerations

This project intentionally uses a webpage instead of storing personal data inside the QR code.

Advantages:

- Information can be updated.
- Contact details can be removed.
- The QR code does not expose information unless scanned.
- No app is required.

Consider limiting publicly displayed information if privacy concerns change.

---

# License

MIT License

Copyright (c) 2026 Bill Pariseau

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files, to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software.

The software is provided "as is", without warranty of any kind.

---

# Future Improvements

Potential enhancements:

- Automatic QR generation
- Multiple pet support
- Lost pet notification form
- Anonymous scan analytics
- NFC tag support
- Additional 3D tag designs
- Veterinary information section

---

# Credits

Created as a personal pet recovery project for:

🐶 Stanley

Yellow Labrador Retriever

Forest Lake, Minnesota
