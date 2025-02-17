.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the Tree.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_Tree:

Tree
====

**Inherits:** :ref:`Control<class_Control>` **<** :ref:`CanvasItem<class_CanvasItem>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

**Category:** Core

Brief Description
-----------------

Control to show a tree of items.

Properties
----------

+-----------------------------------------+---------------------------------------------------------------+-------+
| :ref:`bool<class_bool>`                 | :ref:`allow_reselect<class_Tree_property_allow_reselect>`     | false |
+-----------------------------------------+---------------------------------------------------------------+-------+
| :ref:`bool<class_bool>`                 | :ref:`allow_rmb_select<class_Tree_property_allow_rmb_select>` | false |
+-----------------------------------------+---------------------------------------------------------------+-------+
| :ref:`int<class_int>`                   | :ref:`columns<class_Tree_property_columns>`                   | 1     |
+-----------------------------------------+---------------------------------------------------------------+-------+
| :ref:`int<class_int>`                   | :ref:`drop_mode_flags<class_Tree_property_drop_mode_flags>`   | 0     |
+-----------------------------------------+---------------------------------------------------------------+-------+
| :ref:`bool<class_bool>`                 | :ref:`hide_folding<class_Tree_property_hide_folding>`         | false |
+-----------------------------------------+---------------------------------------------------------------+-------+
| :ref:`bool<class_bool>`                 | :ref:`hide_root<class_Tree_property_hide_root>`               | false |
+-----------------------------------------+---------------------------------------------------------------+-------+
| :ref:`SelectMode<enum_Tree_SelectMode>` | :ref:`select_mode<class_Tree_property_select_mode>`           | 0     |
+-----------------------------------------+---------------------------------------------------------------+-------+

Methods
-------

+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`         | :ref:`are_column_titles_visible<class_Tree_method_are_column_titles_visible>` **(** **)** const                                                     |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| void                            | :ref:`clear<class_Tree_method_clear>` **(** **)**                                                                                                   |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`TreeItem<class_TreeItem>` | :ref:`create_item<class_Tree_method_create_item>` **(** :ref:`Object<class_Object>` parent=null, :ref:`int<class_int>` idx=-1 **)**                 |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| void                            | :ref:`ensure_cursor_is_visible<class_Tree_method_ensure_cursor_is_visible>` **(** **)**                                                             |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`           | :ref:`get_column_at_position<class_Tree_method_get_column_at_position>` **(** :ref:`Vector2<class_Vector2>` position **)** const                    |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`     | :ref:`get_column_title<class_Tree_method_get_column_title>` **(** :ref:`int<class_int>` column **)** const                                          |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`           | :ref:`get_column_width<class_Tree_method_get_column_width>` **(** :ref:`int<class_int>` column **)** const                                          |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Rect2<class_Rect2>`       | :ref:`get_custom_popup_rect<class_Tree_method_get_custom_popup_rect>` **(** **)** const                                                             |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`           | :ref:`get_drop_section_at_position<class_Tree_method_get_drop_section_at_position>` **(** :ref:`Vector2<class_Vector2>` position **)** const        |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`TreeItem<class_TreeItem>` | :ref:`get_edited<class_Tree_method_get_edited>` **(** **)** const                                                                                   |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`           | :ref:`get_edited_column<class_Tree_method_get_edited_column>` **(** **)** const                                                                     |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Rect2<class_Rect2>`       | :ref:`get_item_area_rect<class_Tree_method_get_item_area_rect>` **(** :ref:`Object<class_Object>` item, :ref:`int<class_int>` column=-1 **)** const |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`TreeItem<class_TreeItem>` | :ref:`get_item_at_position<class_Tree_method_get_item_at_position>` **(** :ref:`Vector2<class_Vector2>` position **)** const                        |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`TreeItem<class_TreeItem>` | :ref:`get_next_selected<class_Tree_method_get_next_selected>` **(** :ref:`Object<class_Object>` from **)**                                          |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`           | :ref:`get_pressed_button<class_Tree_method_get_pressed_button>` **(** **)** const                                                                   |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`TreeItem<class_TreeItem>` | :ref:`get_root<class_Tree_method_get_root>` **(** **)**                                                                                             |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`   | :ref:`get_scroll<class_Tree_method_get_scroll>` **(** **)** const                                                                                   |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`TreeItem<class_TreeItem>` | :ref:`get_selected<class_Tree_method_get_selected>` **(** **)** const                                                                               |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`           | :ref:`get_selected_column<class_Tree_method_get_selected_column>` **(** **)** const                                                                 |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| void                            | :ref:`set_column_expand<class_Tree_method_set_column_expand>` **(** :ref:`int<class_int>` column, :ref:`bool<class_bool>` expand **)**              |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| void                            | :ref:`set_column_min_width<class_Tree_method_set_column_min_width>` **(** :ref:`int<class_int>` column, :ref:`int<class_int>` min_width **)**       |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| void                            | :ref:`set_column_title<class_Tree_method_set_column_title>` **(** :ref:`int<class_int>` column, :ref:`String<class_String>` title **)**             |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| void                            | :ref:`set_column_titles_visible<class_Tree_method_set_column_titles_visible>` **(** :ref:`bool<class_bool>` visible **)**                           |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+

Theme Properties
----------------

+---------------------------------+------------------------------+------------------------------+
| :ref:`Texture<class_Texture>`   | arrow                        |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`Texture<class_Texture>`   | arrow_collapsed              |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`StyleBox<class_StyleBox>` | bg                           |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`StyleBox<class_StyleBox>` | bg_focus                     |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`int<class_int>`           | button_margin                | 4                            |
+---------------------------------+------------------------------+------------------------------+
| :ref:`StyleBox<class_StyleBox>` | button_pressed               |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`Texture<class_Texture>`   | checked                      |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`StyleBox<class_StyleBox>` | cursor                       |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`Color<class_Color>`       | cursor_color                 | Color( 0, 0, 0, 1 )          |
+---------------------------------+------------------------------+------------------------------+
| :ref:`StyleBox<class_StyleBox>` | cursor_unfocused             |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`StyleBox<class_StyleBox>` | custom_button                |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`Color<class_Color>`       | custom_button_font_highlight | Color( 0.94, 0.94, 0.94, 1 ) |
+---------------------------------+------------------------------+------------------------------+
| :ref:`StyleBox<class_StyleBox>` | custom_button_hover          |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`StyleBox<class_StyleBox>` | custom_button_pressed        |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`int<class_int>`           | draw_guides                  | 1                            |
+---------------------------------+------------------------------+------------------------------+
| :ref:`int<class_int>`           | draw_relationship_lines      | 0                            |
+---------------------------------+------------------------------+------------------------------+
| :ref:`Color<class_Color>`       | drop_position_color          | Color( 1, 0.3, 0.2, 1 )      |
+---------------------------------+------------------------------+------------------------------+
| :ref:`Font<class_Font>`         | font                         |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`Color<class_Color>`       | font_color                   | Color( 0.69, 0.69, 0.69, 1 ) |
+---------------------------------+------------------------------+------------------------------+
| :ref:`Color<class_Color>`       | font_color_selected          | Color( 1, 1, 1, 1 )          |
+---------------------------------+------------------------------+------------------------------+
| :ref:`Color<class_Color>`       | guide_color                  | Color( 0, 0, 0, 0.1 )        |
+---------------------------------+------------------------------+------------------------------+
| :ref:`int<class_int>`           | guide_width                  | 2                            |
+---------------------------------+------------------------------+------------------------------+
| :ref:`int<class_int>`           | hseparation                  | 4                            |
+---------------------------------+------------------------------+------------------------------+
| :ref:`int<class_int>`           | item_margin                  | 12                           |
+---------------------------------+------------------------------+------------------------------+
| :ref:`Color<class_Color>`       | relationship_line_color      | Color( 0.27, 0.27, 0.27, 1 ) |
+---------------------------------+------------------------------+------------------------------+
| :ref:`int<class_int>`           | scroll_border                | 4                            |
+---------------------------------+------------------------------+------------------------------+
| :ref:`int<class_int>`           | scroll_speed                 | 12                           |
+---------------------------------+------------------------------+------------------------------+
| :ref:`Texture<class_Texture>`   | select_arrow                 |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`StyleBox<class_StyleBox>` | selected                     |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`StyleBox<class_StyleBox>` | selected_focus               |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`Color<class_Color>`       | selection_color              | Color( 0.1, 0.1, 1, 0.8 )    |
+---------------------------------+------------------------------+------------------------------+
| :ref:`Color<class_Color>`       | title_button_color           | Color( 0.88, 0.88, 0.88, 1 ) |
+---------------------------------+------------------------------+------------------------------+
| :ref:`Font<class_Font>`         | title_button_font            |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`StyleBox<class_StyleBox>` | title_button_hover           |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`StyleBox<class_StyleBox>` | title_button_normal          |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`StyleBox<class_StyleBox>` | title_button_pressed         |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`Texture<class_Texture>`   | unchecked                    |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`Texture<class_Texture>`   | updown                       |                              |
+---------------------------------+------------------------------+------------------------------+
| :ref:`int<class_int>`           | vseparation                  | 4                            |
+---------------------------------+------------------------------+------------------------------+

Signals
-------

.. _class_Tree_signal_button_pressed:

- **button_pressed** **(** :ref:`TreeItem<class_TreeItem>` item, :ref:`int<class_int>` column, :ref:`int<class_int>` id **)**

Emitted when a button on the tree was pressed (see :ref:`TreeItem.add_button<class_TreeItem_method_add_button>`).

.. _class_Tree_signal_cell_selected:

- **cell_selected** **(** **)**

Emitted when a cell is selected.

.. _class_Tree_signal_column_title_pressed:

- **column_title_pressed** **(** :ref:`int<class_int>` column **)**

Emitted when a column's title is pressed.

.. _class_Tree_signal_custom_popup_edited:

- **custom_popup_edited** **(** :ref:`bool<class_bool>` arrow_clicked **)**

Emitted when a cell with the :ref:`TreeItem.CELL_MODE_CUSTOM<class_TreeItem_constant_CELL_MODE_CUSTOM>` is clicked to be edited.

.. _class_Tree_signal_empty_rmb:

- **empty_rmb** **(** :ref:`Vector2<class_Vector2>` position **)**

.. _class_Tree_signal_empty_tree_rmb_selected:

- **empty_tree_rmb_selected** **(** :ref:`Vector2<class_Vector2>` position **)**

Emitted when the right mouse button is pressed if right mouse button selection is active and the tree is empty.

.. _class_Tree_signal_item_activated:

- **item_activated** **(** **)**

Emitted when an item's label is double-clicked.

.. _class_Tree_signal_item_collapsed:

- **item_collapsed** **(** :ref:`TreeItem<class_TreeItem>` item **)**

Emitted when an item is collapsed by a click on the folding arrow.

.. _class_Tree_signal_item_custom_button_pressed:

- **item_custom_button_pressed** **(** **)**

.. _class_Tree_signal_item_double_clicked:

- **item_double_clicked** **(** **)**

Emitted when an item's icon is double-clicked.

.. _class_Tree_signal_item_edited:

- **item_edited** **(** **)**

Emitted when an item is edited.

.. _class_Tree_signal_item_rmb_edited:

- **item_rmb_edited** **(** **)**

Emitted when an item is edited using the right mouse button.

.. _class_Tree_signal_item_rmb_selected:

- **item_rmb_selected** **(** :ref:`Vector2<class_Vector2>` position **)**

Emitted when an item is selected with the right mouse button.

.. _class_Tree_signal_item_selected:

- **item_selected** **(** **)**

Emitted when an item is selected.

.. _class_Tree_signal_multi_selected:

- **multi_selected** **(** :ref:`TreeItem<class_TreeItem>` item, :ref:`int<class_int>` column, :ref:`bool<class_bool>` selected **)**

Emitted instead of ``item_selected`` if ``select_mode`` is :ref:`SELECT_MULTI<class_Tree_constant_SELECT_MULTI>`.

.. _class_Tree_signal_nothing_selected:

- **nothing_selected** **(** **)**

Enumerations
------------

.. _enum_Tree_SelectMode:

.. _class_Tree_constant_SELECT_SINGLE:

.. _class_Tree_constant_SELECT_ROW:

.. _class_Tree_constant_SELECT_MULTI:

enum **SelectMode**:

- **SELECT_SINGLE** = **0** --- Allows selection of a single item at a time.

- **SELECT_ROW** = **1**

- **SELECT_MULTI** = **2** --- Allows selection of multiple items at the same time.

.. _enum_Tree_DropModeFlags:

.. _class_Tree_constant_DROP_MODE_DISABLED:

.. _class_Tree_constant_DROP_MODE_ON_ITEM:

.. _class_Tree_constant_DROP_MODE_INBETWEEN:

enum **DropModeFlags**:

- **DROP_MODE_DISABLED** = **0**

- **DROP_MODE_ON_ITEM** = **1**

- **DROP_MODE_INBETWEEN** = **2**

Description
-----------

This shows a tree of items that can be selected, expanded and collapsed. The tree can have multiple columns with custom controls like text editing, buttons and popups. It can be useful for structured displays and interactions.

Trees are built via code, using :ref:`TreeItem<class_TreeItem>` objects to create the structure. They have a single root but multiple roots can be simulated if a dummy hidden root is added.

::

    func _ready():
        var tree = Tree.new()
        var root = tree.create_item()
        tree.set_hide_root(true)
        var child1 = tree.create_item(root)
        var child2 = tree.create_item(root)
        var subchild1 = tree.create_item(child1)
        subchild1.set_text(0, "Subchild1")

Property Descriptions
---------------------

.. _class_Tree_property_allow_reselect:

- :ref:`bool<class_bool>` **allow_reselect**

+-----------+---------------------------+
| *Default* | false                     |
+-----------+---------------------------+
| *Setter*  | set_allow_reselect(value) |
+-----------+---------------------------+
| *Getter*  | get_allow_reselect()      |
+-----------+---------------------------+

If ``true``, the currently selected cell may be selected again.

.. _class_Tree_property_allow_rmb_select:

- :ref:`bool<class_bool>` **allow_rmb_select**

+-----------+-----------------------------+
| *Default* | false                       |
+-----------+-----------------------------+
| *Setter*  | set_allow_rmb_select(value) |
+-----------+-----------------------------+
| *Getter*  | get_allow_rmb_select()      |
+-----------+-----------------------------+

If ``true``, a right mouse button click can select items.

.. _class_Tree_property_columns:

- :ref:`int<class_int>` **columns**

+-----------+--------------------+
| *Default* | 1                  |
+-----------+--------------------+
| *Setter*  | set_columns(value) |
+-----------+--------------------+
| *Getter*  | get_columns()      |
+-----------+--------------------+

The number of columns.

.. _class_Tree_property_drop_mode_flags:

- :ref:`int<class_int>` **drop_mode_flags**

+-----------+----------------------------+
| *Default* | 0                          |
+-----------+----------------------------+
| *Setter*  | set_drop_mode_flags(value) |
+-----------+----------------------------+
| *Getter*  | get_drop_mode_flags()      |
+-----------+----------------------------+

The drop mode as an OR combination of flags. See ``DROP_MODE_*`` constants. Once dropping is done, reverts to :ref:`DROP_MODE_DISABLED<class_Tree_constant_DROP_MODE_DISABLED>`. Setting this during :ref:`Control.can_drop_data<class_Control_method_can_drop_data>` is recommended.

.. _class_Tree_property_hide_folding:

- :ref:`bool<class_bool>` **hide_folding**

+-----------+-------------------------+
| *Default* | false                   |
+-----------+-------------------------+
| *Setter*  | set_hide_folding(value) |
+-----------+-------------------------+
| *Getter*  | is_folding_hidden()     |
+-----------+-------------------------+

If ``true``, the folding arrow is hidden.

.. _class_Tree_property_hide_root:

- :ref:`bool<class_bool>` **hide_root**

+-----------+----------------------+
| *Default* | false                |
+-----------+----------------------+
| *Setter*  | set_hide_root(value) |
+-----------+----------------------+
| *Getter*  | is_root_hidden()     |
+-----------+----------------------+

If ``true``, the tree's root is hidden.

.. _class_Tree_property_select_mode:

- :ref:`SelectMode<enum_Tree_SelectMode>` **select_mode**

+-----------+------------------------+
| *Default* | 0                      |
+-----------+------------------------+
| *Setter*  | set_select_mode(value) |
+-----------+------------------------+
| *Getter*  | get_select_mode()      |
+-----------+------------------------+

Allows single or multiple selection. See the ``SELECT_*`` constants.

Method Descriptions
-------------------

.. _class_Tree_method_are_column_titles_visible:

- :ref:`bool<class_bool>` **are_column_titles_visible** **(** **)** const

Returns ``true`` if the column titles are being shown.

.. _class_Tree_method_clear:

- void **clear** **(** **)**

Clears the tree. This removes all items.

.. _class_Tree_method_create_item:

- :ref:`TreeItem<class_TreeItem>` **create_item** **(** :ref:`Object<class_Object>` parent=null, :ref:`int<class_int>` idx=-1 **)**

Create an item in the tree and add it as the last child of ``parent``. If ``parent`` is ``null``, it will be added as the root's last child, or it'll be the the root itself if the tree is empty.

.. _class_Tree_method_ensure_cursor_is_visible:

- void **ensure_cursor_is_visible** **(** **)**

Makes the currently selected item visible. This will scroll the tree to make sure the selected item is visible.

.. _class_Tree_method_get_column_at_position:

- :ref:`int<class_int>` **get_column_at_position** **(** :ref:`Vector2<class_Vector2>` position **)** const

Returns the column index under the given point.

.. _class_Tree_method_get_column_title:

- :ref:`String<class_String>` **get_column_title** **(** :ref:`int<class_int>` column **)** const

Returns the column's title.

.. _class_Tree_method_get_column_width:

- :ref:`int<class_int>` **get_column_width** **(** :ref:`int<class_int>` column **)** const

Returns the column's width in pixels.

.. _class_Tree_method_get_custom_popup_rect:

- :ref:`Rect2<class_Rect2>` **get_custom_popup_rect** **(** **)** const

Returns the rectangle for custom popups. Helper to create custom cell controls that display a popup. See :ref:`TreeItem.set_cell_mode<class_TreeItem_method_set_cell_mode>`.

.. _class_Tree_method_get_drop_section_at_position:

- :ref:`int<class_int>` **get_drop_section_at_position** **(** :ref:`Vector2<class_Vector2>` position **)** const

If :ref:`drop_mode_flags<class_Tree_property_drop_mode_flags>` includes :ref:`DROP_MODE_INBETWEEN<class_Tree_constant_DROP_MODE_INBETWEEN>`, returns -1 if ``position`` is the upper part of a tree item at that position, 1 for the lower part, and additionally 0 for the middle part if :ref:`drop_mode_flags<class_Tree_property_drop_mode_flags>` includes :ref:`DROP_MODE_ON_ITEM<class_Tree_constant_DROP_MODE_ON_ITEM>`.

Otherwise, returns 0. If there are no tree items at ``position``, returns -100.

.. _class_Tree_method_get_edited:

- :ref:`TreeItem<class_TreeItem>` **get_edited** **(** **)** const

Returns the currently edited item. This is only available for custom cell mode.

.. _class_Tree_method_get_edited_column:

- :ref:`int<class_int>` **get_edited_column** **(** **)** const

Returns the column for the currently edited item. This is only available for custom cell mode.

.. _class_Tree_method_get_item_area_rect:

- :ref:`Rect2<class_Rect2>` **get_item_area_rect** **(** :ref:`Object<class_Object>` item, :ref:`int<class_int>` column=-1 **)** const

Returns the rectangle area for the specified item. If column is specified, only get the position and size of that column, otherwise get the rectangle containing all columns.

.. _class_Tree_method_get_item_at_position:

- :ref:`TreeItem<class_TreeItem>` **get_item_at_position** **(** :ref:`Vector2<class_Vector2>` position **)** const

Returns the tree item at the specified position (relative to the tree origin position).

.. _class_Tree_method_get_next_selected:

- :ref:`TreeItem<class_TreeItem>` **get_next_selected** **(** :ref:`Object<class_Object>` from **)**

Returns the next selected item after the given one.

.. _class_Tree_method_get_pressed_button:

- :ref:`int<class_int>` **get_pressed_button** **(** **)** const

Returns the last pressed button's index.

.. _class_Tree_method_get_root:

- :ref:`TreeItem<class_TreeItem>` **get_root** **(** **)**

Returns the tree's root item.

.. _class_Tree_method_get_scroll:

- :ref:`Vector2<class_Vector2>` **get_scroll** **(** **)** const

Returns the current scrolling position.

.. _class_Tree_method_get_selected:

- :ref:`TreeItem<class_TreeItem>` **get_selected** **(** **)** const

Returns the currently selected item.

.. _class_Tree_method_get_selected_column:

- :ref:`int<class_int>` **get_selected_column** **(** **)** const

Returns the current selection's column.

.. _class_Tree_method_set_column_expand:

- void **set_column_expand** **(** :ref:`int<class_int>` column, :ref:`bool<class_bool>` expand **)**

If ``true``, the column will have the "Expand" flag of :ref:`Control<class_Control>`. Columns that have the "Expand" flag will use their "min_width" in a similar fashion to :ref:`Control.size_flags_stretch_ratio<class_Control_property_size_flags_stretch_ratio>`.

.. _class_Tree_method_set_column_min_width:

- void **set_column_min_width** **(** :ref:`int<class_int>` column, :ref:`int<class_int>` min_width **)**

Sets the minimum width of a column. Columns that have the "Expand" flag will use their "min_width" in a similar fashion to :ref:`Control.size_flags_stretch_ratio<class_Control_property_size_flags_stretch_ratio>`.

.. _class_Tree_method_set_column_title:

- void **set_column_title** **(** :ref:`int<class_int>` column, :ref:`String<class_String>` title **)**

Sets the title of a column.

.. _class_Tree_method_set_column_titles_visible:

- void **set_column_titles_visible** **(** :ref:`bool<class_bool>` visible **)**

If ``true``, column titles are visible.

