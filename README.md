# Tool Pocket Generator V22

Complete rebuild from the known-good V14 foundation. This is a new version, not a patch or amendment.

## Core photo/grid behaviour
1. The entered Length × Width defines the outside/master rectangle and is not changed by **Detect Tool Outline**.
2. The physical metric ruler/grid in the uploaded photograph is the authoritative physical reference for measuring the tool only.
3. The detected tool outline is transferred into the master rectangle at its measured physical size; it is not stretched to the rectangle boundaries.
4. **Set dimensions from physical grid** remains a separate deliberate action that replaces the master Length × Width with the measured tool size.

## Preserved functions
- Point editing and automatic renumbering.
- Undo edit history.
- Straight/Curved segment editing.
- Finger Relief FR1/FR2 workflow.
- Geometry Check and STL workflow.
- Saved tools, autosave/restore and JSON profile backup.

## Finalisation
The edited screen coordinates are converted to millimetres without an additional bounding-box stretch. The aim is a practical pocket that the real tool fits into, not a perfect pixel trace.
