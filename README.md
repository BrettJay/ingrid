![ingrid]
A free Sketch template, for seamlessly tiling Instagram compositions

![demo]

A sane, seamless, multi-part image workflow
-------------------------------------------

Ingrid is a free Sketch template, providing an easy way to export a seamless
tiling set of images for Instagram.

Design your multi-part image composition at 1× (375pt × 375pt), and export
higher resolution images (4× jpeg by default; 1500 × 1500px) for upload to
Instagram.

Basic usage
-----------

1. Select the artboard, and enter `375 * [number of desired segments]` as its width.
2. Use the rectangle tool (<kbd>R</kbd>) to draw out masks as desired
3. Nest each rectangle in its own group (<kbd>Command ⌘</kbd> + <kbd>G</kbd>)
4. Enable mask mode on each rectangle (<kbd>Right click</kbd> → <kbd>Mask</kbd>)
5. Drag photographs into corresponding group to mask each image inside the shape,
   scale, and position as desired.
6. Create slices for each segment(<kbd>S</kbd>); set to 4x size, JPG.
7. Select all slices, click <kbd>Export Selected</kbd>, and upload!

Why 375pt?
----------

375pt is the native display width of iPhones 6, 6s, 7, 8, X, and XS. This
accounts for a large proportion of devices using Instagram. By designing at the
‘1×’ scale of these devices, you can tailor the scale and spacing of elements in
your composition for these devices.

For example, any element inset in your composition by 15pt will appear to align
with various UI elements in Instagram on these devices. It’s subtle, but quite a
nice effect when viewed on device.

*Bear in mind that Instagram stores images at 1080px × 1080px, so while you can
design accurately with regards to scale, some [downsampling][ds] will occur*.

Create your own artboard
------------------------

You can delete the included artboard, and start from scratch.

Create your own artboard at `X: 0`, `Y:0`, with a width of `375 * [number of segments]`,
and a height of `375`.

[demo]: ./demo.jpg "Screenshot of Ingrid template in Sketch"
[ingrid]: ./logo.svg "Ingrid"
[ds]: https://bjango.com/articles/everythingisagrid/ "Everything is a Grid, by Marc Edwards"
