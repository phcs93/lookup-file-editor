# Group File Studio

A tool for editing .GRP files from Build Engine games.

You can access the app here:  
https://phcs93.github.io/group-file-studio/

# Features

- you can load a .grp file and see all its contents
- you can replace or edit the PALETTE.DAT file and export the modified file
- you can replace or edit the LOOKUP.DAT file and export the modified file
- you can reorder or replace tiles in an .ART file and export the modified file
- you can export the tiles as you see them (with palette swaps, shade, transparency and alterantive palettes)
    - the tiles will be exported as 8 bits .PNG files in a .ZIP

# TO-DO

- improve the ux
    - ability to unload .art files
    - disable upload lookup file button if no palette is loaded
    - disable upload art files button if no palette is loaded

- ability to edit animations (because these will be messed by the tile reordering feature)
- figure out the transparency table (alpha blending?)
- ability to upload/edit/export a tiles.cfg (for Mapster32 tile groups)
- validate uploaded files (for example, check if the GRP is a valid GRP)

- ability to edit tile pixels with loaded palette colors
    - this one might be too much...