VisionMetrics ESP32
Overview

VisionMetrics ESP32 is an open-source visual testing platform built on the ESP32 microcontroller. It presents controlled visual stimuli on a TFT display and records user responses to measure aspects of visual performance such as acuity, contrast sensitivity, and reaction time.

This project is designed as a low-cost, portable experimental system for structured visual testing and self-tracking under consistent conditions.

It is not a medical device and is not intended for diagnosis or treatment.

Purpose

The goal of this project is to create a simple, extensible platform for:

Running repeatable visual perception tests
Measuring response accuracy and reaction time
Tracking changes in visual performance over time
Exploring human visual processing using embedded systems
Core Features (Planned / In Progress)
Visual Acuity Test
Orientation-based optotypes (e.g. directional “E” shapes)
Scalable size levels to approximate resolution thresholds
Contrast Sensitivity Test
Fixed-size targets with variable contrast
Measures detection under low visibility conditions
Reaction Time Test
Timed visual stimuli
Measures latency between stimulus and user response
Peripheral Detection (Planned)
Stimuli presented outside central focus area
Measures detection speed and attention spread
System Overview

Hardware:

ESP32 (DevKit or compatible)
SPI TFT display (ILI9341 / ST7789)
Button inputs (or rotary encoder)

Software:

Arduino framework (initial target)
TFT_eSPI or similar display library
Modular test system (planned)
Intended Use
Personal visual performance tracking
Embedded systems experimentation
Human-computer interaction testing
Educational demonstrations of perception measurement
Prototyping low-cost visual testing tools
Limitations
Not medically calibrated
Results depend on consistent viewing distance and lighting
Provides relative measurements, not clinical assessments
Does not replace professional eye testing
Project Philosophy

This project treats visual testing as a stimulus → response system:

Visual input is controlled and repeatable
User responses are measured quantitatively
Performance is tracked over time

The focus is on measurement and consistency, not claims of vision improvement or correction.

Roadmap

Phase 1

Basic test modes (acuity, contrast, reaction)
Simple UI and input handling

Phase 2

Calibration system (distance + scaling)
Structured test sessions

Phase 3

Data logging (SD card / memory)
Performance tracking over time

Phase 4

Improved UI/UX
Modular architecture for adding new tests
Contributing

Contributions are welcome. Areas that need work:

Test algorithm design (e.g. proper scaling methods)
Display rendering optimization
Input handling and UI systems
Data logging and analysis
Hardware layouts and wiring diagrams

If contributing:

Keep code modular and readable
Avoid unnecessary complexity
Focus on repeatability and measurement accuracy
Getting Started (Planned)

Instructions will include:

Hardware setup (wiring + components)
Library dependencies
Upload process for ESP32
Running initial test modes
License

(To be added — recommend MIT or Apache 2.0)

Status

Early-stage concept and development. Core structure and testing framework are being defined.
