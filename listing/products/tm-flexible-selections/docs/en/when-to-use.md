---
title: When to use Tm Flexible Selections
---

## Good fit when

- A sheet needs selections for several fields in one object.
- Different fields need different controls, such as a tile list for Region and a dropdown for Category.
- People need to choose app field values directly, or to switch between a short list of related fields.
- A date field, an editable app variable or the app's bookmarks need a dedicated control.

The object needs fields in the app for field selections. A master dimension can be used instead of typing a field name. Date range needs date values. Variable mode needs an existing variable that can be changed, and bookmark mode needs bookmarks in the app.

## Not a good fit when

- An existing object uses the old Flexible Selections extension: those objects are not converted. Rebuild the selections in this extension or use the native Qlik filter pane.
- A list has more than 2,000 values and users cannot search for the rest. Scrolling loads at most 2,000 rows; use search, or use the native Qlik filter pane for a different filtering layout.
- A button bar must display every value. It keeps a few buttons and uses search for the rest; choose a dropdown or list with check boxes for a larger set.
- The date entry format must be identical for every viewer. Date inputs follow the viewer's browser format and locale; use another display, such as a dropdown, if that does not fit.
- A project requires screen-reader behavior already tested with NVDA or VoiceOver. Those checks have not been done for this object; evaluate the native Qlik filter pane with the assistive technology and host you support, or check this object before relying on it.
