Driver Mode and Pipeline Index
==============================
After :ref:`creating a PhotonCamera <docs/programming/photonlib/creating-photon-camera:Constructing a PhotonCamera>`, one can toggle Driver Mode and change the Pipeline Index of the vision program from robot code.

Toggle Driver Mode
------------------
You can use the ``setDriverMode()``/``SetDriverMode()`` (Java and C++ respectively) to toggle driver mode from your robot program. Driver mode is an unfiltered / normal view of the camera to be used while driving the robot.

.. tab-set-code::

    .. code-block:: java

        // Set driver mode to on.
        camera.setDriverMode(true);

    .. code-block:: C++

        // Set driver mode to on.
        camera.SetDriverMode(true);

Setting the Pipeline Index
--------------------------
You can use the ``setPipelineIndex()``/``SetPipelineIndex()`` (Java and C++ respectively) to dynamically change the vision pipeline from your robot program.

.. tab-set-code::

    .. code-block:: java

        // Change pipeline to 2
        camera.setPipelineIndex(2);

    .. code-block:: C++

        // Change pipeline to 2
        camera.SetPipelineIndex(2);

.. Add link to description of pipelines once those docs are complete.
