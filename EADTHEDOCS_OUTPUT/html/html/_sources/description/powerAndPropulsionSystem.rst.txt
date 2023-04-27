Power and Propulsion system
===========================



The batteries are charged with a battery charger supporting LiIon Battery charging and cell voltage balancing.

.. warning::
    The batteries need to be handled with care due to the high amount of energy stored and high voltage. If damage to the batteries is observed (Casing, connector, wiring), it is not serivceable and must be repaired before use.
    
    .. image:: /images/highVoltage.png
        :width: 100
        :alt: High Votlage Warning Symbol
        :align: center




The main indicator of the state of charge of the batteries is the minimum cell voltage.

.. drawio-image:: /diagrams/LiIon_cell_voltages.drawio.xml
    :export-scale: 150
    :align: center


The list shows Status that is during normal operation, in which case the battery can be used for flight.

+-------+-----------------------+----------------------+-----------------------+
| Color | Color                 | Phase                | Status                |
+=======+=======================+======================+=======================+
| G-G   | Slow Blink Continuous | Initial              | Battery OK, no Errors |
+-------+-----------------------+----------------------+                       +
| G-G-G | Slow Blink Continuous | Power OFF            |                       |
+-------+-----------------------+----------------------+                       +
| B-B-B | Blink Continuous      | Precharge            |                       |
+-------+-----------------------+----------------------+                       +
| B     | Continuous            | Power ON             |                       |
+-------+-----------------------+----------------------+                       +
| Y     | Continuous            | Power OFF in progres |                       |
+-------+-----------------------+----------------------+-----------------------+

