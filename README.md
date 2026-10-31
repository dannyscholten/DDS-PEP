# DDS-PEP

Version 2.0.4 - 31 October 2026.

[Open DDS-PEP](https://dannyscholten.github.io/DDS-PEP/)

Integrated Personal Education Plan for Master Drug Discovery Sciences. Build and plan your curriculum, review requirements, complete approval details and download the approval PDF. Approval remains with the relevant university boards.

This replaces the separate PEP-builder and PEP-approval tools.

## Local use and source

Download index.html and open it in a browser. Planning data is stored in your browser; use Save build to keep a portable copy. Only files saved by the integrated DDS-PEP can be reopened with Open build. Files from the earlier separate Builder and Approval tools are not supported.

The source archive contains the readable HTML, CSS, JavaScript, curriculum data and third-party licence notices. Extract it, then run `python3 src/build.py` to reproduce the standalone HTML in outputs/. No private student plans are included.

## Changes in 2.0.4

- List and Approval curriculum tables use Course, or Project for major and minor research projects.
- List timing headings read Year & period(s); the action column is labelled Actions.

## Changes in 2.0.3

- Strict cohort-aware import validation and shared export checks. Catalogue attributes are reconstructed from the catalogue; unlisted courses require permitted levels and a public HTTP/HTTPS syllabus URL.
- Exception requests require a justification, remain pending a decision and require reconfirmation after relevant curriculum changes.
- Consistent Action required, Decision required and Planning advice labels; softer warning and curriculum-check colours in the tool and PDFs.
- Compact full-year calendar on narrow screens, chronological course ordering and uniform readable course-name sizes; smaller full-calendar typography.
- Live calendar dragging with validated snap targets. Automatic drag advice appears after one second, once per course in the current browser session, and remains in the advice panel.
- Acknowledge individual Planning advice messages to collapse them to their title. Reopen by clicking the title; acknowledgement does not bypass requirements or remove PDF warnings.
- C1 period warning markers in the web calendar and planning PDF replace the separate workload row. Planning PDFs carry a red personal-use-only notice on every page.
- Full calendars use Period 1 to Period 6; compact calendars retain P1 to P6. Normal dashes replace middle-dot separators.
- Persistent advice for first-year courses placed in Year 2; student-facing unlisted-course review notices; clarified extracurricular wording.
- Calendar-only extracurricular summary removed; List information and credit accounting retained. Mobile catalogue controls and scrolling refined.

## Changes in 2.0.2

- Unlisted-course syllabus URLs in approval PDFs are blue, underlined, clickable links, including wrapped lines.
- Curriculum checks include an Unlisted courses row naming the courses, with Needs review status.

## Changes in 2.0.1

- Refined category legends, course cards, action icons and structured warning panels.
- Compact phone landscape controls and independently scrolling Course Catalog; mobile Calendar course names are 25% smaller to show more text.
- Complete unlisted-course information required at entry, including institution, level and syllabus URL.
- Project settings grouped into concise rows with a scheduled-break editor and timing validation.
- Reliable automatic research-project fallback placement with applicable overlap warnings.
- Approval course edits remain in context; contextual navigation and exception-request feedback improved.

The previous 2.0.0 source archive remains in the repository. Git history retains the previous published page.
