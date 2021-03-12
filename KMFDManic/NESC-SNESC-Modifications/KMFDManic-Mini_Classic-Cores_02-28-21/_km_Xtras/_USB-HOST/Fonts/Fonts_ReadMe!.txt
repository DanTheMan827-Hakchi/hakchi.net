Custom Fonts, Courtesy of DanTheMan827, Melthris, and KMFDManic

Use BMFont to generate the fnt and png file.

Options > Font Settings
- Select a font, and set the size to around 48 for a title font
- Turn on font smoothing and super sampling to level 4
click "OK"

Select the characters that you want to include on the right side of the window

Options > Export Settings
- Select 32-bit depth, and choose the "Outlined text with alpha" preset
- Choose binary font descriptor, and png for texture format
- Start with a texture width of 1024x512, click "OK"

Options > Visualize
If the title of the window indicates more than one sheet, close it and go back and 
increase the texture size a little bit until there's only one sheet

If there's only one and a lot of red at the bottom, you can decrease the size until it's gone.

Options > Save bitmap font as...

Use FntCombiner.exe to combine the two fnt and png files into a single fnt that the classic can use.