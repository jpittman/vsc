# Desktop Audio Setup

This is a simple breakdown of the audio setup defaults for streaming in both XSplit and OBS. It's based upon this [video](https://www.youtube.com/watch?v=EdAhR_CdjLc).

### Windows Audio Settings

1. Open Windows Audio Settings.
1. In the Playback tab, make sure VoiceMeeter Input is set to the Default Device.

![Windows Audio](/assets/images/audio-setup/windows_audio.png)

### VoiceMeeter Banana

Start with making sure that Hardware Input 1 is set to the microphone. In this case, the Yeti Mic and make sure to priortize WDM over MME for latency reasons.

![Hardware Input 1](/assets/images/audio-setup/hardware_input_1.png)

Then you want to make sure that Hardware Input 2 is set to CABLE-A Output (VB-Audio Cable A). Again, prioritize WDM.

![Hardware Input 2](/assets/images/audio-setup/hardware_input_2.png)

And to be able to monitor what you're mixing together, make sure that Hardware Output A1 is set to headphones. Again, prioritize WDM.

![Hardware Output 1](/assets/images/audio-setup/hardware_output_a1.png)

### Discord
1. Open Discord.
1. In Discord, navigate to Settings and then to the Voice section.
1. In the Voice Section, Input Device should be the Yeti Mic. Again, prioritize WDM.

![Discord Input Device](/assets/images/audio-setup/discord_input_device.png)


1. In the Voice Section, Output Device should be set to CABLE-A Output (VB-Audio Cable A). Again, prioritize WDM.

![Discord Output Device](/assets/images/audio-setup/discord_output_device.png)


### Zoom
1. Open Zoom.
1. In Zoom, navigate to Settings and then to the Audio section.
1. In the Audio Section, Input Device should be the Yeti Mic. Again, prioritize WDM.

![Zoom Input Device](/assets/images/audio-setup/zoom_input_device.png)

1. In the Audio Section, Output Device should be set to CABLE-B Output (VB-Audio Cable B). Again, prioritize WDM.

![Zoom Output Device](/assets/images/audio-setup/zoom_output_device.png)


### OBS Studio
1. Open OBS Studio
1. In OBS, navigate to settings and then audio.
1. Set all Audio devices to Disabled.
1. Set Mic/Auxilary Audio Device to VoiceMeeter Aux Output (VB-Audio VoiceMeeter AUX VAIO)

![OBS Audio Settings](/assets/images/audio-setup/obs_audio_settings.png)


### XSplit
1. Open XSplit
1. In XSplit, navigate to settings and then audio.
1. In Audio, set System Sounds to None.
1. In Audio, set Audio Preview to None.
1. In Audio, set Microphone to VoiceMeeter Aux Output (VB-Audio VoiceMeeter AUX VAIO).

![XSplit Audio Settings](/assets/images/audio-setup/xsplit_audio_settings.png)
