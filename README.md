## Upload and Update 2/28/2020

Hi, this is my personal fork of @sunpazed/garmin-mickey.

About a year and half ago, I DL'd the original source, found it didn't work with my Vivoactive 3 Music and cleaned it up/modified it to so it'd function.  I uploaded it today with an updated manifest.xml for Vivoactive 3 and Vivoactive 3 Music LTE.

The source has not been changed since 2018, so the alignment for all watches besides **Vivoactive 3/3 Music/3 Music LTE** will be off.

---

# Mickey

An Mickey watchface for Garmin's wearable lineup.

![](artwork/mickey.jpg)

## About

The purpose of this code is to showcase a new rendering technique I developed using fonts as a tilemap.
This is a more storage-friendly method than images, and allows developers to efficiently pack many frames of bitmapped animation in a 26kb font.
Also, the great thing about fonts, its that they do alpha blending with the existing framebuffer on the canvas. So, you get anti-aliasing as a nice by-product.
