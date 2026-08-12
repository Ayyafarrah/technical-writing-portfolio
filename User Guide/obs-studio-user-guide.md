# **OBS Studio Documentation**

##  1. Introduction
OBS Studio (Open Broadcaster Software Studio) is a free and open-source application for video recording and live streaming.

OBS Studio allows users to capture and combine multiple sources, such as:
1. Display or window captures
1. Webcams
1. Microphones
1. Application audio
1. Images
1. Videos
1. Browser content

This documentation provides a beginner-friendly guide to installing and using OBS Studio for basic screen recording.

**Purpose**
This guide is intended to help first-time users:

1. Install OBS Studio.
1. Understand the OBS Studio interface.
1. Create and configure a scene.
1. Add video and audio sources.
1. Configure basic recording settings.
1. Record a screen using OBS Studio.

**Target Audience**

This documentation is intended for users who have little or no previous experience with OBS Studio.
##  2. System Requirements
Before installing OBS Studio, make sure your computer meets the minimum requirements for your operating system.

**Supported Operating Systems**
OBS Studio supports major desktop operating systems, including:
1. Windows
1. macOS
1. Linux

**Hardware Considerations**

The hardware requirements may vary depending on the recording or streaming workload.

For example, recording at higher resolutions or frame rates may require more processing power.

|Component	|Consideration|
|---|---|
|Processor	|A modern CPU is recommended for video recording and encoding.|
|Graphics	|GPU capabilities may affect recording and rendering performance.|
|Memory	|More memory may be required when using multiple sources or applications.|
|Storage	|Recorded videos can require significant storage space.|
|Internet	|A stable internet connection is required for live streaming.|
> Note: System requirements may vary depending on the selected resolution, frame rate, encoder, and number of sources.
{.is-info}

##  3. Installation Guide
This section explains how to install OBS Studio on Windows.
**Step 1: Download OBS Studio**
1. Open the official OBS Studio website.
1. Select the Windows download option.
1. Download the installer.
1. Wait until the download is complete.
 
> Tip: Download OBS Studio from the official OBS Studio website to ensure that you are using the legitimate software.
> 


**Step 2: Run the Installer**
1. Locate the downloaded installer.
1. Double-click the installer file.
1. If Windows displays a security confirmation, review the information and continue if appropriate.

**Step 3: Start the Installation**
1. Follow the instructions displayed by the installation wizard.
1. Review the license information.
1. Select the installation location if prompted.
1. Continue with the installation.
1. Wait until the installation process is complete.

**Step 4: Launch OBS Studio**
After the installation is complete:

1. Launch OBS Studio.
1. Wait for the application to initialize.
1. The OBS Studio main window should appear.

![First page.png](User Guide/First page.PNG)
📸 OBS Studio main interface after installation.

## 4. Getting Started
### 4.1 Interface Overview
When OBS Studio is opened, the main interface is divided into several sections.

**Main Interface Components**
|Component	|Description
|---|---|
|Preview	|Displays the current scene output.
|Scenes	|Contains the scenes available in the current OBS Studio profile.
|Sources	|Contains the visual and audio sources assigned to the selected scene.
|Audio |Mixer	Displays and controls audio sources.
|Scene |Transitions	Controls transitions between scenes.
|Controls	|Provides access to recording, streaming, settings, and other functions.|

![capture1.png](/capture1.png){.align-center}

📸 Label the main OBS Studio interface.
### 4.2 Create a Scene
A Scene is a collection of sources that determines what appears in the recording or stream.

To create a scene:

1. Open OBS Studio.
1. Locate the Scenes panel.
1. Click the + button.
1. Enter a name for the scene.
1. Click OK.

The new scene will appear in the Scenes panel.
![Scene.png](/Scene.png)
> Tip: Use descriptive scene names to make your OBS Studio setup easier to manage.
> 
{.is-info}

### 4.3 Add a Source
After creating a scene, you need to add one or more sources.

For example, to record your screen:
1. Select the scene you created.
1. Locate the Sources panel.
1. Click the + button.
1. Select Display Capture.
1. Enter a name for the source if prompted.
1. Select the display you want to capture.
1. Confirm the configuration.

The selected display should now appear in the preview area.
**Common Source Types**
|Source	|Purpose|
|---|---|
|Display Capture	|Captures an entire display.
|Window Capture	|Captures a specific application window.
|Video Capture |Device	Captures video from a webcam or other compatible device.
|Image	|Displays an image in the scene.
|Media Source	|Adds a video or audio file.
|Browser	|Displays web-based content.
> Note: Available source options may vary depending on the operating system and OBS Studio configuration.
{.is-info}

### 4.4 Configure Audio
OBS Studio can capture audio from different sources, such as your microphone and system audio.

**Configure a Microphone**
1. Locate the Audio Mixer panel.
1. Check whether a microphone source is available.
1. Speak into the microphone.
1. Observe the audio level indicator.

If the microphone is working correctly, the audio level should respond to your voice.

**Adjust Audio Volume**
Use the volume slider in the Audio Mixer to adjust the input level.

> Tip: Avoid setting the microphone level too high because excessive input levels can cause audio distortion.
{.is-info}

### 4.5 Start Recording
Before starting the recording, verify that:

- The correct scene is selected.
- The required sources are visible.
- Your microphone is working.
- The desired audio sources are enabled.
To start recording:

1. Select the scene you want to record.
1. Check the preview.
1. Confirm the audio levels.
1. Click Start Recording.
1. Perform the actions you want to record.
To stop the recording:

1. Return to OBS Studio.
1. Click Stop Recording.
1. Wait for OBS Studio to finish processing the recording.

The recorded file will be saved according to the configured recording path.

## 5. Recording Guide
This section provides a basic workflow for recording a screen using OBS Studio.

**Basic Recording Workflow**

```diagram
PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHN0eWxlPSJiYWNrZ3JvdW5kOiB0cmFuc3BhcmVudDsgYmFja2dyb3VuZC1jb2xvcjogdHJhbnNwYXJlbnQ7IGNvbG9yLXNjaGVtZTogbGlnaHQgZGFyazsiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB2ZXJzaW9uPSIxLjEiIHdpZHRoPSIxNzBweCIgaGVpZ2h0PSIyNzBweCIgdmlld0JveD0iMCAwIDE3MCAyNzAiIGNvbnRlbnQ9IiZsdDtteGZpbGUgaG9zdD0mcXVvdDtlbWJlZC5kaWFncmFtcy5uZXQmcXVvdDsmZ3Q7Jmx0O2RpYWdyYW0gaWQ9JnF1b3Q7UTJ4SjlLdjBhR1VPTUNRTExlOVMmcXVvdDsgbmFtZT0mcXVvdDtQYWdlLTEmcXVvdDsmZ3Q7clpSZFQrc3dESVovVFMrUnVoWTJ6dVVvWTRnUHdhRkhCNGtiRkJvdmpVaWI0cnAwNDlmanRpbGROWkNRTnFtS25DZjJtOFNwN1lWUnRsNmlLTkpiSzhGNGdTL1hYbmp1QmNIcDFPZXhBWnNPSE0vQ0RpalVza09UQWNUNkF4eDBjYXJTRXNxUkkxbHJTQmRqbU5nOGg0UkdUQ0RhZXV5MnNtYThheUVVN0lBNEVXYVhQbXBKcWJ2V2lUL3dTOUFxN1hlZStHNGxFNzJ6QTJVcXBLMjNVTGp3d2dpdHBjN0sxaEdZSm5kOVhycTRpeDlXdnc2R2tOTnZBcDRYMmZYdHcwbjVvdi81eS84M3M2ZWp2MWRIMzZnNFZOS216d0hCbXRmTzZsUVR4SVZJR2x6emF6TkxLVE04bTdBcGpGWTUyd2tyQVRMb2RONkZxWnpPWFFFNWs3dXptTWVZS3FtdEYweE5vLzJDYkNscW8veHZ2a1hnblU2OVArR3VmNFFnQ0pyWGJrUjVjOWhmY3k0bE81enJzakJpdzFZa0NxcndBTUtSelZkYXRWTCsvRUQzVHlGNVpaZDdoSGNOOWY2Q01Ra2tkbm1BeEtMVXVkcGY4aDV3WlRGclJkOHFqZENrZDU2UXRubDVpQVBiNHJEbjdYUGFTYmFudmRCY0RkMFBEY2dGc1ZVcnJ0eVdZRE1nYlA2WGRLc2pCRE5YLy9YUVBpWTljekpCM3pSY2t3eVAzVnk0N3FXK3RJY0NaOFBWZUQ4ZGVrbTd0dFdRdzhVbiZsdDsvZGlhZ3JhbSZndDsmbHQ7L214ZmlsZSZndDsiPjxkZWZzLz48Zz48ZyBkYXRhLWNlbGwtaWQ9IjAiPjxnIGRhdGEtY2VsbC1pZD0iMSI+PGcgZGF0YS1jZWxsLWlkPSJfRW1LTVI1c2JpVDBHVkw3Wi1RSi0xIj48Zz48cmVjdCB4PSIwIiB5PSIwIiB3aWR0aD0iMTcwIiBoZWlnaHQ9IjI3MCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJub25lIiBwb2ludGVyLWV2ZW50cz0iYWxsIi8+PC9nPjxnPjxnPjxzd2l0Y2g+PGZvcmVpZ25PYmplY3Qgc3R5bGU9Im92ZXJmbG93OiB2aXNpYmxlOyB0ZXh0LWFsaWduOiBsZWZ0OyIgcG9pbnRlci1ldmVudHM9Im5vbmUiIHdpZHRoPSIxMDAlIiBoZWlnaHQ9IjEwMCUiIHJlcXVpcmVkRmVhdHVyZXM9Imh0dHA6Ly93d3cudzMub3JnL1RSL1NWRzExL2ZlYXR1cmUjRXh0ZW5zaWJpbGl0eSI+PGRpdiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94aHRtbCIgc3R5bGU9ImRpc3BsYXk6IGZsZXg7IGFsaWduLWl0ZW1zOiB1bnNhZmUgZmxleC1zdGFydDsganVzdGlmeS1jb250ZW50OiB1bnNhZmUgY2VudGVyOyB3aWR0aDogMTY4cHg7IGhlaWdodDogMXB4OyBwYWRkaW5nLXRvcDogN3B4OyBtYXJnaW4tbGVmdDogMXB4OyI+PGRpdiBzdHlsZT0iYm94LXNpemluZzogYm9yZGVyLWJveDsgZm9udC1zaXplOiAwOyB0ZXh0LWFsaWduOiBjZW50ZXI7IGNvbG9yOiAjMDAwMDAwOyAiPjxkaXYgc3R5bGU9ImRpc3BsYXk6IGlubGluZS1ibG9jazsgZm9udC1zaXplOiAxMnB4OyBmb250LWZhbWlseTogSGVsdmV0aWNhOyBjb2xvcjogbGlnaHQtZGFyaygjMDAwMDAwLCAjZmZmZmZmKTsgbGluZS1oZWlnaHQ6IDEuMjsgcG9pbnRlci1ldmVudHM6IGFsbDsgd2hpdGUtc3BhY2U6IG5vcm1hbDsgd29yZC13cmFwOiBub3JtYWw7ICI+T3BlbiBPQlMgU3R1ZGlvPGJyIC8+ICAgICAgIOKGkzxiciAvPkNyZWF0ZSBhIFNjZW5lPGJyIC8+ICAgICAgIOKGkzxiciAvPkFkZCBEaXNwbGF5IENhcHR1cmU8YnIgLz4gICAgICAg4oaTPGJyIC8+Q29uZmlndXJlIEF1ZGlvPGJyIC8+ICAgICAgIOKGkzxiciAvPkNoZWNrIFByZXZpZXc8YnIgLz4gICAgICAg4oaTPGJyIC8+U3RhcnQgUmVjb3JkaW5nPGJyIC8+ICAgICAgIOKGkzxiciAvPlBlcmZvcm0gUmVxdWlyZWQgQWN0aW9uczxiciAvPiAgICAgICDihpM8YnIgLz5TdG9wIFJlY29yZGluZzxiciAvPiAgICAgICDihpM8YnIgLz5DaGVjayBSZWNvcmRlZCBGaWxlPC9kaXY+PC9kaXY+PC9kaXY+PC9mb3JlaWduT2JqZWN0Pjx0ZXh0IHg9Ijg1IiB5PSIxOSIgZmlsbD0iIzAwMDAwMCIgZm9udC1mYW1pbHk9IkhlbHZldGljYSIgZm9udC1zaXplPSIxMnB4IiB0ZXh0LWFuY2hvcj0ibWlkZGxlIiBzdHlsZT0iZmlsbDogbGlnaHQtZGFyayhyZ2IoMCwgMCwgMCksIHJnYigyNTUsIDI1NSwgMjU1KSk7Ij48dHNwYW4geD0iODUiIHk9IjE5Ij5PcGVuIE9CUyBTdHVkaW88L3RzcGFuPjx0c3BhbiB4PSI4NSIgeT0iMzMiPuKGkzwvdHNwYW4+PHRzcGFuIHg9Ijg1IiB5PSI0NyI+Q3JlYXRlIGEgU2NlbmU8L3RzcGFuPjx0c3BhbiB4PSI4NSIgeT0iNjEiPuKGkzwvdHNwYW4+PHRzcGFuIHg9Ijg1IiB5PSI3NSI+QWRkIERpc3BsYXkgQ2FwdHVyZTwvdHNwYW4+PHRzcGFuIHg9Ijg1IiB5PSI4OSI+4oaTPC90c3Bhbj48dHNwYW4geD0iODUiIHk9IjEwMyI+Q29uZmlndXJlIEF1ZGlvPC90c3Bhbj48dHNwYW4geD0iODUiIHk9IjExNyI+4oaTPC90c3Bhbj48dHNwYW4geD0iODUiIHk9IjEzMSI+Q2hlY2sgUHJldmlldzwvdHNwYW4+PHRzcGFuIHg9Ijg1IiB5PSIxNDUiPuKGkzwvdHNwYW4+PHRzcGFuIHg9Ijg1IiB5PSIxNTkiPlN0YXJ0IFJlY29yZGluZzwvdHNwYW4+PHRzcGFuIHg9Ijg1IiB5PSIxNzMiPuKGkzwvdHNwYW4+PHRzcGFuIHg9Ijg1IiB5PSIxODciPlBlcmZvcm0gUmVxdWlyZWQgQWN0aW9uczwvdHNwYW4+PHRzcGFuIHg9Ijg1IiB5PSIyMDEiPuKGkzwvdHNwYW4+PHRzcGFuIHg9Ijg1IiB5PSIyMTUiPlN0b3AgUmVjb3JkaW5nPC90c3Bhbj48dHNwYW4geD0iODUiIHk9IjIyOSI+4oaTPC90c3Bhbj48dHNwYW4geD0iODUiIHk9IjI0MyI+Q2hlY2sgUmVjb3JkZWQgRmlsZTwvdHNwYW4+PC90ZXh0Pjwvc3dpdGNoPjwvZz48L2c+PC9nPjwvZz48L2c+PC9nPjxzd2l0Y2g+PGcgcmVxdWlyZWRGZWF0dXJlcz0iaHR0cDovL3d3dy53My5vcmcvVFIvU1ZHMTEvZmVhdHVyZSNFeHRlbnNpYmlsaXR5Ii8+PGEgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMCwtNSkiIHhsaW5rOmhyZWY9Imh0dHBzOi8vd3d3LmRyYXdpby5jb20vZG9jL2ZhcS9zdmctZXhwb3J0LXRleHQtcHJvYmxlbXMiIHRhcmdldD0iX2JsYW5rIj48dGV4dCB0ZXh0LWFuY2hvcj0ibWlkZGxlIiBmb250LXNpemU9IjEwcHgiIHg9IjUwJSIgeT0iMTAwJSI+VGV4dCBpcyBub3QgU1ZHIC0gY2Fubm90IGRpc3BsYXk8L3RleHQ+PC9hPjwvc3dpdGNoPjwvc3ZnPg==
```

**Recommended Pre-Recording Checklist**
- [ ] Select the correct scene.
- [ ] Verify the display capture.
- [ ] Check microphone input.
- [ ] Check system audio.
- [ ] Confirm available storage space.
- [ ] Review recording settings.
- [ ] Perform a short test recording.

## 6. Common Settings
OBS Studio provides various settings that control how recordings are captured and stored.

**Output Settings**
Output settings can affect:

- Recording quality
- File format
- Encoder
- Recording location
- Bitrate

**Video Settings**
Video settings include options such as:

- Base Canvas Resolution
- Output Resolution
- Common FPS Value

Higher resolutions and frame rates may require more system resources.

**Audio Settings**

Audio settings control the audio devices and sample rate used by OBS Studio.
> Note: The recommended configuration depends on the user's hardware and recording requirements.
{.is-info}

## 7. Troubleshooting
**OBS Studio Does Not Detect My Microphone**

**Possible causes:**

- The microphone is not connected.
- The wrong input device is selected.
- Windows does not have permission to access the microphone.
- Another application is using the microphone.

**Recommended actions:**

- Check whether the microphone is connected.
- Check the selected audio device in OBS Studio.
- Check Windows microphone permissions.
- Restart OBS Studio if necessary.

**The Recording Is Lagging**

Possible causes include insufficient system resources, high recording settings, or an unsuitable encoder configuration.

Try:

1. Lowering the output resolution.
1. Reducing the frame rate.
1. Closing unnecessary applications.
1. Checking CPU/GPU usage.
1. Reviewing the selected encoder.

## 8. FAQ
**What is OBS Studio?**

OBS Studio is a free and open-source application used for video recording and live streaming.

**Can OBS Studio record my screen?**

Yes. OBS Studio can capture an entire display or a specific application window.

**Can I record my webcam?**

Yes. A compatible webcam can be added as a Video Capture Device source.

**Can I record my microphone?**

Yes. OBS Studio can capture audio from a configured microphone.

**Is OBS Studio free?**

Yes. OBS Studio is free and open-source software.

**Where is my recording saved?**

The recording is saved in the configured recording location. You can check or change the location through OBS Studio's output settings.
## 9. References
**commended references:**

- Official OBS Studio website
- Official OBS Studio documentation
- OBS Studio GitHub repository
