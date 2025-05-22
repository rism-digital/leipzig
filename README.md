# Leipzig music font

Repository for the Leipzig music font. The font was initially developed by Etienne Darbellay and Jean-François Marti as part of the Wolfgang music notation software. It is now developed further as part of the [Verovio](https://www.verovio.org) project.

Since version 5.0, the Leipzig font is compliant with the [Standard Music Font Layout (SMuFL)](https://www.smufl.org/). 

It is distributed under the [SIL Open Font License (OFL), Version 1.1](./LICENSE.txt).

You can view the list of glyphs [here](https://torinak.com/font/lsfont.html#https://raw.githubusercontent.com/rism-digital/leipzig/main/Leipzig.otf).

## Generation of font files

The [Leipzig.otf](./Leipzig.otf), [Leipzig.svg](./Leipzig.svg), [Leipzig.ttf](./Leipzig.ttf), [Leipzig.woff2](./Leipzig.woff2), and the corresponding [leipzig_metadata.json](./leipzig_metadata.json) are all generated from the [Leipzig.sfd](./Leipzig.sfd) file using the [generate_font.py](./generate_font.py) script. 

The script requires the `fontforge` package. Instead of installing the `fontforge` package, it is also possible to use the Python interpreter embedded in [FontForge](https://fontforge.org) (on macOS e.g., `/Applications/FontForge.app/Contents/Frameworks/Python.framework/Versions/3.9/bin/python3 generate_font.py`)  
