# Adaptive UI using Size Classes




For big screens, in storyboard:


- Select an iPad view, then click 'Vary for Traits' button, select both width and height. 

- Change the font trait of title label: 
			Click '+' beside 'Font' and set a larger font for 'wR hR'.
			
- Change the constraint value of title label:
			Select the required constraint
			Click '+' beside 'Constant' and set a larger value for 'wR hR'.
			
- Add a new label as subtitle, since the option 'Vary for Traits' is selected for regular width and height,
	this will not appear on screens with compact width and height.
	
- Display different image from the one for compact size:	
			In 'Assets' folder, select the image set and show its 'Attributes inspector'.
			Add two devices: (iPad and iPhone).
