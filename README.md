# AdaptiveHitchance
Adaptive hitchance calculation - Customizable per weapon.

    /*
     *            HOW TO CONFIG SETTINGS
     *  Enable the config button and reload the script, all settings will be set
     *  to the values below.
     *
     *  You can set a default value by doing the following:
     *  UI.SetValue("Script items", "name of option/slider", value);
     *
     *  In order to pick a mode or playstyle, simply set 0 for increasing/agressive (accordingly)
     *  and 1 for decreasing/passive.
     *
     *  In order to config the enabled weapons, you need to think of it as binary value.
     *  For example: If you want to enabled Auto, Scout, and AWP, the total you'd need to
     *  set the dropdown to would be 7.
     *
     *  Bits go in this order:
     *  1, 2, 4, 8, 16, 32, 64, 128
     *
     *  All you have to do is find the position of the gun(s) you want enabled and
     *  add the values of the list above that are in the same position.
     *
     *  Checkboxes are set as true/false.
     *
     *  Colors can be set in the format of [r,g,b,alpha]
     *
     *  If you ever wonder how to use something, check the forums:
     *  https://onetap.su/resources/
     *
     *  Add me on discord @Ultranite#9259 for help.
     *
     */
