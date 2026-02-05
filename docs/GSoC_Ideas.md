---
short-description: GSoC project ideas we like
...

# GSoC Project Ideas

To apply for a [GSoC internship] you need to make a project proposal. The scope
of your GSoC project will probably cover only Pitivi, but it could very well
span multiple codebases:

-   [Pitivi], which is the user interface. Written in Python. *For those
    who love design and graphical user interaction.*
-   [GES], the high-level video editing GStreamer library that powers
    Pitivi and other applications. Written in C. *For those who wish to
    improve an easy to use, powerful and flexible library for
    audio/video editing.*
-   GStreamer, for low-level work, such as improving filters/effects,
    codecs, hardware decoding/encoding acceleration, analysis, etc.
    Written in C. *For those seeking a challenging audio and video
    experience where optimization is key.*

We'd love to see GSoC proposals originating from an itch you need to scratch.
You are welcome to ask around and **bring your own ideas**. If you're not sure
where you can be most useful, have a look at our list of ideas below. These
shall be used as a base for writing a detailed project proposal.

See [Past GSoCs] for details on what the previous GSoC students did.

To create a detailed proposal, use our [GSoC application template].
Deadlines for applying are approaching fast, hurry up!

  [Pitivi]: https://www.pitivi.org/manual/mainwindow.html
  [GES]: GES.md
  [Past GSoCs]: Past_GSoCs.md
  [GSoC internship]: Google_Summer_of_Code.md
  [GSoC application template]: GSoC_Application.md


## GTK4 Timeline Ruler Widget in Rust

The [ruler above the timeline](https://aleb.ro/post/2016-01-23-polishing-pitivis-ruler/) provides the time context for the timeline. It displays time markers and at lower zoom levels the successive frames. Currently it's implemented in Python as a GTK3 widget, relying on the legacy cairo based drawing model. This project involves rewriting the ruler as a standalone, native Rust widget using GTK4's modern [GSK](https://en.wikipedia.org/wiki/GTK_Scene_Graph_Kit) rendering model.

**Requirements**: Rust. Minimal experience contributing to **any** Rust based GTK application. Familiarity with Python, GES and contributions to Pitivi a plus.


## GTK 4

The migration from GTK 3 to GTK 4 is advanced and needs finishing.
If interested, get in touch with us to put together some concrete tasks.

**Requirements**: Python. Minimal experience contributing to the GTK4 porting
branch. Experience developing GTK apps is a plus.
