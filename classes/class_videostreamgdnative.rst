:github_url: hide

.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the VideoStreamGDNative.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_VideoStreamGDNative:

VideoStreamGDNative
===================

**Inherits:** :ref:`VideoStream<class_VideoStream>` **<** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

:ref:`VideoStream<class_VideoStream>` resource for for video formats implemented via GDNative.

Description
-----------

:ref:`VideoStream<class_VideoStream>` resource for for video formats implemented via GDNative.

It can be used via `godot-videodecoder <https://github.com/KidRigger/godot-videodecoder>`__ which uses the `FFmpeg <https://ffmpeg.org>`__ library.

Methods
-------

+-----------------------------+---------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>` | :ref:`get_file<class_VideoStreamGDNative_method_get_file>` **(** **)**                                  |
+-----------------------------+---------------------------------------------------------------------------------------------------------+
| void                        | :ref:`set_file<class_VideoStreamGDNative_method_set_file>` **(** :ref:`String<class_String>` file **)** |
+-----------------------------+---------------------------------------------------------------------------------------------------------+

Method Descriptions
-------------------

.. _class_VideoStreamGDNative_method_get_file:

- :ref:`String<class_String>` **get_file** **(** **)**

Returns the video file handled by this ``VideoStreamGDNative``.

----

.. _class_VideoStreamGDNative_method_set_file:

- void **set_file** **(** :ref:`String<class_String>` file **)**

Sets the video file that this ``VideoStreamGDNative`` resource handles. The supported extensions depend on the GDNative plugins used to expose video formats.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
