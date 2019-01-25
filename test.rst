.. _assigning-batches:

Assigning Batches
=================

When a batch is published, it is usually available to everyone to work on. In the *Batches* table such batch is
marked with *Available to everyone*.

A batch can be assigned to a specific list of workers (in which case, the worker IDs are shown in the *Batches* table,
next to the batch) or it can be in *Unassigned* state. If unassigned, no regular user can work on the batch
(administrators can work on any batch they chose).

You can change the batch assignment from the administrator's *Batches* page by clicking on the link following the
*Assigned To* label.

.. image:: ../_static/batch_assignment.png

The default assignment that a batch has immediately after publishing can be changed by setting the *assigned_to*
attribute. See the *batch.json* description in the :ref:`structure-of-a-batch-file` section.
