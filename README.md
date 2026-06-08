# Avo Toolkit for Zotero

Turns a collection's PDF annotations into a Word-ready reference list in one click.
Each annotation becomes `► [gerd01] highlighted text`, where `[gerd01]` is a live
link that opens the PDF at that annotation — no footnotes, nothing to clean up.

## Install

1. Download the latest **`avo-toolkit.xpi`** from
   [Releases](https://github.com/jlupini/zotero-avo-toolkit-dist/releases/latest).
2. In Zotero, open **Tools → Plugins**.
3. Click the **gear** icon (top-right) → **Install Plugin From File…**
4. Select the `avo-toolkit.xpi` you downloaded. Done — no restart needed.

After this, updates install themselves: Zotero checks for new versions
automatically, so you only ever install once.

## Use

Select a collection (or some items) that have annotations, then either right-click
or use the **Tools** menu. Two options:

- **Avo: Make Annotation Note** — creates a single Zotero note containing every
  annotation, each as `► [citekey] highlighted text`. The note is auto-selected.
- **Avo: Export Annotations to Word** — generates a Word document (`.docx`) of the
  same content and opens it in Word automatically. No copy-paste needed.

In both, each `[citekey]` is a live link that opens the source PDF at that exact
annotation.
