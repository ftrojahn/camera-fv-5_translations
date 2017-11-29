# Considerations with RAW capture

When shooting in RAW, consider the following.

* RAW images are considerably bigger than JPEG or PNG images, and therefore they take much longer to write, and take much more space from the selected storage.
* RAW images contain the same EXIF information present in JPEG images.
* RAW images have no processing, that means that any post-processing that Camera FV-5 does to pictures are not applied to RAW images. Specifically:
    * Digital zoom takes no effect. Digital zoom means cropping and stretching the image to simulate zoom. RAW images contain exactly what the sensor sees, and therefore digital zoom is not present in RAW images.
    * White balance. White balance is applied in post-processing. However, the DNG metadata contains the white balance preset used in Camera FV-5 in the moment of capture, and therefore the RAW converter software will apply the same white balance preset that Camera FV-5 used by default. However, the white balance is still applied in post-processing, meaning that the recorded image itself does not contain this processing.
    * The RAW image, as an exact copy of the sensor data, follows always the sensor orientation (i.e. landscape). However, the orientation is recorded in the DNG metadata, and it is up to the RAW converter to honor this orientation when converting the DNG image.
