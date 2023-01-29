# Physiology-based_Model


|- [File] PM_tester.exe:	PM execution file. You should add your vibration set with '.txt' format into "./Vibration" before running this file.
				As a result of the running, a predicted perceptual dissimilarity matrix, 'PM_Prediction.txt', will be generated.
				
	|- [Folder] Vibration	:	A vibration set for the test. For testing, we provide 8 vibration patterns.
				1. All vibrations that you want to predict must be in the path of "./Vibration".
				2. All vibrations' sampling rate must be 10kHz
				3. All vibrations' durations in the vibration pattern set must be the same. If they are different, please apply zero-padding to shorter patterns.
