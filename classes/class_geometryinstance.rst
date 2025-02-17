.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the GeometryInstance.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_GeometryInstance:

GeometryInstance
================

**Inherits:** :ref:`VisualInstance<class_VisualInstance>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

**Inherited By:** :ref:`CPUParticles<class_CPUParticles>`, :ref:`CSGShape<class_CSGShape>`, :ref:`ImmediateGeometry<class_ImmediateGeometry>`, :ref:`MeshInstance<class_MeshInstance>`, :ref:`MultiMeshInstance<class_MultiMeshInstance>`, :ref:`Particles<class_Particles>`, :ref:`SpriteBase3D<class_SpriteBase3D>`

**Category:** Core

Brief Description
-----------------

Base node for geometry-based visual instances.

Properties
----------

+-------------------------------------------------------------------------+-------------------------------------------------------------------------------+-------+
| :ref:`ShadowCastingSetting<enum_GeometryInstance_ShadowCastingSetting>` | :ref:`cast_shadow<class_GeometryInstance_property_cast_shadow>`               | 1     |
+-------------------------------------------------------------------------+-------------------------------------------------------------------------------+-------+
| :ref:`float<class_float>`                                               | :ref:`extra_cull_margin<class_GeometryInstance_property_extra_cull_margin>`   | 0.0   |
+-------------------------------------------------------------------------+-------------------------------------------------------------------------------+-------+
| :ref:`float<class_float>`                                               | :ref:`lod_max_distance<class_GeometryInstance_property_lod_max_distance>`     | 0.0   |
+-------------------------------------------------------------------------+-------------------------------------------------------------------------------+-------+
| :ref:`float<class_float>`                                               | :ref:`lod_max_hysteresis<class_GeometryInstance_property_lod_max_hysteresis>` | 0.0   |
+-------------------------------------------------------------------------+-------------------------------------------------------------------------------+-------+
| :ref:`float<class_float>`                                               | :ref:`lod_min_distance<class_GeometryInstance_property_lod_min_distance>`     | 0.0   |
+-------------------------------------------------------------------------+-------------------------------------------------------------------------------+-------+
| :ref:`float<class_float>`                                               | :ref:`lod_min_hysteresis<class_GeometryInstance_property_lod_min_hysteresis>` | 0.0   |
+-------------------------------------------------------------------------+-------------------------------------------------------------------------------+-------+
| :ref:`Material<class_Material>`                                         | :ref:`material_override<class_GeometryInstance_property_material_override>`   |       |
+-------------------------------------------------------------------------+-------------------------------------------------------------------------------+-------+
| :ref:`bool<class_bool>`                                                 | :ref:`use_in_baked_light<class_GeometryInstance_property_use_in_baked_light>` | false |
+-------------------------------------------------------------------------+-------------------------------------------------------------------------------+-------+

Methods
-------

+-------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>` | :ref:`get_flag<class_GeometryInstance_method_get_flag>` **(** :ref:`Flags<enum_GeometryInstance_Flags>` flag **)** const                          |
+-------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| void                    | :ref:`set_custom_aabb<class_GeometryInstance_method_set_custom_aabb>` **(** :ref:`AABB<class_AABB>` aabb **)**                                    |
+-------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| void                    | :ref:`set_flag<class_GeometryInstance_method_set_flag>` **(** :ref:`Flags<enum_GeometryInstance_Flags>` flag, :ref:`bool<class_bool>` value **)** |
+-------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+

Enumerations
------------

.. _enum_GeometryInstance_ShadowCastingSetting:

.. _class_GeometryInstance_constant_SHADOW_CASTING_SETTING_OFF:

.. _class_GeometryInstance_constant_SHADOW_CASTING_SETTING_ON:

.. _class_GeometryInstance_constant_SHADOW_CASTING_SETTING_DOUBLE_SIDED:

.. _class_GeometryInstance_constant_SHADOW_CASTING_SETTING_SHADOWS_ONLY:

enum **ShadowCastingSetting**:

- **SHADOW_CASTING_SETTING_OFF** = **0** --- Will not cast any shadows.

- **SHADOW_CASTING_SETTING_ON** = **1** --- Will cast shadows from all visible faces in the GeometryInstance.

Will take culling into account, so faces not being rendered will not be taken into account when shadow casting.

- **SHADOW_CASTING_SETTING_DOUBLE_SIDED** = **2** --- Will cast shadows from all visible faces in the GeometryInstance.

Will not take culling into account, so all faces will be taken into account when shadow casting.

- **SHADOW_CASTING_SETTING_SHADOWS_ONLY** = **3** --- Will only show the shadows casted from this object.

In other words: The actual mesh will not be visible, only the shadows casted from the mesh.

.. _enum_GeometryInstance_Flags:

.. _class_GeometryInstance_constant_FLAG_USE_BAKED_LIGHT:

.. _class_GeometryInstance_constant_FLAG_DRAW_NEXT_FRAME_IF_VISIBLE:

.. _class_GeometryInstance_constant_FLAG_MAX:

enum **Flags**:

- **FLAG_USE_BAKED_LIGHT** = **0** --- Will allow the GeometryInstance to be used when baking lights using a :ref:`GIProbe<class_GIProbe>` and/or any other form of baked lighting.

- **FLAG_DRAW_NEXT_FRAME_IF_VISIBLE** = **1** --- Unused in this class, exposed for consistency with :ref:`InstanceFlags<enum_VisualServer_InstanceFlags>`.

- **FLAG_MAX** = **2** --- Represents the size of the :ref:`Flags<enum_GeometryInstance_Flags>` enum.

Description
-----------

Base node for geometry-based visual instances. Shares some common functionality like visibility and custom materials.

Property Descriptions
---------------------

.. _class_GeometryInstance_property_cast_shadow:

- :ref:`ShadowCastingSetting<enum_GeometryInstance_ShadowCastingSetting>` **cast_shadow**

+-----------+---------------------------------+
| *Default* | 1                               |
+-----------+---------------------------------+
| *Setter*  | set_cast_shadows_setting(value) |
+-----------+---------------------------------+
| *Getter*  | get_cast_shadows_setting()      |
+-----------+---------------------------------+

The selected shadow casting flag. See :ref:`ShadowCastingSetting<enum_GeometryInstance_ShadowCastingSetting>` for possible values.

.. _class_GeometryInstance_property_extra_cull_margin:

- :ref:`float<class_float>` **extra_cull_margin**

+-----------+------------------------------+
| *Default* | 0.0                          |
+-----------+------------------------------+
| *Setter*  | set_extra_cull_margin(value) |
+-----------+------------------------------+
| *Getter*  | get_extra_cull_margin()      |
+-----------+------------------------------+

The extra distance added to the GeometryInstance's bounding box (:ref:`AABB<class_AABB>`) to increase its cull box.

.. _class_GeometryInstance_property_lod_max_distance:

- :ref:`float<class_float>` **lod_max_distance**

+-----------+-----------------------------+
| *Default* | 0.0                         |
+-----------+-----------------------------+
| *Setter*  | set_lod_max_distance(value) |
+-----------+-----------------------------+
| *Getter*  | get_lod_max_distance()      |
+-----------+-----------------------------+

The GeometryInstance's max LOD distance.

.. _class_GeometryInstance_property_lod_max_hysteresis:

- :ref:`float<class_float>` **lod_max_hysteresis**

+-----------+-------------------------------+
| *Default* | 0.0                           |
+-----------+-------------------------------+
| *Setter*  | set_lod_max_hysteresis(value) |
+-----------+-------------------------------+
| *Getter*  | get_lod_max_hysteresis()      |
+-----------+-------------------------------+

The GeometryInstance's max LOD margin.

.. _class_GeometryInstance_property_lod_min_distance:

- :ref:`float<class_float>` **lod_min_distance**

+-----------+-----------------------------+
| *Default* | 0.0                         |
+-----------+-----------------------------+
| *Setter*  | set_lod_min_distance(value) |
+-----------+-----------------------------+
| *Getter*  | get_lod_min_distance()      |
+-----------+-----------------------------+

The GeometryInstance's min LOD distance.

.. _class_GeometryInstance_property_lod_min_hysteresis:

- :ref:`float<class_float>` **lod_min_hysteresis**

+-----------+-------------------------------+
| *Default* | 0.0                           |
+-----------+-------------------------------+
| *Setter*  | set_lod_min_hysteresis(value) |
+-----------+-------------------------------+
| *Getter*  | get_lod_min_hysteresis()      |
+-----------+-------------------------------+

The GeometryInstance's min LOD margin.

.. _class_GeometryInstance_property_material_override:

- :ref:`Material<class_Material>` **material_override**

+----------+------------------------------+
| *Setter* | set_material_override(value) |
+----------+------------------------------+
| *Getter* | get_material_override()      |
+----------+------------------------------+

The material override for the whole geometry.

If there is a material in ``material_override``, it will be used instead of any material set in any material slot of the mesh.

.. _class_GeometryInstance_property_use_in_baked_light:

- :ref:`bool<class_bool>` **use_in_baked_light**

+-----------+-----------------+
| *Default* | false           |
+-----------+-----------------+
| *Setter*  | set_flag(value) |
+-----------+-----------------+
| *Getter*  | get_flag()      |
+-----------+-----------------+

If ``true``, this GeometryInstance will be used when baking lights using a :ref:`GIProbe<class_GIProbe>` and/or any other form of baked lighting.

Method Descriptions
-------------------

.. _class_GeometryInstance_method_get_flag:

- :ref:`bool<class_bool>` **get_flag** **(** :ref:`Flags<enum_GeometryInstance_Flags>` flag **)** const

.. _class_GeometryInstance_method_set_custom_aabb:

- void **set_custom_aabb** **(** :ref:`AABB<class_AABB>` aabb **)**

Overrides the bounding box of this node with a custom one. To remove it, set an :ref:`AABB<class_AABB>` with all fields set to zero.

.. _class_GeometryInstance_method_set_flag:

- void **set_flag** **(** :ref:`Flags<enum_GeometryInstance_Flags>` flag, :ref:`bool<class_bool>` value **)**

