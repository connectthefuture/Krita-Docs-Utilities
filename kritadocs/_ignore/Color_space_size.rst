Using Krita's color space browser, you can see that there's many
different space sizes.

`thumb\|800px\|center <File:Basiccolormanagement_compare4spaces.png>`__

How do these affect you image, and why would you use them?

The primary reason to use a large space is for three reasons:

#. Even though you can't see the colors, the computer program does
   understand them and can do color maths with it.
#. For exchanging between programs and devices: most CMYK profiles are a
   little bigger than our default sRGB in places, while in other places,
   it's smaller. To get the best conversion, having your image in a
   space that encompasses both you screen profile as your printer
   profile.
#. For archival purposes. In other words, maybe monitors of the future
   will have larger amounts of colors they can show(spoiler: they
   already do), and this allows you to be prepared for that.

Let's compare the following gradients in different spaces:

`File:Basiccolormanagement gradientsin4spaces
v2.jpg <File:Basiccolormanagement_gradientsin4spaces_v2.jpg>`__\ `File:Basiccolormanagement
gradientsin4spaces
nonmanaged.png <File:Basiccolormanagement_gradientsin4spaces_nonmanaged.png>`__

On the left we have an artefact-ridden color managed jpeg file with an
ACES sRGBtrc v2 profile attached(or not, depending on mediawiki's mood,
if not then you can see the exact different between the colors more
clearly). This should give an approximation of the actual colors. On the
right, we have a sRGB png that was converted in Krita from the base
file.

Each of the gradients are gradients from the max of a given channel. As
you can see, the mid-tone of the ACES color space is much brighter than
the mid-tone of the RGB colorspace, and this is because the primaries
are further apart.

What this means for us is that when we start mixing or applying filters,
Krita can output values higher than visible, but also generate more
correct mixes and gradients. In particular, when color correcting, the
bigger space can help with giving more precise information.

If you have a display profile that uses a LUT, then you can use
perceptual to give an indication of how your image will look.

Bigger spaces do have the downside they require more precision if you do
not want to see banding, so make sure to have at the least 16bit per
channel when choosing a bigger space.

Category:Color
