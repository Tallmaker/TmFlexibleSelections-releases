---
title: Settings
---

## Fields

Add up to 50 field entries, then move or remove them as needed. Several controls appear only for the selected display or sorting and colour choices.

### Field

Names the app field to select from. Values: a field name or expression. Default: none is set. Change it to the field whose values people should select. For a master dimension, choose it in **Master dimension (instead of the field)** instead.

### Label

Sets the heading shown for the field. Values: text or an expression. Default: none is set; the field name is used when no label is supplied. Change it when the app's field name needs a clearer heading.

### Master dimension (instead of the field)

Uses one of the app's master dimensions in place of the field name. Values: **None (use the field)** or a master dimension available in the app. Default: **None (use the field)**. Change it when this selection should use a master dimension and its colours. A custom value order or date range also needs the field name in **Field**.

### Variable name

Names the app variable used by the Variable display. Values: an existing variable name that does not need quoting. Default: blank. Change it to the variable the control should set. Formula variables and Qlik system variables cannot be changed here.

### Bookmarks to show

Limits the bookmarks shown by the Bookmarks display. Values: **All the user can see**, **Public bookmarks only**, or **The user’s own private bookmarks only**. Default: **All the user can see**. Change it to show only the audience's public bookmarks or the current user's private bookmarks.

### Variable control

Chooses the control used by the Variable display. Values: **Buttons**, **Radio list**, **Select list**, or **Slider**. Default: **Buttons**. Change it to suit the available space or the variable's values.

### Values (one per line, Label=value or value)

Lists the choices for a button, radio or select variable control. Use up to 50 values, one per line; add a label before an equals sign to show different text. Default: blank. Change it when users should choose from a fixed set of values. This setting is hidden for the slider control.

### Slider minimum

Sets the low end of the Variable slider. Values: numbers, including decimals. Default: 0. Change it to match the low end of the variable's useful range. Shown only when **Variable control** is **Slider**.

### Slider maximum

Sets the high end of the Variable slider. Values: numbers, including decimals. Default: 100. Change it to match the high end of the variable's useful range. Shown only when **Variable control** is **Slider**.

### Slider step

Sets how much the Variable slider changes in one step. Values: positive numbers, including decimals. Default: 1. Change it when the variable needs finer or larger increments. Shown only when **Variable control** is **Slider**.

### Other fields the user can switch to (one per line, up to 5)

Adds other fields that can take turns in this entry's display. Values: up to five field names, one per line. Default: blank. Change it when users need to compare or choose from related fields in the same space.

### Display as

Chooses how values appear and behave. Values: **Tiles**, **Dropdown**, **List with check boxes**, **Button bar**, **Radio list**, **Toggle switch (two values)**, **Date range**, **Variable (set a value)**, or **Bookmarks**. Default: **Tiles**. Change it to suit the field and the way users should select. See [Displays](modes.md).

### Section

Groups field entries under a numbered section heading. Values: 1 to 20. Default: 1. Change it to separate groups of filters.

### Order in section (lower first)

Sets this entry's order within its section. Values: -999 to 999; lower numbers come first. Default: 0 when unset. Change it to move an entry earlier or later within the same section.

### Show label

Shows or hides the field heading. Values: **On** or **Off**. Default: **On**. Change it when the field heading is redundant in the layout.

### Show value text

Shows or hides the text for each value. Values: **On** or **Off**. Default: **On**. Change it when the values are already clear from another visual cue.

### Frequency

Shows how often each value occurs. Values: **Off**, **Count**, **Percent**, or **Relative**. Default: **Off**. Change it when people need to compare how common the values are.

### Bars behind values

Adds a small bar to show each value's relative frequency. Values: **On** or **Off**. Default: **Off**. Change it when a quick visual comparison helps. The bar is available with displays that show value tiles.

### Sort by

Chooses the order of values. Values: **Load order**, **Selected first**, **Text**, **Number**, **Frequency**, **My own order**, or **Expression**. Default: **Load order**. Change it when users need a meaningful order. **My own order** and **Expression** reveal another setting.

### Descending

Reverses the selected sort order. Values: **On** or **Off**. Default: **Off**. Change it when the largest, latest or last value should appear first.

### Values in order, one per line

Sets the order for **My own order**. Values: one field value per line, in the order to show. Default: blank. Change it when a specific business order is more useful than the field's load order. Shown only when **Sort by** is **My own order**.

### Sort expression

Orders values by a Qlik expression. Values: an expression. Default: blank. Change it when a calculated order is needed. Shown only when **Sort by** is **Expression**.

### Colour values by

Chooses how values get their colour. Values: **Qlik state colours**, **Expression**, or **Master dimension colours** when a master dimension is selected. Default: **Qlik state colours**. Change it when colour should show a measure or follow the selected master dimension's colour map. Expression and master dimension colours reveal related settings.

### Colour expression

Sets the expression used to colour values. Values: a Qlik expression. Default: blank. Change it when values should use colours calculated by the expression. Shown when **Colour values by** is **Expression**.

### Colour caption (what the colours mean)

Adds a caption explaining an expression or master-dimension colour. Values: text or an expression. Default: blank. Change it when viewers need a key to understand what the colours represent.

### Apply colours to

Chooses which unselected values can receive expression or master-dimension colours. Values: **Possible values** or **All unselected values**. Default: **Possible values**. Change it when alternative or excluded values should also carry the colours.

### Hide empty values

Hides empty values from the list. Values: **On** or **Off**. Default: **On**. Change it to show empty values when they matter to the analysis.

### Search box

Shows a search field for finding values. Values: **On** or **Off**. Default: **Off**. Change it when people need to find a value in a long list. Search is also offered when a list reaches its loaded-row limit.

### Single value

Allows only one value to be selected at a time. Values: **On** or **Off**. Default: **Off**. Change it for a field where selections should replace one another rather than accumulate.

### Values to show

Sets how many values are loaded at a time for this field. Values: 10 to 1,000. Default: 200. Change it when a different initial number of values suits the sheet. More values can load as the user scrolls; search finds values beyond the list limit.

### Images

Adds an image beside matching values. Values: **None**, the built-in currency flags, or an image list created in **Presentation**. Default: **None**. Change it when an image helps identify each value.

### Text when nothing is selected

Sets the text shown by a closed dropdown when nothing is selected. Values: text. Default: **All**. Change it to use wording that fits the app. Shown only for **Dropdown**.

## Presentation

### Preset

Applies a starting look to the object. Values: **Standard**, **List box**, **Pills**, **Check box**, **Selection dots**, **Bold**, **Segmented control**, **Qlik filter pane**, or **Cards**. Default: **Standard**. Change it to start from a familiar look; each preset can be adjusted afterwards in Presentation and Styling.

### Layout

Arranges tile values. Values: **Across**, **Down**, or **Grid**. Default: **Across**. Change it to fit the shape of the sheet or the number of values.

### Columns

Sets the number of columns in a grid. Values: 1 to 12. Default: 3. Change it when a grid needs more or fewer columns. Shown only when **Layout** is **Grid**.

### Rows to show before scrolling (0 shows all)

Limits the visible grid height before it scrolls. Values: 0 to 50 rows. Default: 0, which shows all rows. Change it to keep a grid within a set height. Shown only when **Layout** is **Grid**.

### Fill the grid

Chooses how values fill a grid. Values: **By rows** or **By columns**. Default: **By rows**. Change it when the reading order should run down columns instead of across rows. Shown only when **Layout** is **Grid**.

### Wrap values onto new lines

Allows values to continue on another line when they do not fit. Values: **On** or **Off**. Default: **On**. Change it when values should stay on one line or wrap within the object.

### Stretch values to fill the width

Stretches value tiles across the available width. Values: **On** or **Off**. Default: **Off**. Change it when the values should share the full row width.

### Stretch fields to fill the width

Stretches field entries across the available width. Values: **On** or **Off**. Default: **Off**. Change it when the fields should share the full row width.

### Value alignment

Sets how value tiles are spaced. Values: **Start**, **Centre**, **End**, **Spread, edges first**, **Spread, space around**, or **Spread evenly**. Default: **Start**. Change it when values should be centred, aligned to the end or spread across their area.

### Label placement

Sets where each field label appears. Values: **Above**, **Before**, **After**, or **Below**. Default: **Above**. Change it to place the label beside or under its values.

### Label rotation

Rotates the field label in the across or grid layout. Values: **None**, **Down**, or **Up**. Default: **None**. Change it when vertical labels make better use of space.

### Label placement in the down layout

Sets label placement when **Layout** is **Down**. Values: **Same as above**, **Above**, **Before**, **After**, or **Below**. Default: **Same as above**. Change it when labels need a different position in a down layout.

### Label rotation in the down layout

Sets label rotation when **Layout** is **Down**. Values: **Same**, **None**, **Down**, or **Up**. Default: **Same**. Change it when down-layout labels need a different rotation.

### Check mark

Chooses the mark for a selected value. Values: **Tick**, **Dot**, **Star**, **Cross**, **Check box**, **Radio button**, or **None**. Default: **Tick**. Change it when a different mark better matches the intended look.

### Mark on alternative values

Adds a mark to alternative values. Values: **None**, **Dot**, **Star**, or **Cross**. Default: **None**. Change it to give alternative values a non-colour cue.

### Mark on excluded values

Adds a mark to excluded values. Values: **None**, **Dot**, **Star**, or **Cross**. Default: **None**. Change it to make excluded values easier to distinguish.

### Mark on locked values

Chooses the mark for locked values. Values: **Lock**, **Dot**, **Star**, or **Cross**. Default: **Lock**. Change it when a different mark fits the design while still making the locked state clear.

### Mark as text (up to 4 characters, instead of the icon)

Replaces the selected-value icon with text. Values: up to four characters. Default: blank. Change it when a short symbol or label is clearer than an icon.

### Section alignment

Sets how field sections are spaced. Values: **Start**, **Centre**, **End**, **Spread, edges first**, **Spread, space around**, or **Spread evenly**. Default: **Start**. Change it when sections should be centred or spread across the object.

### Image lists

Creates image lists that can be selected in a field's **Images** setting. Values: up to 20 lists; add, remove or reorder them. Default: no lists. Change it when particular values should show their own images.

### Name

Names an image list. Values: text. Default: **My images**. Change it to make the list easy to identify in a field's **Images** choices.

### One per line: value = image address (https)

Maps each field value to an image address. Values: one value and HTTPS image address per line, separated by an equals sign. Default: blank. Change it to add images for the values in a selected image list.

### Image for values a list does not name (https)

Sets a fallback image when the chosen list has no image for a value. Values: an HTTPS image address. Default: blank. Change it when unmatched values should share an image.

### Show only when (expression)

Controls whether the selectors appear. Values: a Qlik expression. Default: none is set. Change it when the whole object should be conditional.

### Message when hidden

Sets the message shown while the selectors are hidden by the condition. Values: text or an expression. Default: none is set. Change it to explain why the controls are not available. Shown when **Show only when (expression)** is set.

### Tile shape rules (shape: Custom)

Adds up to eight rules for tile corners and border widths by position. Values: rules can be added, removed and reordered. Default: no rules. Change it after choosing **Custom** under **Tile shape** in Styling.

### Values at

Chooses a position for the rule. Values: **First value**, **Last value**, **Only value**, **Middle values**, **Top row (grid)**, **Bottom row (grid)**, **First column (grid)**, or **Last column (grid)**. Default: **First value**. Change it to target values by their position.

### And also at

Adds another position that must match. Values: **Anywhere** or the same positions as **Values at**. Default: **Anywhere**. Change it when a rule should apply only where both positions match.

### Corner: start of first line

Sets the first corner radius for a shape rule. Values: 0 to 64 pixels. Default: unset, so the selected tile shape supplies it. Change it to round or square that corner.

### Corner: end of first line

Sets the opposite corner radius on the first line. Values: 0 to 64 pixels. Default: unset, so the selected tile shape supplies it. Change it to set that corner separately.

### Corner: start of last line

Sets the first corner radius on the last line. Values: 0 to 64 pixels. Default: unset, so the selected tile shape supplies it. Change it to set that corner separately.

### Corner: end of last line

Sets the opposite corner radius on the last line. Values: 0 to 64 pixels. Default: unset, so the selected tile shape supplies it. Change it to set that corner separately.

### Border width: top

Sets the top border width for a shape rule. Values: 0 to 64 pixels. Default: unset. Change it to adjust the top edge at matching positions.

### Border width: bottom

Sets the bottom border width for a shape rule. Values: 0 to 64 pixels. Default: unset. Change it to adjust the bottom edge at matching positions.

### Border width: start side

Sets the start-side border width for a shape rule. Values: 0 to 64 pixels. Default: unset. Change it to adjust that edge at matching positions.

### Border width: end side

Sets the end-side border width for a shape rule. Values: 0 to 64 pixels. Default: unset. Change it to adjust that edge at matching positions.

### Copy settings

Copies this object's settings so they can be reused on another object. Values: action button; no value is stored here. Default: not applicable. Use it when another object should start with the same selections setup and look.

### Paste copied settings here

Applies settings copied from another object. Values: paste the copied settings text. Default: blank. Use it to reuse the other object's field settings and look.

### Confirm selections with the Qlik toolbar

Holds selections until the user confirms them with the Qlik toolbar. Values: **On** or **Off**. Default: **Off**, so picks apply at once. Change it when users should review a group of picks before applying them.

### Font size

Sets the size of value text. Values: **Theme default**, 10, 11, 12, 13, 14, 16, 18, 20 or 24 pixels. Default: **Theme default**. Change it to make values easier to read or fit more values.

### Inner spacing

Sets the space inside a value tile. Values: 0 to 32 pixels. Default: 6 pixels vertically and 12 horizontally. The value sets vertical spacing, with twice that spacing horizontally. Change it to make tiles roomier or more compact.

### Border colour

Sets the value tile border colour. Values: a colour picker. Default: light grey (#d9d9d9). Change it to make the tile edge more or less visible.

### Bar colour

Sets the colour of frequency bars. Values: a colour picker. Default: grey (#767676). Change it when the frequency bars should use another colour.

### Selected background

Sets the background for selected values. Values: a colour picker. Default: green (#009845). Change it to fit the app's selection colour.

### Selected text

Sets the text colour for selected values. Values: a colour picker. Default: white. Change it when the selected background needs different text contrast.

### Possible background

Sets the background for possible values. Values: a colour picker. Default: white. Change it to distinguish possible values from other states.

### Possible text

Sets the text colour for possible values. Values: a colour picker. Default: dark grey (#262626). Change it when the possible-value background needs different text contrast.

### Alternative background

Sets the background for alternative values. Values: a colour picker. Default: light grey (#e4e4e4). Change it to fit the app's state colours.

### Alternative text

Sets the text colour for alternative values. Values: a colour picker. Default: dark grey (#262626). Change it when the alternative background needs different text contrast.

### Excluded background

Sets the background for excluded values. Values: a colour picker. Default: grey (#a9a9a9). Change it to fit the app's state colours.

### Excluded text

Sets the text colour for excluded values. Values: a colour picker. Default: dark grey (#262626). Change it when the excluded background needs different text contrast.

### Locked background

Sets the background for locked values. Values: a colour picker. Default: grey (#7b7a78). Change it to fit the app's state colours.

### Locked text

Sets the text colour for locked values. Values: a colour picker. Default: white. Change it when the locked background needs different text contrast.

### Font

Sets the value font. Values: **Theme font**, **Source Sans**, **Inter**, **Arial**, **Georgia**, or **Courier New**. Default: **Theme font**. Change it to use a different typeface for values.

### Weight

Sets the value font weight. Values: **Theme default**, 300, 400, 500, 600, or 700. Default: **Theme default**. Change it to make value text lighter or heavier.

### Alignment

Sets value text alignment. Values: **Default**, **Start**, **Center**, or **End**. Default: **Default**. Change it to align value text within a tile.

### Outer spacing

Sets space outside a value tile. Values: 0 to 48 pixels. Default: 0. Change it to separate tiles from nearby content.

### Outer spacing: set each side

Shows separate outer spacing controls for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set the sides separately.

### Outer spacing: top

Sets the outer spacing above a value tile. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: end

Sets the outer spacing at the end side of a value tile. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: bottom

Sets the outer spacing below a value tile. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: start

Sets the outer spacing at the start side of a value tile. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Space between mark, image, text and frequency

Sets the gap between the parts of a value tile. Values: 0 to 32 pixels. Default: 6. Change it when its mark, image, text or frequency needs more or less room.

### Inner spacing: set each side

Shows separate inner spacing controls for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set tile padding on each side.

### Inner spacing: top

Sets the inner spacing above the tile content. Values: 0 to 48 pixels. Default: 4. Shown when **Inner spacing: set each side** is On.

### Inner spacing: end

Sets the inner spacing at the end side of the tile. Values: 0 to 48 pixels. Default: 4. Shown when **Inner spacing: set each side** is On.

### Inner spacing: bottom

Sets the inner spacing below the tile content. Values: 0 to 48 pixels. Default: 4. Shown when **Inner spacing: set each side** is On.

### Inner spacing: start

Sets the inner spacing at the start side of the tile. Values: 0 to 48 pixels. Default: 4. Shown when **Inner spacing: set each side** is On.

## Field box

### Background colour

Sets the field box background. Values: a colour picker. Default: white. Change it to separate the field from the object background.

### Border colour

Sets the field box border colour. Values: a colour picker. Default: light grey (#d9d9d9). Change it when the edge needs more or less contrast.

### Border width

Sets the width of all field box borders. Values: 0 to 16 pixels. Default: 0. Change it to add or strengthen an outline.

### Border width: set each side

Shows a separate width for each field box edge. Values: **On** or **Off**. Default: **Off**. Turn it on to set the edges independently.

### Border width: top

Sets the top border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: end

Sets the end-side border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: bottom

Sets the bottom border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: start

Sets the start-side border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Corner radius

Rounds all field box corners equally. Values: 0 to 64 pixels. Default: 0. Change it for square or rounded corners.

### Corner radius: set each side

Shows a separate radius for each corner. Values: **On** or **Off**. Default: **Off**. Turn it on to set corners independently.

### Corner radius: top start

Sets the top-start corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: top end

Sets the top-end corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: bottom end

Sets the bottom-end corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: bottom start

Sets the bottom-start corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Inner spacing

Sets space between the field box edge and its contents. Values: 0 to 48 pixels. Default: 0. Change it to add room inside the field box.

### Inner spacing: set each side

Shows a separate inner spacing value for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set sides independently.

### Inner spacing: top

Sets the field box's top inner spacing. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: end

Sets the field box's end-side inner spacing. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: bottom

Sets the field box's bottom inner spacing. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: start

Sets the field box's start-side inner spacing. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Outer spacing

Sets space outside the field box. Values: 0 to 48 pixels. Default: 0. Change it to separate this field from nearby content.

### Outer spacing: set each side

Shows a separate outer spacing value for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set sides independently.

### Outer spacing: top

Sets the field box's top outer spacing. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: end

Sets the field box's end-side outer spacing. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: bottom

Sets the field box's bottom outer spacing. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: start

Sets the field box's start-side outer spacing. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Space between label and values

Sets the gap between the field label and its values. Values: 0 to 32 pixels. Default: 4. Change it to bring the label closer or leave more room.

## Field labels

### Font size

Sets the field label size. Values: **Theme default**, 10, 11, 12, 13, 14, 16, 18, 20 or 24 pixels. Default: 14 pixels, with a 1.2 line height. **Theme default** keeps the theme size. Change it to make field labels easier to read.

### Text colour

Sets the field label colour. Values: a colour picker. Default: #404040. Change it to fit the app's contrast and palette.

### Weight

Sets the field label weight. Values: **Bold** or **Regular**. Default: **Bold**. Change it when labels should be lighter or less prominent.

### Font

Sets the field label font. Values: **Theme font**, **Source Sans**, **Inter**, **Arial**, **Georgia**, or **Courier New**. Default: **Theme font**. Change it to use another typeface.

### Alignment

Sets field label alignment. Values: **Default**, **Start**, **Center**, or **End**. Default: **Default**. Change it to align labels within their field boxes.

### Background colour

Sets the field label background. Values: a colour picker. Default: white. Change it when labels need a contrasting background.

### Border colour

Sets the field label border colour. Values: a colour picker. Default: light grey (#d9d9d9). Change it when the label edge needs more or less contrast.

### Border width

Sets all field label border widths. Values: 0 to 16 pixels. Default: 0. Change it to add an outline around the label.

### Border width: set each side

Shows a separate border width for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set the label edges independently.

### Border width: top

Sets the top label border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: end

Sets the end-side label border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: bottom

Sets the bottom label border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: start

Sets the start-side label border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Corner radius

Rounds all field label corners equally. Values: 0 to 64 pixels. Default: 0. Change it for square or rounded labels.

### Corner radius: set each side

Shows a separate radius for each corner. Values: **On** or **Off**. Default: **Off**. Turn it on to set corners independently.

### Corner radius: top start

Sets the top-start label corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: top end

Sets the top-end label corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: bottom end

Sets the bottom-end label corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: bottom start

Sets the bottom-start label corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Inner spacing

Sets space inside the field label. Values: 0 to 48 pixels. Default: 0. Change it to add room around the label text.

### Inner spacing: set each side

Shows separate inner spacing controls for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set sides independently.

### Inner spacing: top

Sets the top inner spacing for a field label. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: end

Sets the end-side inner spacing for a field label. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: bottom

Sets the bottom inner spacing for a field label. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: start

Sets the start-side inner spacing for a field label. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Outer spacing

Sets space outside a field label. Values: 0 to 48 pixels. Default: 0. Change it to separate the label from nearby content.

### Outer spacing: set each side

Shows separate outer spacing controls for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set sides independently.

### Outer spacing: top

Sets the top outer spacing for a field label. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: end

Sets the end-side outer spacing for a field label. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: bottom

Sets the bottom outer spacing for a field label. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: start

Sets the start-side outer spacing for a field label. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Space before the selection dot

Sets the gap before the selection dot. Values: 0 to 32 pixels. Default: 6. Change it when the dot needs more or less separation from its label.

## Value area

### Background colour

Sets the background behind a field's values. Values: a colour picker. Default: white. Change it to distinguish the value area from the field box.

### Border colour

Sets the value area border colour. Values: a colour picker. Default: light grey (#d9d9d9). Change it when the edge needs more or less contrast.

### Border width

Sets all value area border widths. Values: 0 to 16 pixels. Default: 0. Change it to add an outline around the values.

### Border width: set each side

Shows a separate width for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set edges independently.

### Border width: top

Sets the top value area border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: end

Sets the end-side value area border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: bottom

Sets the bottom value area border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: start

Sets the start-side value area border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Corner radius

Rounds all value area corners equally. Values: 0 to 64 pixels. Default: 0. Change it for square or rounded corners.

### Corner radius: set each side

Shows a separate radius for each corner. Values: **On** or **Off**. Default: **Off**. Turn it on to set corners independently.

### Corner radius: top start

Sets the top-start value area corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: top end

Sets the top-end value area corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: bottom end

Sets the bottom-end value area corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: bottom start

Sets the bottom-start value area corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Inner spacing

Sets space between the value area edge and its contents. Values: 0 to 48 pixels. Default: 0. Change it to add room inside the value area.

### Inner spacing: set each side

Shows a separate inner spacing value for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set sides independently.

### Inner spacing: top

Sets the top inner spacing for the value area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: end

Sets the end-side inner spacing for the value area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: bottom

Sets the bottom inner spacing for the value area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: start

Sets the start-side inner spacing for the value area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Outer spacing

Sets space outside the value area. Values: 0 to 48 pixels. Default: 0. Change it to separate the value area from nearby content.

### Outer spacing: set each side

Shows separate outer spacing controls for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set sides independently.

### Outer spacing: top

Sets the top outer spacing for the value area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: end

Sets the end-side outer spacing for the value area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: bottom

Sets the bottom outer spacing for the value area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: start

Sets the start-side outer spacing for the value area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

## Check marks

### Mark colour

Sets the main check mark colour. Values: a colour picker. Default: white. Change it when the mark needs more contrast against the value background.

### Mark size

Sets the check mark size. Values: **Theme default**, 10, 11, 12, 13, 14, 16, 18, 20 or 24 pixels. Default: **Theme default**. Change it to make marks easier to see.

### Position

Places the mark before or after the value text. Values: **Before the value** or **After the value**. Default: **Before the value**. Change it to suit the reading order.

### Selected mark colour

Sets the mark colour for selected values. Values: a colour picker. Default: #404040. Change it when the selected mark needs a different contrast.

### Possible mark colour

Sets the mark colour for possible values. Values: a colour picker. Default: #404040. Change it when the possible-value mark needs a different contrast.

### Alternative mark colour

Sets the mark colour for alternative values. Values: a colour picker. Default: #404040. Change it when the alternative-state mark needs a different contrast.

### Excluded mark colour

Sets the mark colour for excluded values. Values: a colour picker. Default: #404040. Change it when the excluded-state mark needs a different contrast.

### Locked mark colour

Sets the mark colour for locked values. Values: a colour picker. Default: #404040. Change it when the locked-state mark needs a different contrast.

### Mark box width

Sets the mark area width. Values: 0 to 64 pixels. Default: 0, which leaves its width to the mark size. Change it to reserve a wider or narrower mark area.

### Mark box height

Sets the mark area height. Values: 0 to 64 pixels. Default: 0. Change it to give marks a fixed-height area.

### Selected mark background

Sets the background behind marks for selected values. Values: a colour picker. Default: white. Change it when the mark area needs a background.

### Possible mark background

Sets the background behind marks for possible values. Values: a colour picker. Default: white. Change it when the mark area needs a background.

### Alternative mark background

Sets the background behind marks for alternative values. Values: a colour picker. Default: white. Change it when the mark area needs a background.

### Excluded mark background

Sets the background behind marks for excluded values. Values: a colour picker. Default: white. Change it when the mark area needs a background.

### Locked mark background

Sets the background behind marks for locked values. Values: a colour picker. Default: white. Change it when the mark area needs a background.

### Font

Sets the font used around the check mark. Values: **Theme font**, **Source Sans**, **Inter**, **Arial**, **Georgia**, or **Courier New**. Default: **Theme font**. Change it to use a different typeface.

### Weight

Sets the font weight used around the check mark. Values: **Theme default**, 300, 400, 500, 600, or 700. Default: **Theme default**. Change it to make that text lighter or heavier.

### Alignment

Sets alignment in the mark area. Values: **Default**, **Start**, **Center**, or **End**. Default: **Default**. Change it to align the mark-area content.

### Border colour

Sets the mark area border colour. Values: a colour picker. Default: light grey (#d9d9d9). Change it when the mark edge needs more or less contrast.

### Border width

Sets all mark area border widths. Values: 0 to 16 pixels. Default: 0. Change it to add an outline around the mark area.

### Border width: set each side

Shows separate border widths for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set edges independently.

### Border width: top

Sets the top mark area border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: end

Sets the end-side mark area border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: bottom

Sets the bottom mark area border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: start

Sets the start-side mark area border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Corner radius

Rounds all mark area corners equally. Values: 0 to 64 pixels. Default: 0. Change it to round the mark area.

### Corner radius: set each side

Shows a separate radius for each corner. Values: **On** or **Off**. Default: **Off**. Turn it on to set corners independently.

### Corner radius: top start

Sets the top-start mark area corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: top end

Sets the top-end mark area corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: bottom end

Sets the bottom-end mark area corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: bottom start

Sets the bottom-start mark area corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Inner spacing

Sets space inside the mark area. Values: 0 to 48 pixels. Default: 0. Change it to add room around the mark.

### Inner spacing: set each side

Shows separate inner spacing values for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set sides independently.

### Inner spacing: top

Sets top inner spacing in the mark area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: end

Sets end-side inner spacing in the mark area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: bottom

Sets bottom inner spacing in the mark area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: start

Sets start-side inner spacing in the mark area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Outer spacing

Sets space outside the mark area. Values: 0 to 48 pixels. Default: 0. Change it to separate the mark from surrounding content.

### Outer spacing: set each side

Shows separate outer spacing values for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set sides independently.

### Outer spacing: top

Sets top outer spacing for the mark area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: end

Sets end-side outer spacing for the mark area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: bottom

Sets bottom outer spacing for the mark area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: start

Sets start-side outer spacing for the mark area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

## Value text

### Font

Sets the value text font. Values: **Theme font**, **Source Sans**, **Inter**, **Arial**, **Georgia**, or **Courier New**. Default: **Theme font**. Change it to use a different typeface.

### Weight

Sets the value text weight. Values: **Theme default**, 300, 400, 500, 600, or 700. Default: **Theme default**. Change it to make values lighter or heavier.

### Alignment

Sets value text alignment. Values: **Default**, **Start**, **Center**, or **End**. Default: **Default**. Change it to align text within each value.

### Text colour

Sets the value text colour. Values: a colour picker. Default: #404040. Change it when value text needs another colour.

### Background colour

Sets the value text area's background. Values: a colour picker. Default: white. Change it when the text area needs a background.

### Border colour

Sets the value text area's border colour. Values: a colour picker. Default: light grey (#d9d9d9). Change it when the edge needs more or less contrast.

### Border width

Sets all value text area border widths. Values: 0 to 16 pixels. Default: 0. Change it to add an outline.

### Border width: set each side

Shows separate border widths for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set edges independently.

### Border width: top

Sets the top border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: end

Sets the end-side border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: bottom

Sets the bottom border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: start

Sets the start-side border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Corner radius

Rounds all value text area corners equally. Values: 0 to 64 pixels. Default: 0. Change it to round the text area.

### Corner radius: set each side

Shows a separate radius for each corner. Values: **On** or **Off**. Default: **Off**. Turn it on to set corners independently.

### Corner radius: top start

Sets the top-start corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: top end

Sets the top-end corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: bottom end

Sets the bottom-end corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: bottom start

Sets the bottom-start corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Inner spacing

Sets space inside the value text area. Values: 0 to 48 pixels. Default: 0. Change it to add room around the text.

### Inner spacing: set each side

Shows separate inner spacing controls for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set sides independently.

### Inner spacing: top

Sets top inner spacing for the value text area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: end

Sets end-side inner spacing for the value text area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: bottom

Sets bottom inner spacing for the value text area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: start

Sets start-side inner spacing for the value text area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Outer spacing

Sets space outside the value text area. Values: 0 to 48 pixels. Default: 0. Change it to separate text from nearby content.

### Outer spacing: set each side

Shows separate outer spacing controls for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set sides independently.

### Outer spacing: top

Sets top outer spacing for the value text area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: end

Sets end-side outer spacing for the value text area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: bottom

Sets bottom outer spacing for the value text area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: start

Sets start-side outer spacing for the value text area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Letter spacing

Sets the space between value text letters. Values: 0 to 10 pixels. Default: 0. Change it to spread letters farther apart.

## Images

### Image height

Sets image height. Values: 8 to 96 pixels. Default: 20. Change it to make value images larger or smaller.

### Image fit

Chooses how an image fits its box. Values: **Whole image**, **Fill the box**, or **Stretch**. Default: **Whole image**. Change it when the image should fill or stretch to its box.

### Image width (0 keeps its shape)

Sets image width. Values: 0 to 160 pixels. Default: 0, which keeps the image's proportions. Change it to give images a fixed width.

### Background colour

Sets the image area's background. Values: a colour picker. Default: white. Change it when the image area needs a background.

### Border colour

Sets the image border colour. Values: a colour picker. Default: light grey (#d9d9d9). Change it when the image edge needs more or less contrast.

### Border width

Sets all image border widths. Values: 0 to 16 pixels. Default: 0. Change it to add an outline around images.

### Border width: set each side

Shows separate border widths for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set edges independently.

### Border width: top

Sets the top image border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: end

Sets the end-side image border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: bottom

Sets the bottom image border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: start

Sets the start-side image border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Corner radius

Rounds all image corners equally. Values: 0 to 64 pixels. Default: 0. Change it to round image corners.

### Corner radius: set each side

Shows a separate radius for each image corner. Values: **On** or **Off**. Default: **Off**. Turn it on to set corners independently.

### Corner radius: top start

Sets the image's top-start corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: top end

Sets the image's top-end corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: bottom end

Sets the image's bottom-end corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: bottom start

Sets the image's bottom-start corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Inner spacing

Sets space inside the image area. Values: 0 to 48 pixels. Default: 0. Change it to add room around the image.

### Inner spacing: set each side

Shows separate inner spacing controls for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set sides independently.

### Inner spacing: top

Sets top inner spacing for the image area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: end

Sets end-side inner spacing for the image area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: bottom

Sets bottom inner spacing for the image area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: start

Sets start-side inner spacing for the image area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Outer spacing

Sets space outside the image area. Values: 0 to 48 pixels. Default: 0. Change it to separate images from nearby content.

### Outer spacing: set each side

Shows separate outer spacing controls for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set sides independently.

### Outer spacing: top

Sets top outer spacing for the image area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: end

Sets end-side outer spacing for the image area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: bottom

Sets bottom outer spacing for the image area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: start

Sets start-side outer spacing for the image area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

## Frequency

### Font size

Sets the frequency text size. Values: **Theme default**, 10, 11, 12, 13, 14, 16, 18, 20 or 24 pixels. Default: **Theme default**. Change it to make frequency easier to read.

### Text colour

Sets the frequency text colour. Values: a colour picker. Default: #595959. Change it when the frequency text needs another colour.

### Selected frequency colour

Sets the frequency colour for selected values. Values: a colour picker. Default: #404040. Change it to distinguish this state.

### Possible frequency colour

Sets the frequency colour for possible values. Values: a colour picker. Default: #404040. Change it to distinguish this state.

### Alternative frequency colour

Sets the frequency colour for alternative values. Values: a colour picker. Default: #404040. Change it to distinguish this state.

### Excluded frequency colour

Sets the frequency colour for excluded values. Values: a colour picker. Default: #404040. Change it to distinguish this state.

### Locked frequency colour

Sets the frequency colour for locked values. Values: a colour picker. Default: #404040. Change it to distinguish this state.

### Position

Places frequency text after or before the value, or at the end of the row. Values: **After the value**, **Before the value**, or **At the end**. Default: **After the value**. Change it to suit the available space.

### Frequency box width

Sets the frequency area width. Values: 0 to 120 pixels. Default: 0. Change it when frequencies should line up in a fixed-width area.

### Frequency box height

Sets the frequency area height. Values: 0 to 64 pixels. Default: 0. Change it when the frequency needs a fixed-height area.

### Selected frequency background

Sets the background behind frequency for selected values. Values: a colour picker. Default: white. Change it when the frequency area needs a background for this state.

### Possible frequency background

Sets the background behind frequency for possible values. Values: a colour picker. Default: white. Change it when the frequency area needs a background for this state.

### Alternative frequency background

Sets the background behind frequency for alternative values. Values: a colour picker. Default: white. Change it when the frequency area needs a background for this state.

### Excluded frequency background

Sets the background behind frequency for excluded values. Values: a colour picker. Default: white. Change it when the frequency area needs a background for this state.

### Locked frequency background

Sets the background behind frequency for locked values. Values: a colour picker. Default: white. Change it when the frequency area needs a background for this state.

### Font

Sets the frequency font. Values: **Theme font**, **Source Sans**, **Inter**, **Arial**, **Georgia**, or **Courier New**. Default: **Theme font**. Change it to use another typeface.

### Weight

Sets the frequency font weight. Values: **Theme default**, 300, 400, 500, 600, or 700. Default: **Theme default**. Change it to make frequency lighter or heavier.

### Alignment

Sets frequency alignment. Values: **Default**, **Start**, **Center**, or **End**. Default: **Default**. Change it to align frequency within its area.

### Background colour

Sets the frequency area background. Values: a colour picker. Default: white. Change it when frequency needs a background.

### Border colour

Sets the frequency area border colour. Values: a colour picker. Default: light grey (#d9d9d9). Change it when the edge needs more or less contrast.

### Border width

Sets all frequency area border widths. Values: 0 to 16 pixels. Default: 0. Change it to add an outline.

### Border width: set each side

Shows separate border widths for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set edges independently.

### Border width: top

Sets the top frequency area border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: end

Sets the end-side frequency area border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: bottom

Sets the bottom frequency area border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: start

Sets the start-side frequency area border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Corner radius

Rounds all frequency area corners equally. Values: 0 to 64 pixels. Default: 0. Change it to round the frequency area.

### Corner radius: set each side

Shows a separate radius for each corner. Values: **On** or **Off**. Default: **Off**. Turn it on to set corners independently.

### Corner radius: top start

Sets the top-start frequency area corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: top end

Sets the top-end frequency area corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: bottom end

Sets the bottom-end frequency area corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: bottom start

Sets the bottom-start frequency area corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Inner spacing

Sets space inside the frequency area. Values: 0 to 48 pixels. Default: 0. Change it to add room around the frequency text.

### Inner spacing: set each side

Shows separate inner spacing controls for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set sides independently.

### Inner spacing: top

Sets top inner spacing for the frequency area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: end

Sets end-side inner spacing for the frequency area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: bottom

Sets bottom inner spacing for the frequency area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: start

Sets start-side inner spacing for the frequency area. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Outer spacing

Sets space outside the frequency area. Values: 0 to 48 pixels. Default: 0. Change it to separate the frequency from nearby content.

### Outer spacing: set each side

Shows separate outer spacing controls for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set sides independently.

### Outer spacing: top

Sets top outer spacing for the frequency area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: end

Sets end-side outer spacing for the frequency area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: bottom

Sets bottom outer spacing for the frequency area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: start

Sets start-side outer spacing for the frequency area. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

## Multi-select hint

### Hint text ({n} is the number picked)

Sets the message shown while multiple selections are being made. Values: text or an expression; use {n} for the number of values picked. Default: “{n} picked. Release the key to apply.” The default message follows the selector language. Change it to explain multi-select behavior in the app's wording.

### Animation

Chooses how the hint appears. Values: **Fade in**, **Slide in**, **Pop**, **Pulse**, **Flip**, **Bounce**, **Spin**, **Jump**, **Shake**, **Wobble**, or **None**. Default: **Fade in**. Change it to suit the page's motion and style.

### Background colour

Sets the hint background. Values: a colour picker. Default: green (#009845). Change it to fit the app's palette.

### Text colour

Sets the hint text colour. Values: a colour picker. Default: white. Change it to keep the text readable against its background.

### Font size

Sets the hint text size. Values: **Theme default**, 10, 11, 12, 13, 14, 16, 18, 20 or 24 pixels. Default: **Theme default**. Change it to make the hint easier to read.

### Font

Sets the hint font. Values: **Theme font**, **Source Sans**, **Inter**, **Arial**, **Georgia**, or **Courier New**. Default: **Theme font**. Change it to use another typeface.

### Weight

Sets the hint font weight. Values: **Theme default**, 300, 400, 500, 600, or 700. Default: **Theme default**. Change it to make the hint lighter or heavier.

### Alignment

Sets hint alignment. Values: **Default**, **Start**, **Center**, or **End**. Default: **Default**. Change it to align the hint text.

### Border colour

Sets the hint border colour. Values: a colour picker. Default: light grey (#d9d9d9). Change it when the hint edge needs more or less contrast.

### Border width

Sets all hint border widths. Values: 0 to 16 pixels. Default: 0. Change it to add an outline.

### Border width: set each side

Shows separate border widths for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set edges independently.

### Border width: top

Sets the top hint border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: end

Sets the end-side hint border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: bottom

Sets the bottom hint border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Border width: start

Sets the start-side hint border width. Values: 0 to 16 pixels. Default: 0. Shown when **Border width: set each side** is On.

### Corner radius

Rounds all hint corners equally. Values: 0 to 64 pixels. Default: 0. Change it to round the hint.

### Corner radius: set each side

Shows a separate radius for each corner. Values: **On** or **Off**. Default: **Off**. Turn it on to set corners independently.

### Corner radius: top start

Sets the top-start hint corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: top end

Sets the top-end hint corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: bottom end

Sets the bottom-end hint corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Corner radius: bottom start

Sets the bottom-start hint corner radius. Values: 0 to 64 pixels. Default: 0. Shown when **Corner radius: set each side** is On.

### Inner spacing

Sets space inside the hint. Values: 0 to 48 pixels. Default: 0. Change it to add room around the message.

### Inner spacing: set each side

Shows separate inner spacing controls for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set sides independently.

### Inner spacing: top

Sets top inner spacing for the hint. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: end

Sets end-side inner spacing for the hint. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: bottom

Sets bottom inner spacing for the hint. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Inner spacing: start

Sets start-side inner spacing for the hint. Values: 0 to 48 pixels. Default: 0. Shown when **Inner spacing: set each side** is On.

### Outer spacing

Sets space outside the hint. Values: 0 to 48 pixels. Default: 0. Change it to separate the hint from nearby content.

### Outer spacing: set each side

Shows separate outer spacing controls for each side. Values: **On** or **Off**. Default: **Off**. Turn it on to set sides independently.

### Outer spacing: top

Sets top outer spacing for the hint. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: end

Sets end-side outer spacing for the hint. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: bottom

Sets bottom outer spacing for the hint. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

### Outer spacing: start

Sets start-side outer spacing for the hint. Values: 0 to 48 pixels. Default: 0. Shown when **Outer spacing: set each side** is On.

## Selection dot

### Dot size (0 hides it)

Sets the selection dot size. Values: 0 to 24 pixels. Default: 0, which hides the dot. Change it when the field label should have a visible selection indicator.

### Dot colour

Sets the selection dot colour. Values: a colour picker. Default: green (#00be56). Change it to fit the app's palette.

### Dot roundness (%)

Sets how round the selection dot is. Values: 0 to 50 percent. Default: 25. Change it to make the indicator more or less rounded.

## Tile shape

### Tile shape

Chooses the shape of value tiles. Values: **Separate tiles**, **Joined row**, **Joined column**, **Card grid**, or **Custom**. Default: **Separate tiles**. Change it for separate buttons, joined controls, cards or position-based rules.

### Corner radius

Sets the corners of value tiles. Values: 0 to 64 pixels. Default: 6 for separate tiles. Change it for square or more rounded tiles.

### Border width

Sets tile border width. Values: 0 to 8 pixels. Default: 1. Change it to strengthen or remove tile outlines.

### Space between tiles

Sets the gap between tiles. Values: 0 to 32 pixels. Default: 6. Change it to bring separate tiles closer or spread them apart. This control is hidden for **Joined row** and **Joined column**.

## About

About shows product information, its version and a link to the product page. These are read-only details; there is no setting to change.

## License

When the object has no license, it shows a small License tab with license information. The tab is read-only and has no setting to change. The object can still be used without a license.
