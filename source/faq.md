---
layout: default
title: FAQ
permalink: /faq/
slug: faq
---

FAQ
===

{: .alert .alert-info }
Hint
: [Help us add more information to this page](https://github.com/mpc-hc/mpc-hc.org)

1. **What are the requirements for MPC-HC?**

    In order to run MPC-HC you must have an SSE capable CPU. MPC-HC will work on
    Windows® XP Service Pack 3, Vista, 7 and 8, both 32-bit (x86) and 64-bit (x64).

2. **My picture is up-side down, how do I fix it?**

    Try updating your video card drivers.

3. **Why is there suddenly a different seekbar in fullscreen?**

    You have accidentally enabled D3D Fullscreen, go to Options -> Output
    and disable the D3D Fullscreen checkbox.

4. **Why am I seeing tearing in the video?**

    The video display is experiencing a synchronisation issue, try enabling V-Sync by pressing V.
    If you have more than one monitor connected make sure you extend the screen instead of duplicating it.

5. **Why am I seeing strange glitches in the video?**

    Hardware acceleration is most likely not working correctly.
    Try going to Options -> Internal Filters, right-click the list on the right
    and click "Disable DXVA filters" and then reload the video file.
    If this does not solve and your video file plays correctly in other
    video players then please make a bug report.

6. **Will MPC-HC support Windows RT or Metro?**

    Supporting these new platforms require a lot of changes and this is simply
    not possible for us in the near future, with the current manpower.

7. **Why after playback event doesn't work when repeat forever is selected?**

    Repeat forever option means that the current playlist will be repeated every time and
    because of that none after playback event is executed. We ecourage to use playlist which
    let you queue files to playback.

8. **Why am I seeing player logo or cover art during audio file playback, how can I hide it?**

    Cover-art image loading can be disabled in options->player settings page. If you want also to
    have minimal MPC-HC window size upon opening audio file you need to adjust size limit for audio files
    in Options->Advanced->CoverArtSizeLimit.

9. **I want to pause playback with mouse click, but my window is dragged instead, what is happening?**

    If you click on video space and the mouse pointer is not moved in between button click and release, playback
    will be paused, but if you move your mouse pointer window will be dragged. If you want to prevent such
    behaviour change Play/Pause command (Options->Keys) to "Left Down" instead of default "Left Up".

10. **Why PGS subtitles goes out of video frame?**

    PGS subtitles are rendered in the exact same position as for Blu-ray and if video frame was cropped to remove
    black bars, subtitles can still use this space. We do that to maintain best possible quality and reproduction of
    subtitles. Don't worry, nothing is lost you just need to resize MPC-HC window to restore previously cropped space.
