# Nicad

Nicad is a parametric 3D CAD app for Windows, macOS and Linux. You sketch with constraints and dimensions, build a part from features in a history you can go back and change, and put parts together into assemblies and drawings.

**[Download the latest version](../../releases/latest)**

## What it does

- **Sketches:**
  - lines, arcs, circles, rectangles, slots, polygons, ellipses, splines and text;
  - geometric constraints and driving dimensions, with trim, extend, offset, mirror and patterns;
  - 3D sketches for pipes and wires;
  - sketch templates: draw a shape once (a nut trap, a keyhole slot, a logo), give it parameters, and place it on any sketch's points.
- **Parts:**
  - extrude, revolve, sweep, loft, rib, holes (tapped, with modelled threads if you want them), shell, draft, fillets (including variable radius) and chamfers;
  - patterns, body tools and construction geometry;
  - direct face edits, which work on imported solids too;
  - a Surface tab, for shapes that start as surfaces;
  - a history that says what each step is (*on top face of Extrude1*, *Sketch1 · Join · 10 mm*).
- **Parameters:** names and formulas in any field, shared between parts through parameter files, in millimetres or inches.
- **Assemblies:**
  - linked parts placed with joints, and sub-assemblies;
  - interference checks, exploded views, a bill of materials, and motion you can animate.
- **Drawings:** 2D sheets with views and dimensions, exported as PDF or DXF.
- **Checking:** measure, mass properties, section views, and draft, curvature and zebra analysis.
- **Files:**
  - imports STEP, IGES, DXF, STL, OBJ and 3MF;
  - exports STEP, IGES, DXF, STL, 3MF, OBJ, glTF and pictures;
  - files you save open in every later version.

When a change breaks something, Nicad shows a card that says what happened, why, and how to fix it.

## Installing

| System | Download |
|---|---|
| Windows (64-bit) | `Nicad-<version>-win-x64.exe` |
| macOS, Apple silicon (M1 and later) | `Nicad-<version>-mac-arm64.dmg` |
| macOS, Intel | `Nicad-<version>-mac-x64.dmg` |
| Linux | `.AppImage` (updates itself), `.deb` (Debian, Ubuntu) or `.rpm` (Fedora, openSUSE) |

Nicad needs a graphics card or driver that supports WebGL 2, which almost every computer from the last ten years has.

Nicad isn't signed with a paid certificate yet, so your system warns you the first time:
- **Windows:** in the SmartScreen warning, choose **More info**, then **Run anyway**.
- **macOS:** open System Settings › Privacy & Security, and choose **Open Anyway** next to Nicad.

## Getting started

When Nicad opens, the start page has a step-by-step first part and three sample parts to look around. The full user guide is built in: press **F1**. Settings has mouse presets that behave like SolidWorks, Fusion 360, Onshape or Blender.

## Updates

Nicad checks this page for new versions when it starts and every few hours after that. It only tells you when there's one: nothing is downloaded or installed until you say so, and a download you don't install is deleted when you quit.
- **macOS:** Nicad can't install updates itself yet. Its card brings you here to download the new `.dmg`.
- **`.deb` and `.rpm` installs:** these are updated by installing the newer package.

## What's coming

Next, roughly in this order (no dates, and plans may change):
- **More for assemblies:** the bill of materials on drawings, flexible sub-assemblies, and several joints moving together.
- **Part features:** mitred sweep corners, more loft options, Up To Face onto freeform faces, and shell on freeform faces.
- **Speed:** faster modelled threads and quicker rebuilds of large parts.
- **The modelling tolerance as a setting.**
- **Scripting:** macros in TypeScript to generate parts and automate edits.

Bug fixes come out as they're needed, between these. Tell us what you'd like to see through **Send Feedback…**.

## Feedback

Found a bug, or missing something? In Nicad, choose **Send Feedback…** from the app menu. It opens a new [issue](../../issues) with your version and system filled in. You can also open one here directly. Issues are public, so only attach files you're happy to share.

The source code isn't public.
