Exapod – Modular Six-Leg Robot

Work in progress.
This repository documents the development of a fully custom hexapod robot, including mechanics, electronics, and joint calibration methods. Firmware will be added as soon as actual implementation work begins.

Main Features

Modular legs with GXServo QY3242BLS brushless servos

Absolute encoders (AS5600 or MT6835) on each joint

Mechanical structure in aluminium and 3D-printed parts

Custom power distribution (TDK-Lambda i7A, TVS protection, BTS443P high-side switches)

Detailed joint calibration pipeline (calibrated offsets, linear mapping, MAG/AGC reference)

Repository Structure

mechanics/
Models, drawings, 3D-printed parts, and laser-cut parts.

electronics/
Schematics, power distribution notes, and component documentation.

docs/
Calibration data, measurements, reference notes, and project documentation.

firmware/
To be added later.
(No firmware is included yet; real implementation will be published once development begins.)

Project Status

Mechanical prototype for a full leg completed

Encoder diagnostics and calibration procedure defined

Power system under evaluation

Full controller firmware not started yet (will be documented here when available)
