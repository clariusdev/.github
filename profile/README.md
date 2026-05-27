# Clarius SDK

Welcome to the Clarius SDK — the home for the APIs, tools, and references used by
[partners](https://github.com/clariusdev/.github/blob/main/partners.md) and researchers
building on Clarius wireless ultrasound: commercial OEM solutions, real-time streaming,
signal processing, AI research, and more.

## Repositories

| Repository | What it's for |
| ---------- | ------------- |
| **[Solum](https://github.com/clariusdev/solum)** | OEM API for building standalone applications that connect **directly** to a Clarius scanner — no Clarius App required. Connectivity and imaging control on Windows, Linux, macOS, iOS, and Android. For commercial partners. |
| **[Cast](https://github.com/clariusdev/cast)** | Stream images and data in **real time** from a probe while the Clarius App is running. The simplest way to get live images and raw data for research. |
| **[Research](https://github.com/clariusdev/research)** | Raw data formats (RF / IQ / envelope) and readers, the in-app research tools, how imaging parameters are automated, and the low-level parameter reference. |
| **[IMU](https://github.com/clariusdev/imu)** | The integrated 9-DOF inertial measurement unit: data access, calibration, and orientation quaternions. |
| **[Cloud](https://github.com/clariusdev/cloud)** | Framework for pushing completed exams from Clarius Cloud into other platforms — clinical review, cloud AI and reporting, and EMR integrations. |

> **Texo** — script-driven research imaging for low-level control of the transmit/receive
> sequence — is coming soon.

## Which one do I need?

- **Build a standalone product that controls the probe directly** → **Solum** (requires an
  OEM partnership).
- **Get real-time images or data alongside the Clarius App** → **Cast**.
- **Analyze raw RF/IQ/envelope data or use the in-app research features** → **Research**
  (plus **IMU** for motion/orientation).
- **Integrate completed exams with your cloud, EMR, or AI service** → **Cloud**.

## Releases

The APIs are matched to the Clarius App: new binaries and source are published alongside
each App release, and there is no forward/backward compatibility across versions. Always
use the build that matches your App — see each repository's **Releases** page for the
latest.

## Partners

Clarius works with partners bringing new technologies into healthcare that need ultrasound
for real-time guidance and other clinical solutions. See the
[partners page](https://github.com/clariusdev/.github/blob/main/partners.md) for OEM
partnerships, cloud integrations, and how to get started.
