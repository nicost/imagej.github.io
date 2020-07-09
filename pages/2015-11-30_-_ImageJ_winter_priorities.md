---
autogenerated: true
title: 2015-11-30 - ImageJ winter priorities
breadcrumb: 2015-11-30 - ImageJ winter priorities
layout: page
author: test author
categories: ImageJ2,News
description: test description
---

Here is a status update from the ImageJ team at [LOCI](LOCI "wikilink"):
where we're at, what's next, and what tasks we see as the most important
to keep ImageJ moving forward.

## Top priority

First and foremost, we're on the cusp of submitting a paper describing
the structure of ImageJ2, which is a critical step towards future
funding efforts.

On the technical side, {% include person content='Rueden' %} just wrote
the first ImageJ code using Java 8 functionality, which will continue
drive our {% include github org='imagej' repo='imagej' issue='135'
label='need' %}. One recent and fundamental step in this direction is
the release of the {% include list-of-update-sites content='3D update
site' %}: providing Java 7- and 8-compatible versions of 3D ImageJ
plugins (previously relegated to Java 6).

## Next steps

In the coming months we have several projects of interest. In
approximate order of our priority:

  - [SCIFIO
    blockization](https://github.com/scifio/scifio/tree/blocks-are-so-plane)
    - better-integrating the [ImgLib2](ImgLib2 "wikilink") data model
    and moving from Planes to a general block-based API
  - [Rich
    images](https://github.com/imagej/imagej-common/tree/rich-image) - a
    polishing pass at the ImageJ data model
  - [Robust-IO](https://github.com/scifio/scifio/tree/location-robust-io)
    - generalizing image I/O sources
  - Increasing the sophistication of [ImageJ Ops](ImageJ_Ops "wikilink")
  - [SciJava-Common 3.x](https://github.com/scijava/scijava-common/milestones/3.0.0)
  - Increased collaboration with KNIME ([LOCI](LOCI "wikilink") is
    pleased to have {% include person content='gab1one' %} on loan from
    Konstanz\!)
  - Improved {% include github org='imagej' repo='imagej-legacy'
    issue='86' label='ImageJ1-ImageJ2' %}
  - [Formalizing developer roles and
    responsibilities](http://forum.imagej.net/t/project-developer-roles/206)
    (which will make an "Adopt-a-plugin" program possible\!)

## Long-term plans

  - Better support for arbitrarily large planes (via google-maps style
    scaling)
  - Improved support for arbitrarily large images (i.e., with huge
    numbers of planes or blocks)
  - JavaFX-based UI

## Continued support

While not directly tied to any one issue or reportable task,
[LOCI](LOCI "wikilink") will continue to support:

  - The ImageJ community—especially with the success of the new
    [forum](http://forum.imagej.net/)
  - [LOCI](http://loci.wisc.edu/) scientific collaborations
  - Technical training, via continued [presentations,
    workshops](https://imagej.net/Presentations#Workshops) and wiki
    guides.

[Category:ImageJ2](Category:ImageJ2 "wikilink")
[Category:News](Category:News "wikilink")