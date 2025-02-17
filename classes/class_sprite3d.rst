.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the Sprite3D.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_Sprite3D:

Sprite3D
========

**Inherits:** :ref:`SpriteBase3D<class_SpriteBase3D>` **<** :ref:`GeometryInstance<class_GeometryInstance>` **<** :ref:`VisualInstance<class_VisualInstance>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

**Category:** Core

Brief Description
-----------------

2D sprite node in a 3D world.

Properties
----------

+-------------------------------+---------------------------------------------------------------+---------------------+
| :ref:`int<class_int>`         | :ref:`frame<class_Sprite3D_property_frame>`                   | 0                   |
+-------------------------------+---------------------------------------------------------------+---------------------+
| :ref:`int<class_int>`         | :ref:`hframes<class_Sprite3D_property_hframes>`               | 1                   |
+-------------------------------+---------------------------------------------------------------+---------------------+
| :ref:`bool<class_bool>`       | :ref:`region_enabled<class_Sprite3D_property_region_enabled>` | false               |
+-------------------------------+---------------------------------------------------------------+---------------------+
| :ref:`Rect2<class_Rect2>`     | :ref:`region_rect<class_Sprite3D_property_region_rect>`       | Rect2( 0, 0, 0, 0 ) |
+-------------------------------+---------------------------------------------------------------+---------------------+
| :ref:`Texture<class_Texture>` | :ref:`texture<class_Sprite3D_property_texture>`               |                     |
+-------------------------------+---------------------------------------------------------------+---------------------+
| :ref:`int<class_int>`         | :ref:`vframes<class_Sprite3D_property_vframes>`               | 1                   |
+-------------------------------+---------------------------------------------------------------+---------------------+

Signals
-------

.. _class_Sprite3D_signal_frame_changed:

- **frame_changed** **(** **)**

Emitted when the :ref:`frame<class_Sprite3D_property_frame>` changes.

Description
-----------

A node that displays a 2D texture in a 3D environment. The texture displayed can be a region from a larger atlas texture, or a frame from a sprite sheet animation.

Property Descriptions
---------------------

.. _class_Sprite3D_property_frame:

- :ref:`int<class_int>` **frame**

+-----------+------------------+
| *Default* | 0                |
+-----------+------------------+
| *Setter*  | set_frame(value) |
+-----------+------------------+
| *Getter*  | get_frame()      |
+-----------+------------------+

Current frame to display from sprite sheet. :ref:`vframes<class_Sprite3D_property_vframes>` or :ref:`hframes<class_Sprite3D_property_hframes>` must be greater than 1.

.. _class_Sprite3D_property_hframes:

- :ref:`int<class_int>` **hframes**

+-----------+--------------------+
| *Default* | 1                  |
+-----------+--------------------+
| *Setter*  | set_hframes(value) |
+-----------+--------------------+
| *Getter*  | get_hframes()      |
+-----------+--------------------+

The number of columns in the sprite sheet.

.. _class_Sprite3D_property_region_enabled:

- :ref:`bool<class_bool>` **region_enabled**

+-----------+-------------------+
| *Default* | false             |
+-----------+-------------------+
| *Setter*  | set_region(value) |
+-----------+-------------------+
| *Getter*  | is_region()       |
+-----------+-------------------+

If ``true``, texture will be cut from a larger atlas texture. See :ref:`region_rect<class_Sprite3D_property_region_rect>`.

.. _class_Sprite3D_property_region_rect:

- :ref:`Rect2<class_Rect2>` **region_rect**

+-----------+------------------------+
| *Default* | Rect2( 0, 0, 0, 0 )    |
+-----------+------------------------+
| *Setter*  | set_region_rect(value) |
+-----------+------------------------+
| *Getter*  | get_region_rect()      |
+-----------+------------------------+

The region of the atlas texture to display. :ref:`region_enabled<class_Sprite3D_property_region_enabled>` must be ``true``.

.. _class_Sprite3D_property_texture:

- :ref:`Texture<class_Texture>` **texture**

+----------+--------------------+
| *Setter* | set_texture(value) |
+----------+--------------------+
| *Getter* | get_texture()      |
+----------+--------------------+

:ref:`Texture<class_Texture>` object to draw.

.. _class_Sprite3D_property_vframes:

- :ref:`int<class_int>` **vframes**

+-----------+--------------------+
| *Default* | 1                  |
+-----------+--------------------+
| *Setter*  | set_vframes(value) |
+-----------+--------------------+
| *Getter*  | get_vframes()      |
+-----------+--------------------+

The number of rows in the sprite sheet.

