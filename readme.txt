The directory should contain two executable files and some audio files: analyzeVoice.exe, output_excel.exe, and the wav audio file.
Enter the path of analyzeVoice through the command line.
Use this program in the command line and pass in the file (in wav format) that needs to be processed.

Usage:       <analyzeVoice.exe> <test.wav>
	 <output_excel.exe> <test>

After running, a directory with the same name as the input file (without the file extension, for example, if the input is test.wav, a directory named test will be created in the current directory to store the output results) will be created in the current directory, and a txt result file will be obtained.
The output_excel.exe performs statistical calculations on the content of the txt file and outputs an excle file.

