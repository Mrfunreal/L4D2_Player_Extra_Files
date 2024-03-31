These sets of mdl and ani files are to be used as includemodel for biker, biker_light, manager, and teenangst_light.

All player models have a set of includemodels for animations, gestures and postures, except for biker, biker_light, manager, and teenangst_light.
these four have loose animations inside themselves that need to be recompiled into the model by yourself, which is a bit of a hassle.
So, with this setup you no longer need to compile anims by yourself.
Instead, just use these includemodel mdl files. (!don't forget to ship them with your mod!)


Instructions:
	1. 	Delete EVERYTHING below $IKAutoPlayLock "lfoot" 1 0.1. (Unless you already have the proportiontrick setup. Thenjust delete all existing includemodels)
	2. 	Add the following line instead:	
	For Biker:				$IncludeModel "survivors/Anim_Biker_New.mdl"   
	For Manager:			$IncludeModel "survivors/Anim_Manager_New.mdl" 
	For Biker_light:		$IncludeModel "survivors/Anim_Biker_Light.mdl"  
	For Teenangst_Light:	$IncludeModel "survivors/Anim_Teenangst_Light.mdl"  
	3.	Add the proportion trick stuff underneath this new $includemodel.
	4. For Biker_light and Teenangst_Light, use thei francis_LIGHT and zoey_LIGHT declaresequence.qci aswell.



