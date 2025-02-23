# Elastre Typeface
Elastre is a modern-looking typeface, it draws inspiration from the early 2000s and the chaotic energy of electronics, evoking the futuristic designs and vibrant colors of advertisements from that era. Its unique blend of blocky and curvy elements creates a versatile aesthetic, perfect for making bold statements or adding subtle, gentle touches to your text with `HEXP` and `INKT` variable axis. It doesn’t confine you — it pushes you forward, encouraging you to break free from limitations. With Elastre typeface, you can *streeeetch* the boundaries of creativity without hesitation, exploring every corner of the galaxy. Elastre has got you covered, no matter how far you aim to go.

![Showcase.](documentation/Elastre-01.png "Elastre")

## Technical information
Some technical information about Elastre, specifically what the typeface includes. 

### Variables
Here's a table for a quick look. The `Inktrap` variable is self-explanatory: glyphs have big and noticeable ink traps; however, the `Line` variable means that glyphs have ink traps, but they are way smaller or *standard* size and less noticeable.
|Variable|Tag|Default|Maximum|Stages|
|:----|:---|:-----|:------|:--------|
|Hyper Expansion|HEXP|0|100|Super, Mega, Ultra|
|Inktrap|INKT|0|100|Line, Inktrap|

And another table to understand what the end-user will see.
|Instances|
|:---|
|Super Line|
|Super Inktrap|
|Mega Line|
|Mega Inktrap|
|Ultra Line|
|Ultra Inktrap|


### Scripts
* Latin
* Cyrillic

## Building Elastre
Time to build the typeface! Follow these steps:
1. At the root of your local clone `cd path/to/local/clone`, create a virtual environment: `python3 -m venv myenv`.
2. Activate the virtual environment: `source myenv/bin/activate`.
3. Install gftools (or the requirements) in the virtual environment: `pip install gftools` or `pip install -r requirements.txt`.
4. Navigate to the `sources` directory and from the terminal, run: `gftools builder config.yaml`.
5. Done! You will find the fonts in the `fonts` directory.

## Additional information
### Designers
* Valeriy Egorov

### License
Copyright (c) 2025, Valeriy Egorov (valeriy.hfmn@gmail.com).
This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is in this repo OFL.txt and is also available with a FAQ at: [*SIL Open Font License, 1.1*](http://scripts.sil.org/OFL).

