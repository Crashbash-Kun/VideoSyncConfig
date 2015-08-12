# Pixiv-Fix

Pixiv's (or, the Japanese DeviantArt, as I call it) servers occasionally have a fit and results in downloaded images not being images, but rather being a 403 Forbidden error named as a .png, .jpg, ect. This can result in hundreds of images being 'corrupted' per say as they're just a few hundred byte files instead of images.

To fix this, this program essentially scans an inputted directory for files less than 500 bytes in size and allows them to be saved as a list in text format. The ImageID (filenames) can then be used to re-download the images properly with a tool such as Pixiv Util2.

NOTE: This program is very roughly done in Visual Basic 2010 and is in no way meant for public use. It was simply thrown together to fix my Pixiv collection that was broken for a year+.
