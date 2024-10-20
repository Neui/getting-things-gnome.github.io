# libLarch, a Python library to easily handle data structures

![Liblarch logo](https://ploum.net/images/liblarch/liblarch0.png)

libLarch is a Python library built to easily handle data structures such
as lists, trees and directed acyclic graphs (tree where nodes can have
multiple parents). There's also a liblarch-gtk binding that will allow
you to use your data structure into a Gtk.Treeview.

libLarch supports multiple views of one data structure, and complex
filtering. That way, you have a clear separation between your data
(Model) and how it is displayed (View).

If you find Gtk.Treeview and Gtk.Treemodel hard to use, then libLarch is
probably for you.

[Download latest release tarball](https://github.com/getting-things-gnome/liblarch/releases) -
[Github page](https://github.com/liblarch/liblarch) -
[![https://flattr.com/thing/499738/Liblarch-a-python-library](https://api.flattr.com/button/flattr-badge-large.png "https://flattr.com/thing/499738/Liblarch-a-python-library")](https://flattr.com/thing/499738/Liblarch-a-python-library)

## Documentation libLarch API 1.0

- [General FAQ](https://wiki.gnome.org/Projects/liblarch/faq)
- [Getting libLarch and using it in your project](https://wiki.gnome.org/Projects/liblarch/installation)
- [Tree and TreeNode](https://wiki.gnome.org/Projects/liblarch/tree): Creating and modifying your data structure.
- [ViewTree and Filters](https://wiki.gnome.org/Projects/liblarch/viewtree): viewing your data
- [libLarch-gtk](https://wiki.gnome.org/Projects/liblarch/gtk): displaying a libLarch.ViewTree in a gtk.TreeView widget.
- [How to develop libLarch](https://wiki.gnome.org/Projects/liblarch/dev)
  - [Test cases for the libLarch test suite](https://wiki.gnome.org/Projects/liblarch/testcases)

## Who built this?

- [LionelDricot](https://wiki.gnome.org/LionelDricot)
- [IzidorMatusov](https://wiki.gnome.org/IzidorMatusov)

## Roadmap

The next milestone is to work on our major issue: performance.

If you identify any use case where using libLarch is hard or impossible,
please tell us, we are open to suggestions. Please report us bugs.

## Projects using libLarch

- [Getting Things GNOME!](index)
