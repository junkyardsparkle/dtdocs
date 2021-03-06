---
title: culling
id: culling
draft: false
weight: 30
author: "people"
---

Culling mode allows you to display images side by side to easily compare them. 

There are two different ways to define how many images are shown at the same time: “fixed” and “dynamic”. Switch between these methods while in culling mode by pressing `<`.

fixed mode
: The number of images displayed is always the same, independent of the selection length. This number can be set with a slider on the bottom panel.

: In this mode, you will navigate through all selected images. If no selection is set (or if only one image is selected), you will navigate through all images.

: The default keyboard shortcut to enter culling in fixed mode is `X`.

dynamic mode
: All of the selected images are shown. If no selection is set (or if only one image is selected) the last value from fixed mode is used.

: The default keyboard shortcut to enter culling in dynamic mode is `Ctrl+X`.

# zoom and pan

In culling mode, you can zoom (up to 100%) using `Ctrl+scroll` and pan within zoomed images with `click+drag`.

By default, zooming and panning are synchronized between all visible images. If you want to zoom or pan only a specific image, add the `Shift` modifier to the above actions.

To enhance performance when loading zoomed images, you can enable ([`preferences` -> `cpu/gpu/memory` -> `enable disk backend for full preview cache`](../../preferences-settings/cpu-gpu-memory.md)). Bear in mind that this can occupy a lot of disk space.
