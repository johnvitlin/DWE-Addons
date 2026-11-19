# Changelog

Notable changes to Dynamic Web Extended (DWE) are recorded here.

## Version 0.3.10 — November 2026

### New features
- Added an optional searchable and sortable table for citations on the individual Citations tab, with columns for Citation, Source, Cited in and Details.
- Added citation context descriptions and links from the table back to the corresponding references on the Individual's page.
- Added a Configuration checkbox allowing visitors to choose between the original list and the searchable table.
- Added an optional creator-selected Citations information note, displayed in an initially collapsed About panel on the Citations tab.

### Fixes
- Fixed missing citations attached directly to event references (EventRefs).
- Improved the collection and display of citations associated with media objects and media references.
- Corrected media file paths in the GEDCOM used by the Topola Tree Viewer when media files are copied into the report. The no-copy option is unchanged.
- Corrected the ordering of media items in galleries to preserve their order in Gramps.

### Improvements
- Relabeled the individual Sources tab to Citations to better describe its content and function.
- Added Gramps citation IDs to the Citations display, respecting the existing option to suppress Gramps IDs.
- Added searching by selected column in the Citations table.
- Improved the presentation and positioning of citation markers in media galleries.
- Added translation labels for citation contexts and Citations table controls.
- Improved table styling, including compatibility with the Enhanced borders option.

### Documentation
- Updated the User Guide to describe Citations, display options, citation navigation and optional About note.

## Version 0.3.9 — November 2026

### New features
- Added a Calendar page displaying birthdays, marriage anniversaries and death anniversaries.
- Added Calendar options for event types, year range, first day of the week and surname display for married women.
- Added an optional Calendar information note.
- Added a visitor filter for displaying events for living people only or all included people.
- Added event details through popovers and dialogs, with support for month-only dates and February 29.
- Integrated Calendar styling with the selected website theme.

### Improvements
- Simplified internal parent–child relationship phrase handling by removing the built-in default phrase table. The existing relationship note format is unchanged, so existing notes do not need to be modified.
- Centralized report-generation progress allocations.
- Added separate progress stages and timing measurements for Calendar and Notable Records.
- Added a diagnostic confirming completion of all progress units.

### Documentation
- Updated the User Guide with Calendar instructions and examples.
- Added Calendar screenshots.
- Updated the report-generation timing example.

## Version 0.3.8 — October 2026

### New features
- Added an option to include or exclude Statistics from the generated website.
- Added the Notable Records feature, displaying records such as ages, marriages and family sizes, with selectable record counts.

### Corrections
- Corrected GEDCOM generation for the Topola Tree Viewer to respect the selected Person filter, including custom filters.
- Corrected Lifespans diagrams to exclude individuals omitted by the Person filter.
- Improved compatibility with custom filters that depend on the active person.

### Important
Users who previously generated websites using Person filters to exclude particular individuals should regenerate their websites with this release to ensure the exported GEDCOM applies those restrictions.

## Version 0.3.7 — October 2026

### New features and improvements
- Added expandable individual details.
- Added additional website themes.
- Improved individual and family event maps.
- Added nickname support to individual searches.
- Added persistent tabbed-panel preferences.
- Renamed Visitor Guide to Quick Guide.
- Improved documentation and help links.