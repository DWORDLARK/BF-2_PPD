----------------------------------------------------------------------------------------
	BF2_ppd  (Player position display)
----------------------------------------------------------------------------------------

	BF2_ppd can display players location X,Y,Z.
		
	Display order is same as location values in BF2 files.
		
	Additional text field combines location values separated with "/" for easy copy.

	Location info is read from BF2 game process memory !
	BF2 game must be running and Player must be in mission for 
	location info display and for use of copy / save functions.
	
	***BF2_ppd can detect if BF2.exe is running, BF2_ppd 
	can be started before BF2 game or after. 



----------------------------------------------------------------------------------------
	Buttons:
----------------------------------------------------------------------------------------
	
	Copy:  	Copy location info from additional text field into clipboard.

	Save:  	Manual Save for location info from additional text field into file.
		
		File name format: BF2_ppd_Pos_(mission folder name).txt  
		Example: "BF2_ppd_Pos_(Highway_Tampa).txt"
		



----------------------------------------------------------------------------------------
	Hotkey (Save):
----------------------------------------------------------------------------------------
	
	Keyboard shortcut for Save function:  Ctrl+S
		***File "Save1.wav" is used to indicate Save function.
		User can re-name, delete or move   this file to disable this option.
		Or replace it with other wav file to use different sound.



----------------------------------------------------------------------------------------
	bf2_ppd_Settings.ini:
----------------------------------------------------------------------------------------

	[Application]

	Form_X	Position on screen, saved on exit
	Form_Y	Position on screen, saved on exit

	OnTop=0    if set to 1, program window is forced as top window.
		Useful for copy-paste location data into game script files.
		OnTop=1 will not force BF2_ppd program window on top of fullscreen game window !
	GameType=1	1 or 2	User must select Game type,  1=BattleField2,  2=ForgottenHope2

	User can set up three shortcuts to start BF2 game (with optional parameters).

	[Start_Game_set_1]
	execMenuName_1=		Optional name to display in Menu.
	GamePath_1=		BF2.exe install dir (without BF2.exe)     Example: C:\Battlefield 2
	execParams_1=		Optional parameters

	[Start_Game_set_2]
	execMenuName_2=
	GamePath_2=
	execParams_2=

	[Start_Game_set_3]
	execMenuName_3=
	GamePath_3=
	execParams_3=



	***Set_1 filled with valid data to show as example:


	[Start_Game_set_1]

	execMenuName_1=BF2 Special Forces

	GamePath_1=C:\Battlefield 2

	execParams_1= +menu 1 +fullscreen 1 +modPath mods/xpack +ignoreAsserts 1



----------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------
	Date:
	08.05.2024
----------------------------------------------------------------------------------------



















































	And remember !	  If you see a crocodile dont forget to scream !

