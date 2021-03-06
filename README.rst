==========================
Smart LED Christmas lights
==========================

`Unofficial documentation`_ of :ref:`API reference <api-reference>`, protocol
details and hardware of `Twinkly`_ - Smart Decoration LED lights for Christmas.

Official materials says:

    Twinkly is a LED light device that you can control via smartphone. It
    allows you to play with colouful and animated effects, or create new ones.
    Decoration lights, not suitable for household illumination.

Since its `Kickstarter project`_ in 2016 many products were introduced with
varying properties and features. Most notably products released since September
2019 are identified as Generation II. Older products are since then referred as
Generation I. Documentation has been created and tested only on some
:ref:`hardware <hardware>`.

Products could be further groupped by families for which firmware is released.
Firmware on devices can be upgraded and sometimes new features are introduced.
Documentation has been created for some of these :ref:`firmwares <firmware>`.

Why?
----

My first Twinkly was 105 LEDs starter light set. That was the latest available
model in 2017: TW105S-EU. As of December 2017 there are only two ways to
control lights: mobile app on Android or iOS or hardware button on the cord.

Android application didn't work as advertised on my Xiaomi Redmi 3S phone. On
first start it connected and disconnected in very fast pace (like every 1-2
seconds) to the hardware. I wasn't able to control anything at all. Later I
wanted to connect it to my local WiFi network. But popup dialog that shouldn't
have appear never did so.

Public API was `promised around Christmas 2016`_ for next season. Later update
from October 2016 it seems `API won't be available any time soon`_:

    API for external control are on our dev check list, we definitely need some
    feedback from the community to understand which could be a proper core set
    to start with.

It turned out that application uses HTTP to control lights. I ended up with
capturing network traffic and documented this private API. In the end I'm able
to configure the device pretty easilly.

As of 2020 Twinkly devices can be controlled by Amazon Alexa and Google
Assistant as well. Mobile application now requires an account to operate lights
even locally. No sign of public API for local devices though. Therefore with my
second device - Twinkly 210 RGB+W Wall I keep updating this documentation to be
able to operate my devices locally and not rely on availability of
manufacturer's servers.

License
-------

Documentation is available under MIT license.

.. _`Twinkly`: https://www.twinkly.com/
.. _`Unofficial documentation`: https://xled-docs.readthedocs.io/
.. _`Kickstarter project`: https://www.kickstarter.com/projects/twinkly/twinkly-smart-decoration-for-your-christmas
.. _`promised around Christmas 2016`: https://www.kickstarter.com/projects/twinkly/twinkly-smart-decoration-for-your-christmas/comments?cursor=15497325#comment-15497324
.. _`API won't be available any time soon`: https://www.kickstarter.com/projects/twinkly/twinkly-smart-decoration-for-your-christmas/comments?cursor=14619713#comment-14619712
