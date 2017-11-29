# Shutter button

![Shutter button](../images/shutter-button.png)

Located on the right of the viewfinder, is the virtual counterpart of the shutter button on traditional cameras. It can replicate all the functionality of a physical shutter button. However, if your device has a physical shutter button, you can also use it to take photos.

## Virtual shutter button

The virtual shutter button emulates a physical shutter button. Since the screen the virtual shutter button is placed on cannot react to half-presses like physical two-stage shutters, the two depths of traditional shutters are mapped differently:

* Tap and hold to focus and lock focus position.
* Release to capture a photograph.
* Drag the finger away from the button to cancel.

In detail, the behavior of the virtual shutter button is the following:

* _Tap and hold_: focuses and locks the focus position (corresponds to pressing a traditional shutter button halfway). While you hold the virtual shutter you can reframe while keeping the same focus position.
* _Release (after holding)_: takes the photograph if the focus was properly acquired (corresponds to pressing a traditional shutter button fully).
* _Single tap_: focuses and when done focusing takes immediately a photograph if the focus was properly acquired.
* _Tap and hold, then drag the finger away from the virtual shutter button_: focuses, locks the focus position, but does not take any photograph (corresponds to pressing a traditional shutter button halfway, then lifting the finger).

By default the app attempts to focus when you press the shutter button, and does not take photographs if the focus routine thinks the focus was not achieved. There are however two settings to override this behavior:

* The normal behavior is to cancel the action of taking a picture if the autofocus result was unsuccessful (that is, the autofocus routine didn’t achieve a sharp subject or couldn’t locate the focus position, both situations lead to a red focus rectangle). If you want Camera FV-5 to take a picture in any case (whether the focus succeeded or not), activate the option `Settings > General camera settings > Allow taking a photo without focus`.
* If you simply don’t want to trigger autofocus before taking a picture (that is, you want to take a picture without changing the focus position), activate the option `Settings > General camera settings > Focus before capturing`.

!!! note
    If the focusing routine fails, the default behavior is not to take the photo. The focus rectangle turns into red in this case. You can change this behavior in `Settings > General camera settings > Allow taking a photo without focus` although it is discouraged, as the resulting photo could be incorrectly focused.

## Physical shutter button

If your phone has a physical shutter key, you can use it to take photos with Camera FV-5. Save for the zoom (when not assigned to volume keys) and any other manual controls, you can take photos without having to ever use the touch screen.

There are two types of shutter keys:

* __With two steps__. Those shutter keys have two depths: you can press it slightly until the middle (half-press) and then continue until the end (full-press). When you half-press the shutter key, Camera FV-5 focuses the picture and then locks the focus, meaning that you can reframe your shot and the focus distance will remain. When you finally fully-press the shutter key, the picture is taken.
* __With one step__. On that case, the physical shutter key will behave the same way as the virtual shutter button.
