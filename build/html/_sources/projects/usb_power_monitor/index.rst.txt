USB type-C Power Monitor
----------------------------------

Project `Github`_

.. _`Github`: https://github.com/EricLin0123/USBPowerMeter.git

This is a USB type-C charging monitor based on 32-bit MCU, 16-bit precision ADC,
0.91 inch OLED display and ADXL345 for tapping control.

.. figure:: charging_demo.jpg
    :height: 300px
    :alt: alternate text
    :align: center

    charging demo

.. figure:: imu_demo.jpg
    :height: 300px
    :alt: alternate text
    :align: center

    IMU demo

BOM
===

.. csv-table:: 
   :header: "Part", "Name"
   :widths: 10, 15
   :align: left

    MCU,`STM32G030F6P6`_
    ADC,`INA226`_
    IMU,`ADXL345`_
    OLED,`SSD1306`_

.. _`STM32G030F6P6`: https://www.st.com/resource/en/datasheet/stm32g030c6.pdf
.. _`INA226`: https://www.ti.com/lit/ds/symlink/ina226.pdf?ts=1719365360563&ref_url=https%253A%252F%252Fwww.ti.com%252Fsitesearch%252Fen-us%252Fdocs%252Funiversalsearch.tsp%253FlangPref%253Den-US
.. _`ADXL345`: https://www.analog.com/media/en/technical-documentation/data-sheets/adxl345.pdf
.. _`SSD1306`: https://cdn-shop.adafruit.com/datasheets/SSD1306.pdf

Schematic
=========

.. figure:: schematic.png
    :width: 800px
    :align: center

    schematic

PCB layout
==========

.. figure:: top.png
    :height: 300px
    :align: center

    Top view

.. figure:: bottom.png
    :height: 300px
    :align: center

    Bottom view

Firmware
========
See `Project Github <https://github.com/EricLin0123/USBPowerMeter.git>`_