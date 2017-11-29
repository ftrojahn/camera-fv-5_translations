# Troubleshooting

## All shots come out with the same exposure

In this case, probably your device does not change exposure compensation instantly and Camera FV-5 leaves not enough time for the exposure to adapt. You can introduce a delay in `Settings > General camera settings > Compatibility > Pause between exposures`. You can also set the setting **Pause duration** to either **Short** or **Long**.

## Photos are out of focus, specially after the first one

Some camera hardware reset the focus after taking a shot. You can force in that case Camera FV-5 to refocus after each shot. To do that, activate `Settings > General camera settings > Compatibility > Refocus after every shot`.

## Bracketing does not work (nothing seems to happen)

If bracketing doesn’t seem to work and it is nothing related with the previous two possible problems, follow the next checklist:

1. You are in program mode (**P** icon at left side of the viewfinder). In **speed priority mode (S)** the bracketing settings are disabled (you are setting the shutter speed in this mode, so you cannot override this parameter).
2. You are using **ISO AUTO**. It might happen that, when exposure time is limited, ISO is needed to compensate the exposure. If ISO is not set to AUTO, this won’t be possible, and you will get some (or all) shots with the same exposure.
3. Be sure to set at least 3 frames (**3F** is shown in the upper display) in the bracketing settings. When **1F** is displayed, means bracketing is disabled.
4. Be sure to set at least one EV step increment (the lower display should be different than **0.0**). If the increment is **0.5**, you can set it to **0.5**, **1.0**, **1.5**, etc.
5. Check the number of frames to be bracketed at the lower exposure meter display. The red mark denotes the central frame, whereas the white marks denote the bracketed frames (darker/brighter). If you see only one red mark, that means that bracketing is disabled (see points 2 and 3).
6. Also, check that there is enough exposure compensation range for the bracketed frames to be taken. That is: if your camera have an exposure compensation range of **[−2, +2]**, in **0.5** steps, and you have set the exposure compensation to **−1**, for instance, you have set the BRK step to **2.0** (the maximum), and you try to change **1F** to **3F**, the resulting compensation would be **−3**, **−1** (the current EV compensation) and **+1**, and of course, your camera negative EV compensation reach only **−2**, so the **−3** compensation is out of range, that’s why Camera FV-5 won’t let you to change to **3F** in that situation (you will need to change EV to 0 to bracket 3 frames with **2.0** step).
