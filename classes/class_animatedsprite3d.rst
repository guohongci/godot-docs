.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the AnimatedSprite3D.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_AnimatedSprite3D:

AnimatedSprite3D
================

**Inherits:** :ref:`SpriteBase3D<class_SpriteBase3D>` **<** :ref:`GeometryInstance<class_GeometryInstance>` **<** :ref:`VisualInstance<class_VisualInstance>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

**Category:** Core

Brief Description
-----------------

2D sprite node in 3D world, that can use multiple 2D textures for animation.

Properties
----------

+-----------------------------------------+-------------------------------------------------------------+-----------+
| :ref:`String<class_String>`             | :ref:`animation<class_AnimatedSprite3D_property_animation>` | "default" |
+-----------------------------------------+-------------------------------------------------------------+-----------+
| :ref:`int<class_int>`                   | :ref:`frame<class_AnimatedSprite3D_property_frame>`         | 0         |
+-----------------------------------------+-------------------------------------------------------------+-----------+
| :ref:`SpriteFrames<class_SpriteFrames>` | :ref:`frames<class_AnimatedSprite3D_property_frames>`       |           |
+-----------------------------------------+-------------------------------------------------------------+-----------+
| :ref:`bool<class_bool>`                 | :ref:`playing<class_AnimatedSprite3D_property_playing>`     | false     |
+-----------------------------------------+-------------------------------------------------------------+-----------+

Methods
-------

+-------------------------+-------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>` | :ref:`is_playing<class_AnimatedSprite3D_method_is_playing>` **(** **)** const                   |
+-------------------------+-------------------------------------------------------------------------------------------------+
| void                    | :ref:`play<class_AnimatedSprite3D_method_play>` **(** :ref:`String<class_String>` anim="" **)** |
+-------------------------+-------------------------------------------------------------------------------------------------+
| void                    | :ref:`stop<class_AnimatedSprite3D_method_stop>` **(** **)**                                     |
+-------------------------+-------------------------------------------------------------------------------------------------+

Signals
-------

.. _class_AnimatedSprite3D_signal_frame_changed:

- **frame_changed** **(** **)**

Emitted when :ref:`frame<class_AnimatedSprite3D_property_frame>` changed.

Description
-----------

Animations are created using a :ref:`SpriteFrames<class_SpriteFrames>` resource, which can be configured in the editor via the SpriteFrames panel.

Property Descriptions
---------------------

.. _class_AnimatedSprite3D_property_animation:

- :ref:`String<class_String>` **animation**

+-----------+----------------------+
| *Default* | "default"            |
+-----------+----------------------+
| *Setter*  | set_animation(value) |
+-----------+----------------------+
| *Getter*  | get_animation()      |
+-----------+----------------------+

The current animation from the ``frames`` resource. If this value changes, the ``frame`` counter is reset.

.. _class_AnimatedSprite3D_property_frame:

- :ref:`int<class_int>` **frame**

+-----------+------------------+
| *Default* | 0                |
+-----------+------------------+
| *Setter*  | set_frame(value) |
+-----------+------------------+
| *Getter*  | get_frame()      |
+-----------+------------------+

The displayed animation frame's index.

.. _class_AnimatedSprite3D_property_frames:

- :ref:`SpriteFrames<class_SpriteFrames>` **frames**

+----------+--------------------------+
| *Setter* | set_sprite_frames(value) |
+----------+--------------------------+
| *Getter* | get_sprite_frames()      |
+----------+--------------------------+

The :ref:`SpriteFrames<class_SpriteFrames>` resource containing the animation(s).

.. _class_AnimatedSprite3D_property_playing:

- :ref:`bool<class_bool>` **playing**

+-----------+-------+
| *Default* | false |
+-----------+-------+

If ``true``, the :ref:`animation<class_AnimatedSprite3D_property_animation>` is currently playing.

Method Descriptions
-------------------

.. _class_AnimatedSprite3D_method_is_playing:

- :ref:`bool<class_bool>` **is_playing** **(** **)** const

Returns ``true`` if an animation is currently being played.

.. _class_AnimatedSprite3D_method_play:

- void **play** **(** :ref:`String<class_String>` anim="" **)**

Plays the animation named ``anim``. If no ``anim`` is provided, the current animation is played.

.. _class_AnimatedSprite3D_method_stop:

- void **stop** **(** **)**

Stops the current animation (does not reset the frame counter).

