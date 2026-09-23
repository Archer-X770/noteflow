# Validation

JavaScript syntax checks passed. DOM-simulated runtime checks passed for:

- Creating and editing notes
- Pencil mode and pressure-bearing input
- Preserving existing ink nodes during drawing
- Undo, redo, erase, and undo erase
- Finger scrolling without drawing in Pencil mode
- Folders, subfolders, and folder paths
- Moving notes and deduplicating tags
- Deleting folders without deleting their notes or subfolders
- Rejecting cyclic folder trees in imported backups
- Batching storage writes during typing
- Responsive paper scaling with a stable drawing coordinate system

These are logic checks with a simulated DOM, not real-browser tests. A browser executable was unavailable and its download was blocked by the environment. Visual layout, Safari integration, Home Screen installation, offline loading, and actual Apple Pencil pressure/palm interactions still require real-device verification. No claim of native-quality palm rejection, Pencil squeeze, or double-tap support is made.
