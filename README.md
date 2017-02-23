# grid-masonry-multires-images

A masonry grid layout that populates images by pulling them from a local folder

Powered by jQuery, and must run on localhost or a server to work correctly.

Be sure to remove restrictions on image permissions, set to at least "read only"

Place 1x, 2x, 3x lower resolution images into each perspective folder and rename with appropriate @1x, @2x, @3x suffix.

If there are no 1x, 2x, 3x folders, script will pull images from the plain 'images' folder which should contain the originals.

Toolips will pull from the name of each image file.

The label is by default above the image.

Move it to the bottom of the image by adjusting this code within index.html file. Comment out "Label BELOW the image" and uncomment "Label ABOVE the image".

For a simpler dynamic cmasonry grid that only pulls images from a single file, check out https://github.com/labelle/grid-masonry-dynamic-images
