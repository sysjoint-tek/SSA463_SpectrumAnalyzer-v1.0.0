SSA463 PC Host Software
As the PC host computer for the SSA463 spectrum analyzer (PyQtGraph-based GUI).

Screenshots
-----------
.. image:: https://github.com/sysjoint-tek/SSA463_SpectrumAnalyzer-v1.0.0/blob/main/SSA463-EN.png

.. image:: https://github.com/sysjoint-tek/SSA463_SpectrumAnalyzer-v1.0.0/blob/main/SSA463-ZN.png

Overview
-----------
This software is designed as a PC host application for the SSA463 handheld spectrum analyzer.
It provides real-time spectrum visualization, waterfall display, trace management, and data analysis functions.

Requirements
------------

- Python >= 3.3
- PyQt4 / PyQt5 / PySide / PySide2
- Qt.py (https://github.com/mottosso/Qt.py)
- PyQtGraph (http://www.pyqtgraph.org)

Download
--------
Download from the Release page
Single executable file provided
No installation required


Usage
-----
As the PC host computer for the SSA463 spectrum analyzer, it is used to connect to the SSA463 handheld spectrum analyzer , display real-time spectrum, waterfall chart , Multi-region screenshot, and import/export data .


Features:
--------
1. Quick device connection: When the connection function is activated, this software will automatically connect to available SSA463 devices without the need for manual selection of serial port, etc.
2. Real-time data display includes "real-time trace", "maximum hold", "minimum hold", "average trace", and "reference trace". The trace colors can be freely defined, and the "reference trace" can be freely named.
3. Waterfall chart display allows for free definition of zone colors.
4. Quickly modify the frequency, number of points, detection method, resolution, and bandwidth of the connected device.
5. Data export and import: It can simultaneously save "real-time trace", "maximum hold", "minimum hold" and "average trace", and can import up to 10 "reference traces".
6. Supports multi-window view, allowing selection of a local area of the spectrogram, drawing in an additional extended window, and synchronously displaying all traces of the selected area in the main window.
7. Channel power measurement allows you to freely select a region and calculate the power of the corresponding section.
8. Mark markers: Up to 10 marks can be displayed at the same time. You can long press or move them using the left and right keys.
9. Information bar display: The information bar at the bottom of the software records frequently used information, tags, etc. Clicking on it will quickly take you to the corresponding menu.
10. Multi-region screenshot: We've prepared multiple screenshot areas, which you can capture individually or select multiple at once, and we'll automatically stitch them together for you.


Troubleshooting
---------------
Device not detected
Check USB connection, replug device, or try another USB port.
Software not responding
Restart the application.

Version
-------
Windows Release version (v1.0)
This is a pre-built binary release. Source code is not included.

Notes
-----
Designed specifically for SSA463 hardware
No installation required
Standalone executable application
