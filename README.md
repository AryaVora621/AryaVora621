# Arya Vora

Robotics, CAD and embedded systems. I'm a junior (class of 2028) at John P. Stevens High School in Edison, NJ.

- Website: [www.arya-vora.org](https://www.arya-vora.org)
- LinkedIn: [linkedin.com/in/aryavora](https://linkedin.com/in/aryavora)
- Email: [aryavora621@gmail.com](mailto:aryavora621@gmail.com)

## About

I build robots: the mechanical design in Onshape, the circuit boards in KiCad, the firmware, and the code around them. Mechanical design is the part I'm strongest at. Electronics and control software are what I'm learning, so several projects below are still in progress, and each one says how far it got.

## FTC Team 23786 MakEMinds

I co-founded MakEMinds in 2023 and I'm the team captain for the 2026-27 season. Before MakEMinds, the team had an FLL team, 45814. In 2025-26 I was Mechanical Lead ("Built the robot and made design changes", per the team portfolio), and in 2024-25 I was Design Lead. My part is the CAD and the build. The robot code is written by our programming team.

Results, as recorded on [FTCScout](https://ftcscout.org/teams/23786):

2025-26 (DECODE)

- New Jersey Championship, 2026-03-15: Parkway Division Winning Alliance, Captain, and Finalist Alliance, Captain. We went 5-0 in qualification in the Parkway Division, ranked 1st of 24.
- Inspire Award, 2nd place, Upper Central League Tournament, 2026-02-14.
- FIRST Championship, Ross Division, Houston: 5-5.
- US Governors Cup, Washington DC (FTCScout lists it as a scrimmage): 4-1 in qualification, ranked 5th of 51.

2024-25 (INTO THE DEEP)

- Control Award, 1st place, New Jersey Championship, 2025-03-16, and Turnpike Division Finalist Alliance, Captain.
- Think Award, 1st place, and Inspire Award, 3rd place, Upper Central League Tournament, 2025-02-15.

### Reaper, the 2025-26 robot

From the team's engineering portfolio (numbers are the team's own):

- A full-width intake that lifts to conform to the game pieces, with mecanum wheels that push them in from the side, and a gecko-wheel transfer.
- A flywheel shooter with a servo-angled hood. A Limelight 3A on the shooter reads AprilTags to set the angle and RPM automatically. The portfolio reports all three stored pieces shot within a second.
- Pedro Pathing for autonomous paths, with goBILDA Pinpoint localization. The portfolio reports autonomous success rising from 52% to 92% over the season.
- Five robot iterations, ending in the smallest and lightest chassis.

## FRC Team 2554 The Warhawks

Board member of FRC Team 2554, The Warhawks, in Edison, NJ ([The Blue Alliance](https://www.thebluealliance.com/team/2554)).

## Projects

Status is as of October 2026.

- **[roboPet](https://github.com/AryaVora621/roboPet)**: a four-legged robot based on the open-source Sesame design. A Raspberry Pi Pico running MicroPython drives the servos and reads an MPU6050 IMU. A Pi Zero 2W is planned for the camera and audio. The 8-servo MVP chassis was designed in Onshape and printed on a Bambu Lab A1 Mini. Status: partly assembled. The gait and inverse kinematics are not written yet, so it does not walk.
- **Gerald Rev 2** (private repo): a carrier board for a 6-axis desk arm, with an ESP32-S3 and six Feetech STS3215 servos, designed around a 12 V, 10 A servo bus. Status: the schematic is complete and 79 parts are placed on a 100 by 105 mm board. The board is not routed yet, and the arm is not built.
- **[ESP32 QuadX Drone](https://github.com/AryaVora621/drone)**: a quadcopter built on the open-source esp-fc flight firmware, with a handheld ESP-NOW joystick transmitter. Status: it flew once, on 2026-07-18, and crashed, breaking two propellers. I'm rebuilding it and retesting the radio link.
- **[Orochi Toolchanger](https://github.com/AryaVora621/orochi)**: a plan to rebuild an Ender 5 Pro as a CoreXY toolchanger running Klipper, with StealthChanger docks. It builds on ZeroG Mercury One.1 and StealthChanger. Status: in planning. There are design docs and a parts list, and nothing is built yet.
- **[M.I.R.A.](https://github.com/AryaVora621/m.i.r.a)**: a design for a room assistant with gesture and voice control, a core daemon planned in Rust, and projector calibration using ArUco markers. Status: design only. The repo holds architecture specs and no code yet.
- **[Nana E-Book Reader](https://github.com/AryaVora621/nana-ebook-reader)**: an offline reading aid for a family member with dyslexia. A camera photographs a book page, OpenCV and Tesseract read it, and Piper reads it aloud, all on a Pi Zero 2W. Status: built and running.
- **[notchTerm](https://github.com/AryaVora621/notchTerm)**: a macOS menu-bar app that puts an overlay at the MacBook notch for Claude CLI and Codex CLI sessions in Terminal.app. It reads each session's output over AppleScript and sends what I type to the matching tab. Status: working, built from source with `swift build`.
- **[SmartInvest](https://github.com/AryaVora621/SmartInvest)**: a stock research dashboard. Its Research tab streams a cited, web-searched report, and it has a screener for emerging markets. Status: working, last updated September 2026.
- **[arya-vora.org](https://github.com/AryaVora621/arya-vora.org)**: my portfolio site, built with Next.js, Three.js and GSAP.

## Tools

- CAD: Onshape, Fusion 360
- Electronics: KiCad 8, ESP32, Raspberry Pi Pico and Zero 2W
- Fabrication: Bambu Lab A1 Mini, Klipper
- Code: C++, MicroPython, Python, TypeScript, Next.js, Swift
