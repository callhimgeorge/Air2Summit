# Air2Summit

Air2Summit is a modular hiking pole system intended for travel, field repair, and adaptation to different terrain and use cases.

This repository publishes the parts of the system that can be shared without exposing critical proprietary design work. The goal is practical openness: release the components that benefit from community improvement, while keeping safety-critical and supplier-specific assemblies under controlled development.

## Scope

Open in this repository:

- Interchangeable tips
- Accessory mounts
- Small accessories and attachment parts
- Reference documentation for the open interfaces

Closed and not included here:

- Structural joints
- Locking systems
- Supplier-specific parts and protected manufacturing details
- Any component where uncontrolled replication could create avoidable safety or reliability risk

## Design Approach

Air2Summit is open where possible, not open at any cost.

That means the published hardware is intended to be useful on its own, mechanically understandable, and easy to modify. At the same time, the project does not publish assemblies that carry primary structural loads, depend on confidential sourcing, or require controlled validation before release.

## License

Open hardware files in this repository are provided under the CERN-OHL-W v2 license unless stated otherwise in a specific file or directory.

See [LICENSE.txt](C:\Users\george\Documents\GitHub\Air2Summit\LICENSE.txt).

## Repository Layout

- `docs/` - project overview and assembly guidance
- `cad/tips/` - open tip system files and notes

Additional open modules may be added over time as interfaces stabilize and release criteria are met.

## Usage Disclaimer

The files in this repository are provided for development, evaluation, and modification by technically competent users. They are not a certification, warranty, or claim of fitness for life-safety use.

If you manufacture or modify parts from these files, you are responsible for material selection, process control, inspection, field testing, and compliance with any applicable regulations.
