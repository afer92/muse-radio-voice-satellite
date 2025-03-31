# Raspiaudio Muse Radio Voice Satellite

   [![YouTube Video](https://img.youtube.com/vi/GGey_L-3grk/0.jpg)](https://youtu.be/GGey_L-3grk?si=UijGHBHlDbeWeOZH)
   
# New   
### This new version (2025.1.10) introduces the OTA Update of Home Assistant. From now on, updates will be very simple and almost automatic...  

## New Version: MuseRadioHomeAssistant

### New Features:

1. **Micro Wake Words**: Supports multiple wake words simultaneously - Alexa, Okay Nabu, Hey Jarvis, and Okay Croft. If you want to enable only one, you'll need to edit the YAML configuration.
   
2. **Sound Control**:
   - Adjust volume using the encoder's rotate function.
   - Toggle pause/play with an encoder click.

3. **Media Player**:
   - Recommended to use Music Assistant for transcoding, enabling any file format playback and avoiding the AAC bug on the player.

4. **Front-end Media Player Control**:
   - Stop via the station's encoder click to interact with the voice assistant.

5. **Buttons**: 
   - Buttons check, 1, 2, and 3 are hardcoded for direct radio station playback.

---

This ESPHome configuration transforms the [Raspiaudio Muse Radio](https://raspiaudio.com/product/muse-radio/) into a [Home Assistant](https://www.home-assistant.io/) voice satellite.

## ESPHome Radio for Raspiaudio Muse Radio

This project is intended for the **Raspiaudio Muse Radio**.

### Flashing Your Device

1. Open **Google Chrome**.
2. Visit [apps.raspiaudio.com](https://apps.raspiaudio.com).
3. Select **Muse Radio - Home Assistant** and follow the on-screen instructions.
4. Connect to the access point created by the device with the following credentials:
   - SSID: "Raspiaudio-radio"
   - Password: "12345678"
5. Open a webpage at `192.168.4.1/?save` to set your home Wi-Fi credentials.

### Source Code

The source code is available on GitHub: [Raspiaudio Muse Radio Voice Satellite](https://github.com/RASPIAUDIO/muse-radio-voice-satellite). To recompile, ensure you perform a full build clean in ESPHome first.

### Forum & Support

For discussions and support, visit the [Raspiaudio Forum](https://forum.raspiaudio.com/t/muse-radio-home-assistant/).

### Step-by-Step Video Guide

For a detailed video tutorial, watch this [**step-by-step guide**](https://youtu.be/QDDjXAWuk0E). It was created for the Luxe model but is also applicable to the Muse Radio.
