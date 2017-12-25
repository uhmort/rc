# Patches for dwm

* [Default transparency](https://dwm.suckless.org/patches/defaulttransparency) with rules, for example

    ``` c++
    /* class      instance    title       tags mask     isfloating   monitor   opacity */
    { "Firefox",  NULL,       NULL,       0,            0,           -1,       -1 } // default opacity
    { "st",       NULL,       NULL,       0,            1,           -1,       .8 } // 80%  opacity
    ```