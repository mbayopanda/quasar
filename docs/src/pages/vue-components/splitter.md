---
title: QSplitter
---

The QSplitter component allow containers to be split vertically and/or horizontally through a draggable separator bar.

## Installation
<doc-installation components="QSplitter" />

## Usage

::: warning
The use of the `before` and `after` slots is required.
:::

Click and drag on the splitter separator bar to see results.

<doc-example title="Basic" file="QSplitter/Basic" />

<doc-example title="Horizontal" file="QSplitter/Horizontal" />

<doc-example title="Custom dragging limits (50-100)" file="QSplitter/Limits" />

<doc-example title="Customized separator" file="QSplitter/CustomizedSeparator" dark />

A QSplitter can be embedded in another QSplitter's `before` and/or `after` slots, like shown in example below.

<doc-example title="Embedded" file="QSplitter/Embedded" />

## API
<doc-api file="QSplitter" />