# Stream Reactive Bridge

## Overview

Stream Reactive Bridge is a connector program that links the Chzzk (치지직) donation system with DRG's (Deep Rock Galactic) Stream Reactive Mod. It acts as a bridge to enable spawning monsters, waves, and supplies in-game based on Chzzk donations. The full system consists of the following components:

[DRG Stream Reactive Mod](https://mod.io/g/drg/m/stream-reactive-chzzk)

Stream Reactive Bridge (this program)

Chzzk Streaming Account

## Setup Guide

1. Install DRG and [Stream Reactive Mod](https://mod.io/g/drg/m/stream-reactive-chzzk)
Make sure Deep Rock Galactic and the Stream Reactive Mod are installed.

2. Prepare Your Chzzk Streaming Account
Your Chzzk account must be set up for donations.

3. Configure the Bridge Program
Run the Stream Reactive Bridge executable.

<img width="486" height="593" alt="image" src="https://github.com/user-attachments/assets/998594b1-b886-4636-9a36-2718c013cb3c" />

Click the "Login with Chzzk" button to start the authentication process.

The login is handled via the OAuth standard. The developer of this program does not have access to your ID/password.

<img width="486" height="593" alt="image" src="https://github.com/user-attachments/assets/d79c7a80-036b-4b02-8762-7a9e44fe6679" />

After logging in, set the Game Folder location.
By default, if you installed DRG via Steam, the folder is:

C:\Program Files (x86)\Steam\steamapps\common\Deep Rock Galactic

If the folder path is correct but DRG Stream Reactive Mod has not been run yet, you will see a yellow check mark.
Run the Stream Reactive Mod at least once to enable a green check mark for verification.

## Testing the Bridge

1. Start Deep Rock Galactic and ensure the Stream Reactive Mod is activated.

2. Note: Monster/wave spawning is disabled in the Space Rig (lobby).
Only test after entering a mission.

3. Once in a cave (mission), set a test amount in the "Donation Test" section at the bottom of the Bridge program and click the Test button.
The in-game effect should trigger according to your Stream Reactive Mod settings.

## Additional Notes

- All authentication is performed securely via OAuth. Your credentials are never seen or stored by the developer.
- For support or questions, please open an issue on this repository.
