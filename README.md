Coding Check
1.	In int brightnessSetting = 75; identify the data type, variable name, and initial value. How would you change the value to 50? data type is int, variable name is brightnessSetting, initial value is 75. To change it to 50, just write brightnessSetting = 50;
2.	Why is bool suitable for switchOn, while int is suitable for brightnessSetting? switchOn only has two state true/false, while brightnessSetting has value of integer.
3.	Predict the output when brightnessSetting is 80 and switchOn is false. brightnessSetting = 80, lampBrightness = 0;
4.	Are switchOn and switchon the same variable? Explain. No. C++ is case-sensitive, so switchOn and switchon are different variable.
5.	What values are passed to getLampBrightness(), and what does it return? the current values of switchOn and brightnessSetting are passed in as arguments, and it return int = 0;
6.	If lampBrightness is declared inside setup(), can loop() access it directly? Explain. No. Variables declared inside a function are local to that function's scope; loop() cannot see or use lampBrightness unless it's declared outside both functions or passed some other way.


Laboratory Activity: Control a Lamp’s Brightness
