# capstone-planning

## Autonomous AGV for Real-Time Warehouse Inventory Tracking System

## Project summary

This project builds a mountable component on the autonomous ground vehicle (AGV) capable of driving warehouse aisles independently while using onboard edge-AI perception to detect and log inventory in real time.

The project is sponsored by **SEW Eurodrive Innovation Hub** (R&D robotics branch), which is providing the team access to an unused small-size AGV for development and testing.

### Software approach

The system builds on existing infrastructure rather than starting from scratch:

- PLC coding onto a UHX controller
- Open-source autonomous driving and localization frameworks
- Order send/receive infrastructure (existing, integrated rather than built new)

The core software challenge for this team is **system design and integration** rather than building autonomy or localization from the ground up.

### Hardware approach

The key hardware challenge is a camera mounted on the AGV's lift mast, which adjusts height as needed to scan inventory at different shelf levels. This camera feeds into a perception application developed by the team to detect and identify inventory in real time.

## Sponsor

**SEW Eurodrive Innovation Hub** (R&D robotics branch)

## Links

- Code repository: [link]
- Roadmap / Project board: [link]
- Live demo (if applicable): [link]
- Course syllabus / assignment brief: [link]

## About this repository

The repository tracks project management artifacts for the capstone.

### Key files

- `CHARTER.md` — problem statement, objectives, scope, and success criteria
- `ROADMAP.md` — deadlines and milestones (course + internal), mirrors the GitHub Project board
- `RISKS.md` — risk register, updated regularly
- `meeting-notes/` — dated notes from team meetings and advisor check-ins
