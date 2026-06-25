# Adrian's Font ROM Editors

These web-based tools are designed to help you edit dedicated font ROMs. This edits the actual ROM image so you can then burn it back onto an EEPROM for use with a video card or in a computer. This tool is not designed to edit fonts baked into program ROMs, like the IBM PC BIOS, or EGA/VGA card BIOS chips. 

To allow you to mix-and-match fonts and glyphs, you can open multiple editors in different tabs and Copy/Paste glyphs between fonts. I have included some sample fonts in the 'samples' directory.

One thing to note: that when you alter settings in the left pane, this does not change the font data, it only changes how it renders on your browser. Only bits you actually change are altered in the ROM file when you click save. You do not have to worry about the ROM structure getting messed up by editing it.

As with everything, you should ALWAYS make backup copes of your fonts first as these tools have not been extensively tested.

[Apple II Font Editor](https://htmlpreview.github.io/?https://github.com/misterblack1/font_editors/blob/main/editors/Apple_II.html)

[Apple II Videx 80 Column Card Font Editor](https://htmlpreview.github.io/?https://github.com/misterblack1/font_editors/blob/main/editors/Videx.html)

[IBM CGA/MDA Font Editor](https://htmlpreview.github.io/?https://github.com/misterblack1/font_editors/blob/main/editors/IBM_CGA_MDA.html)

[Commodore 64/128/PET/VIC-20 Font Editor](https://htmlpreview.github.io/?https://github.com/misterblack1/font_editors/blob/main/editors/Commodore.html)

[TRS-80 Model 1/2/3/4/DTI + CoCo External Font Editor](https://htmlpreview.github.io/?https://github.com/misterblack1/font_editors/blob/main/editors/TRS80.html)

If you have another machine with a font ROM that isn't supported here, create an issue and I can look into it. 

Notes: Apple II font generation circuitry vaies quite a bit from model to model, so you may need to push invert and/or mirror to get them to look correct in the editor. This is just how the hardware work on the Apple II. For other systems, like IBM (CGA/MDA) or TRS-80, you may need to change the mode depending on the font. The editor does not try to guess the system type. 

Screenshots:
![Apple II Editor](/editors/previews/apple_II.png)

![IBM CGA/MDA Editor](/editors/previews/ibm_editor_preview.png)

