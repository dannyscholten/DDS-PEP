# DDS-PEP

Version 2.0.1 — 28 October 2026.

[Open DDS-PEP](https://dannyscholten.github.io/DDS-PEP/)

Integrated Personal Education Plan for Master Drug Discovery Sciences. Build and plan your curriculum, review requirements, complete approval details and download the approval PDF. Approval remains with the relevant university boards.

This replaces the separate PEP-builder and PEP-approval tools.

## Local use and source

Download index.html and open it in a browser. Planning data is stored in your browser; use Save build to keep a portable copy. Only files saved by the integrated DDS-PEP can be reopened with Open build. Files from the earlier separate Builder and Approval tools are not supported.

The source archive contains the readable HTML, CSS, JavaScript, curriculum data and third-party licence notices. Extract it, then run `python3 src/build.py` to reproduce the standalone HTML in outputs/. No private student plans are included.

## Changes in 2.0.1

- Refined category legends, course cards, action icons and structured warning panels.
- Compact phone landscape controls and independently scrolling Course Catalog; mobile Calendar course names are 25% smaller to show more text.
- Complete unlisted-course information required at entry, including institution, level and syllabus URL.
- Project settings grouped into concise rows with a scheduled-break editor and timing validation.
- Reliable automatic research-project fallback placement with applicable overlap warnings.
- Approval course edits remain in context; contextual navigation and exception-request feedback improved.

The previous 2.0.0 source archive remains in the repository. Git history retains the previous published page.
