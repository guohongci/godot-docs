.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the TabContainer.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_TabContainer:

TabContainer
============

**Inherits:** :ref:`Container<class_Container>` **<** :ref:`Control<class_Control>` **<** :ref:`CanvasItem<class_CanvasItem>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

**Category:** Core

Brief Description
-----------------

Tabbed container.

Properties
----------

+---------------------------------------------+-----------------------------------------------------------------------------------------+-------+
| :ref:`int<class_int>`                       | :ref:`current_tab<class_TabContainer_property_current_tab>`                             | 0     |
+---------------------------------------------+-----------------------------------------------------------------------------------------+-------+
| :ref:`bool<class_bool>`                     | :ref:`drag_to_rearrange_enabled<class_TabContainer_property_drag_to_rearrange_enabled>` | false |
+---------------------------------------------+-----------------------------------------------------------------------------------------+-------+
| :ref:`TabAlign<enum_TabContainer_TabAlign>` | :ref:`tab_align<class_TabContainer_property_tab_align>`                                 | 1     |
+---------------------------------------------+-----------------------------------------------------------------------------------------+-------+
| :ref:`bool<class_bool>`                     | :ref:`tabs_visible<class_TabContainer_property_tabs_visible>`                           | true  |
+---------------------------------------------+-----------------------------------------------------------------------------------------+-------+

Methods
-------

+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Control<class_Control>` | :ref:`get_current_tab_control<class_TabContainer_method_get_current_tab_control>` **(** **)** const                                             |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Popup<class_Popup>`     | :ref:`get_popup<class_TabContainer_method_get_popup>` **(** **)** const                                                                         |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`         | :ref:`get_previous_tab<class_TabContainer_method_get_previous_tab>` **(** **)** const                                                           |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Control<class_Control>` | :ref:`get_tab_control<class_TabContainer_method_get_tab_control>` **(** :ref:`int<class_int>` idx **)** const                                   |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`         | :ref:`get_tab_count<class_TabContainer_method_get_tab_count>` **(** **)** const                                                                 |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`       | :ref:`get_tab_disabled<class_TabContainer_method_get_tab_disabled>` **(** :ref:`int<class_int>` tab_idx **)** const                             |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Texture<class_Texture>` | :ref:`get_tab_icon<class_TabContainer_method_get_tab_icon>` **(** :ref:`int<class_int>` tab_idx **)** const                                     |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`   | :ref:`get_tab_title<class_TabContainer_method_get_tab_title>` **(** :ref:`int<class_int>` tab_idx **)** const                                   |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`         | :ref:`get_tabs_rearrange_group<class_TabContainer_method_get_tabs_rearrange_group>` **(** **)** const                                           |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| void                          | :ref:`set_popup<class_TabContainer_method_set_popup>` **(** :ref:`Node<class_Node>` popup **)**                                                 |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| void                          | :ref:`set_tab_disabled<class_TabContainer_method_set_tab_disabled>` **(** :ref:`int<class_int>` tab_idx, :ref:`bool<class_bool>` disabled **)** |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| void                          | :ref:`set_tab_icon<class_TabContainer_method_set_tab_icon>` **(** :ref:`int<class_int>` tab_idx, :ref:`Texture<class_Texture>` icon **)**       |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| void                          | :ref:`set_tab_title<class_TabContainer_method_set_tab_title>` **(** :ref:`int<class_int>` tab_idx, :ref:`String<class_String>` title **)**      |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| void                          | :ref:`set_tabs_rearrange_group<class_TabContainer_method_set_tabs_rearrange_group>` **(** :ref:`int<class_int>` group_id **)**                  |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+

Theme Properties
----------------

+---------------------------------+---------------------+------------------------------+
| :ref:`Texture<class_Texture>`   | decrement           |                              |
+---------------------------------+---------------------+------------------------------+
| :ref:`Texture<class_Texture>`   | decrement_highlight |                              |
+---------------------------------+---------------------+------------------------------+
| :ref:`Font<class_Font>`         | font                |                              |
+---------------------------------+---------------------+------------------------------+
| :ref:`Color<class_Color>`       | font_color_bg       | Color( 0.69, 0.69, 0.69, 1 ) |
+---------------------------------+---------------------+------------------------------+
| :ref:`Color<class_Color>`       | font_color_disabled | Color( 0.9, 0.9, 0.9, 0.2 )  |
+---------------------------------+---------------------+------------------------------+
| :ref:`Color<class_Color>`       | font_color_fg       | Color( 0.94, 0.94, 0.94, 1 ) |
+---------------------------------+---------------------+------------------------------+
| :ref:`int<class_int>`           | hseparation         | 4                            |
+---------------------------------+---------------------+------------------------------+
| :ref:`Texture<class_Texture>`   | increment           |                              |
+---------------------------------+---------------------+------------------------------+
| :ref:`Texture<class_Texture>`   | increment_highlight |                              |
+---------------------------------+---------------------+------------------------------+
| :ref:`int<class_int>`           | label_valign_bg     | 2                            |
+---------------------------------+---------------------+------------------------------+
| :ref:`int<class_int>`           | label_valign_fg     | 0                            |
+---------------------------------+---------------------+------------------------------+
| :ref:`Texture<class_Texture>`   | menu                |                              |
+---------------------------------+---------------------+------------------------------+
| :ref:`Texture<class_Texture>`   | menu_highlight      |                              |
+---------------------------------+---------------------+------------------------------+
| :ref:`StyleBox<class_StyleBox>` | panel               |                              |
+---------------------------------+---------------------+------------------------------+
| :ref:`int<class_int>`           | side_margin         | 8                            |
+---------------------------------+---------------------+------------------------------+
| :ref:`StyleBox<class_StyleBox>` | tab_bg              |                              |
+---------------------------------+---------------------+------------------------------+
| :ref:`StyleBox<class_StyleBox>` | tab_disabled        |                              |
+---------------------------------+---------------------+------------------------------+
| :ref:`StyleBox<class_StyleBox>` | tab_fg              |                              |
+---------------------------------+---------------------+------------------------------+
| :ref:`int<class_int>`           | top_margin          | 24                           |
+---------------------------------+---------------------+------------------------------+

Signals
-------

.. _class_TabContainer_signal_pre_popup_pressed:

- **pre_popup_pressed** **(** **)**

Emitted when the ``TabContainer``'s :ref:`Popup<class_Popup>` button is clicked. See :ref:`set_popup<class_TabContainer_method_set_popup>` for details.

.. _class_TabContainer_signal_tab_changed:

- **tab_changed** **(** :ref:`int<class_int>` tab **)**

Emitted when switching to another tab.

.. _class_TabContainer_signal_tab_selected:

- **tab_selected** **(** :ref:`int<class_int>` tab **)**

Emitted when a tab is selected, even if it is the current tab.

Enumerations
------------

.. _enum_TabContainer_TabAlign:

.. _class_TabContainer_constant_ALIGN_LEFT:

.. _class_TabContainer_constant_ALIGN_CENTER:

.. _class_TabContainer_constant_ALIGN_RIGHT:

enum **TabAlign**:

- **ALIGN_LEFT** = **0** --- Align the tabs to the left.

- **ALIGN_CENTER** = **1** --- Align the tabs to the center.

- **ALIGN_RIGHT** = **2** --- Align the tabs to the right.

Description
-----------

Sets the active tab's ``visible`` property to the value ``true``. Sets all other children's to ``false``.

Ignores non-:ref:`Control<class_Control>` children.

Individual tabs are always visible unless you use :ref:`set_tab_disabled<class_TabContainer_method_set_tab_disabled>` and :ref:`set_tab_title<class_TabContainer_method_set_tab_title>` to hide it.

To hide only a tab's content, nest the content inside a child :ref:`Control<class_Control>`, so it receives the ``TabContainer``'s visibility setting instead.

Property Descriptions
---------------------

.. _class_TabContainer_property_current_tab:

- :ref:`int<class_int>` **current_tab**

+-----------+------------------------+
| *Default* | 0                      |
+-----------+------------------------+
| *Setter*  | set_current_tab(value) |
+-----------+------------------------+
| *Getter*  | get_current_tab()      |
+-----------+------------------------+

The current tab index. When set, this index's :ref:`Control<class_Control>` node's ``visible`` property is set to ``true`` and all others are set to ``false``.

.. _class_TabContainer_property_drag_to_rearrange_enabled:

- :ref:`bool<class_bool>` **drag_to_rearrange_enabled**

+-----------+--------------------------------------+
| *Default* | false                                |
+-----------+--------------------------------------+
| *Setter*  | set_drag_to_rearrange_enabled(value) |
+-----------+--------------------------------------+
| *Getter*  | get_drag_to_rearrange_enabled()      |
+-----------+--------------------------------------+

If ``true``, tabs can be rearranged with mouse drag.

.. _class_TabContainer_property_tab_align:

- :ref:`TabAlign<enum_TabContainer_TabAlign>` **tab_align**

+-----------+----------------------+
| *Default* | 1                    |
+-----------+----------------------+
| *Setter*  | set_tab_align(value) |
+-----------+----------------------+
| *Getter*  | get_tab_align()      |
+-----------+----------------------+

The alignment of all tabs in the tab container. See the ``ALIGN_*`` constants for details.

.. _class_TabContainer_property_tabs_visible:

- :ref:`bool<class_bool>` **tabs_visible**

+-----------+-------------------------+
| *Default* | true                    |
+-----------+-------------------------+
| *Setter*  | set_tabs_visible(value) |
+-----------+-------------------------+
| *Getter*  | are_tabs_visible()      |
+-----------+-------------------------+

If ``true``, tabs are visible. If ``false``, tabs' content and titles are hidden.

Method Descriptions
-------------------

.. _class_TabContainer_method_get_current_tab_control:

- :ref:`Control<class_Control>` **get_current_tab_control** **(** **)** const

Returns the child :ref:`Control<class_Control>` node located at the active tab index.

.. _class_TabContainer_method_get_popup:

- :ref:`Popup<class_Popup>` **get_popup** **(** **)** const

Returns the :ref:`Popup<class_Popup>` node instance if one has been set already with :ref:`set_popup<class_TabContainer_method_set_popup>`.

.. _class_TabContainer_method_get_previous_tab:

- :ref:`int<class_int>` **get_previous_tab** **(** **)** const

Returns the previously active tab index.

.. _class_TabContainer_method_get_tab_control:

- :ref:`Control<class_Control>` **get_tab_control** **(** :ref:`int<class_int>` idx **)** const

Returns the currently visible tab's :ref:`Control<class_Control>` node.

.. _class_TabContainer_method_get_tab_count:

- :ref:`int<class_int>` **get_tab_count** **(** **)** const

Returns the number of tabs.

.. _class_TabContainer_method_get_tab_disabled:

- :ref:`bool<class_bool>` **get_tab_disabled** **(** :ref:`int<class_int>` tab_idx **)** const

Returns ``true`` if the tab at index ``tab_idx`` is disabled.

.. _class_TabContainer_method_get_tab_icon:

- :ref:`Texture<class_Texture>` **get_tab_icon** **(** :ref:`int<class_int>` tab_idx **)** const

Returns the :ref:`Texture<class_Texture>` for the tab at index ``tab_idx`` or ``null`` if the tab has no :ref:`Texture<class_Texture>`.

.. _class_TabContainer_method_get_tab_title:

- :ref:`String<class_String>` **get_tab_title** **(** :ref:`int<class_int>` tab_idx **)** const

Returns the title of the tab at index ``tab_idx``. Tab titles default to the name of the indexed child node, but this can be overridden with :ref:`set_tab_title<class_TabContainer_method_set_tab_title>`.

.. _class_TabContainer_method_get_tabs_rearrange_group:

- :ref:`int<class_int>` **get_tabs_rearrange_group** **(** **)** const

Returns the ``TabContainer`` rearrange group id.

.. _class_TabContainer_method_set_popup:

- void **set_popup** **(** :ref:`Node<class_Node>` popup **)**

If set on a :ref:`Popup<class_Popup>` node instance, a popup menu icon appears in the top-right corner of the ``TabContainer``. Clicking it will expand the :ref:`Popup<class_Popup>` node.

.. _class_TabContainer_method_set_tab_disabled:

- void **set_tab_disabled** **(** :ref:`int<class_int>` tab_idx, :ref:`bool<class_bool>` disabled **)**

If ``disabled`` is ``false``, hides the tab at index ``tab_idx``.

**Note:** Its title text will remain, unless also removed with :ref:`set_tab_title<class_TabContainer_method_set_tab_title>`.

.. _class_TabContainer_method_set_tab_icon:

- void **set_tab_icon** **(** :ref:`int<class_int>` tab_idx, :ref:`Texture<class_Texture>` icon **)**

Sets an icon for the tab at index ``tab_idx``.

.. _class_TabContainer_method_set_tab_title:

- void **set_tab_title** **(** :ref:`int<class_int>` tab_idx, :ref:`String<class_String>` title **)**

Sets a title for the tab at index ``tab_idx``. Tab titles default to the name of the indexed child node, but this can be overridden with :ref:`set_tab_title<class_TabContainer_method_set_tab_title>`.

.. _class_TabContainer_method_set_tabs_rearrange_group:

- void **set_tabs_rearrange_group** **(** :ref:`int<class_int>` group_id **)**

Defines rearrange group id, choose for each ``TabContainer`` the same value to enable tab drag between ``TabContainer``. Enable drag with ``set_drag_to_rearrange_enabled(true)``.

