This allows you to have textured strokes. This parameter always shows up
as two parameters:

Texture
-------

Pattern
    Which pattern you'll be using.
Scale
    The size of the pattern. 1.0 is 100%.

file:krita_2_9_brushengine_texture_05.png

Horizontal Offset & Vertical Offset
    How much a brush is offset, random offset sets a new per stroke.

file:krita_2_9_brushengine_texture_04.png

Texturing mode

-  Multiply - Uses alpha multiplication to determine the effect of the
   texture. Has a soft feel.
-  Subtract - Uses substraction to determine the effect of the texture.
   Has a harsher, more texture feel.

file:krita_2_9_brushengine_texture_01.png

Cutoff policy

Cutoff policy will determine what range and where the strength will
affect the textured outcome.

-  Disabled - doesn't cut off. Full range will be used.
-  Pattern - cuts the pattern off.
-  Brush - Cuts the brush-tip off.

file:krita_2_9_brushengine_texture_02.png

Cutoff
    Cutoff is... the grayscale range that you can limit the texture to.
    This also affects the limit takes by the strength. In the below
    example, we move from the right arrow moved close to the left one,
    resulting in only the darkest values being drawn. After that, three
    images with larger range, and underneath that, three ranges with the
    left arrow moved, result in the darkest values being cut away,
    leaving only the lightest. The last example is the pattern without
    cutoff.

file:krita_2_9_brushengine_texture_07.png

Invert Pattern
    Invert the pattern.

file:krita_2_9_brushengine_texture_06.png

Strength
--------

This allows you to set the texture to Sensors. It will use the cutoff to
continuously draw lighter values of the texture(making the result
darker)

file:krita_2_9_brushengine_texture_03.png

External links
--------------

`David Revoy describing the texture
feature(old) <http://www.davidrevoy.com/article107/textured-brush-in-floss-digital-painting>`__

`Category:Brush Settings <Category:Brush_Settings>`__
