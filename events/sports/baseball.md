# OBS configuration 
3 sources need to be configured, they should already be present but here are the steps to configure each one, if issues arise
#### Scene 1 - Welcome screen
Requires only one source. Should be named `Welcome Screen`
- Image source - with latest graphic containing information about current game
- (optional) Add second audio source that can play background music before the stream starts
#### Scene 2 - Camera 1
Should be named `Camera - name of camera operator`
This will be very similar to source 3 and will contain the scoreboard overlay, NDI camera view, and both presenters audio split in 2 so each level can be adjusted separately. **The sources should be in the same order they are here** 
- *Media Source* - scoreboard
	- Source should be named `Scoreboard`
	- this is going to display the Scoreboard camera and should be adjusted to fill the top left corner of the screen. 
	- Create a source using media source and set the url to `this`
- *NDI Source* - camera 1
	- Source should be named `Camera 1`
	- This will display the actual game footage, 
	- under properties select NDI camera 1
- *NDI Source 2* - sportscaster channel 1
	- Source should be named `Sportcaster 1`
	- this will bring the audio from the macbook into OBS
	- The audio is split in two, one presenter is on the right channel and one presenter is on the left channel, if you simply use the source unmodified one person will be speaking into each ear of any headphone user.
	- Under Source properties:
		- select `SOUMM..` as the source
		- Change mode to audio only
		- Change timing to `not sure which` **this is very important failure to do this will result in stuttery audio**
	- Under advanced audio properties; Which can be accessed via the cogwheel in the audio mixer widget or by clicking on the 3 vertical dots underneath the audio meters.![[Screenshot 2025-03-06 at 8.05.52 AM.png]]
		- Check the box that says mono next to the audio source you created.
		- Drag the balance slider all the way to the left.
		- You can also change the audio monitoring from `Monitor Off` to `Monitor and output` to be able to monitor the audio from the sportscasters
- *NDI Source 3* - sportscaster channel 2
	- **for this we repeat most things from NDI Source 2**
	-  The source should be named `Sportcaster 2`
	- Under Source properties:
		- select `SOUMM..` as the source (should be the same source you selected last time)
		- Change mode to `audio only`
		- Change timing to `not sure which` **this is very important failure to do this will result in stuttery audio**
	- Under advanced audio properties:
		- Check the box that says mono next to the audio source you created.
		- Drag the balance slider all the way **to the right**. 
#### Scene 3 - Camera 2 
Should be named `Camera 2 - name of camera operator`
This scene is very similar to scene 2 so you can start by left clicking on scene 2 which should be named Camera 1 and pressing duplicate. 
- You will need to rename Camera 1 to Camera 2
- You will also need to enter the properties of Camera 2 and set the NDI source to camera 2.
# Production truck configuration
For reasons the software needed to stream the games does not work on windows, to work around this and still use OBS for our switching needs OBS is configured to output an NDI stream, and a mac mini running production truck detects the ndi stream and sends it to NHSS
**All the following steps are for the mac mini, not the streaming computer**
#### Instructions
- ensure the mac mini is on the right vlan, as it will not see the ndi sources if it is on a different vlan than the NDI cameras and streaming computer.
- Launch production truck and have Mr. Pizzo sign in using his account information.
- Press the cogwheel in production truck to go to settings or press `command + ,`
- Under settings click camera 1 - (this will be the only source we use in production truck as all our switching is happening in OBS on the Streaming Computer)
# If something breaks there may be info here to fix it

# things to fix
- [ ] ensure computer does not shut down
- [ ] ensure audio ducking and other tuning 
- [ ] make sure levels on MacBook are more even
- [ ] speakers for the streaming computer
- [ ] better naming convention camera name - name of operator
