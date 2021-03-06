.. figure:: Krita_Preferences_Color_Management.png
   :alt: Krita_Preferences_Color_Management.png

   Krita\_Preferences\_Color\_Management.png

Krita offers extensive functionality for color management, utilising
`http://www.littlecms.com/ Little
CMS <http://www.littlecms.com/_Little_CMS>`__ We describe Color
Management in a more overal level here: `Color
Management <Special:myLanguage/Krita/Manual/ColorManagement>`__.

Default Color Model For New Images
----------------------------------

Choose the default model you prefer for all your images.

Display
-------

Use System Monitor Profile
    This option when selected will tell Krita to use the ICC profile
    selected in your system preferences.
Monitor Profile
    The user can select an ICC profile which Krita will use independent
    of the monitor profile set in system preferences. The default is
    sRGB built-in.
Rendering Intent
    Your choice of rendering intents is a way of telling Littlecms how
    you want colors mapped from one color space to another. There are
    four options available, all are explained on the `Color
    Management <Special:myLanguage/Krita/Manual/ColorManagement#Icc_profiles>`__
    manual page.

Softproofing options
--------------------

These allow you to configure the **default** softproofing options. To
configure the actual softproofing for the current image, go to .

For indepth details about how to use softproofing, check out `the page
on softproofing <Special:MyLanguage/Soft_Proofing>`__.

When Pasting Into Krita From Other Applications
-----------------------------------------------

The user can define what kind of conversion, if any, Krita will do to an
image that is copied from other applications i.e. Browser, GIMP, etc.

Assume sRGB
    This option will show the pasted image in the default Krita ICC
    profile of sRGB.
Assume monitor profile
    This option will show the pasted image in the monitor profile
    selected in system preferences.
Ask each time
    Krita will ask the user each time an image is pasted, what to do
    with it. This is the default.

.. raw:: mediawiki

   {{Note| When copying and pasting in Krita color information is always preserved.}}

Use Blackpoint Compensation
---------------------------

This option will turn on Blackpoint Compensation for the conversion. BPC
is explained below BPC is a sort of “poor man's” gamut mapping. It
basically adjust contrast of images in a way that darkest tone of source
device gets mapped to darkest tone of destination device. If you have an
image that is adjusted to be displayed on a monitor, and want to print
it on a large format printer, you should realize printer can render
black significantly darker that the screen. So BPC can do the adjustment
for you. It only makes sense on Relative colorimetric intent. Perceptual
and Saturation does have an implicit BPC.

Allow LittleCMS optimizations
-----------------------------

Uncheck this option when using Linear Light RGB or XYZ.

OpenColorIO
-----------

Use the OpenColorIO Environment Variable (OCIO) - ---
OpenColorIO Configuration Path: ---

Category:Preferences
