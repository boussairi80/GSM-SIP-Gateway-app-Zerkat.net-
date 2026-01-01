Android app GSM ↔ SIP Gateway replace the old gsm gateway hardware 

🚀 Key Capabilities
📱 Android-Powered GSM Gateway

Turn supported Android devices into fully functional SIP ↔ GSM gateways using SIM cards.

🔁 Two-Way Call Bridging

SIP → GSM (outbound calls via SIM)

GSM → SIP (incoming GSM calls routed to SIP)

🧩 No Dedicated Hardware Required

No GoIP boxes, GSM modems, antennas, or proprietary gateway hardware.









1. SIP call is received by the SIP endpoint
2. Application extracts the destination number from SIP call
3. Initiates outgoing GSM call using the telephony endpoint
4. Bridges audio between SIP and GSM calls
5. Handles call state synchronization (ringing, connected, terminated)
this app demonstrates a **working and deployable solution**,
with confirmed call routing between SIP and GSM networks.
This project turns a supported Android phone into a full GSM ↔ SIP Gateway, functioning similarly to a GoIP device, but implemented entirely in software, works on any sumsung android device

By leveraging the Android telephony stack and SIP integration, a standard Android device can act as a GoIP replacement, enabling two-way call routing between GSM (SIM) and SIP/VoIP systems without dedicated GSM gateway hardware.

🌐 Project website: https://zerkat.net

🔎 What This Project Is

An Android-based GSM SIP Gateway

A software alternative to GoIP hardware

A solution to bridge SIP/VoIP systems with GSM networks

Designed for Asterisk / FreePBX / SIP PBX integration

Suitable for portable, remote, and cost-sensitive deployments



🚀 Portable & Flexible

Ideal for:

Mobile deployments

Remote locations

Temporary installations

Backup routing

Disaster recovery scenarios

💰 Cost-Effective

Significantly reduces:

Hardware costs

Installation complexity

Maintenance overhead

📈 Simple Scalability

Scale horizontally by adding more authorized Android devices.

🧠 Typical Use Cases

Replace GoIP GSM gateways with Android phones

SIP trunk breakout to GSM

GSM backup routing for PBX systems

Mobile or field-deployed GSM gateways

Low-cost multi-SIM SIP routing

⚙️ System Requirements

🚀 Mandatory Requirements

✅ Root access is required

✅ Samsung Android devices only (officially supported)

✅ Any Android version supported

⚠️ Additional Notes

Other devices (Oppo, Huawei, Xiaomi, etc.) or custom ROMs may work
but are not officially supported

This project is not intended for Google Play Store distribution

🏗️ Architecture Overview

The application replaces traditional GSM gateway hardware by:

Using the Android telephony stack for GSM call handling

Bridging audio and signaling with SIP accounts

Acting as a software GSM ↔ SIP bridge

Integrating directly with SIP PBX systems (Asterisk / FreePBX)

📦 APK Distribution & Trial Policy

This repository includes a prebuilt APK for evaluation and testing purposes.

Due to the nature of telecom systems and SIM-based routing, the application uses a device-binding security mechanism.

🔐 Device Binding & Authorization

Each installation is bound to a specific device

Devices must be explicitly authorized by our server

Unauthorized devices:

❌ Cannot place calls

❌ Cannot receive calls

This approach prevents abuse and ensures controlled, legitimate usage.

🧪 Free Trial

⏱ 7-day free trial available upon request

Trial starts after device authorization

During the trial:

All core GSM ↔ SIP features are enabled

After the trial period:

Continued usage requires approval or a commercial agreement

📝 How to Request Access

Install the provided APK

Launch the application

Submit your device ID through the application interface

Wait for server authorization

Once approved, the trial period starts automatically

⚠️ Important Notes

Root access is always required

Device authorization is manual

This project is not fully open-source

The APK is provided for evaluation and testing only

📜 Licensing & Usage

Source code in this repository is provided for reference and documentation

The APK remains proprietary

❌ Redistribution of the APK is not permitted without written permission

🌐 More Information

For documentation, access requests, and commercial inquiries, visit:

👉 https://zerkat.net
