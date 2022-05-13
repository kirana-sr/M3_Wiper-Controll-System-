# Test Cases 01
|Test_ID|Desciption|Status of switch|Actual O/P|Exp O/P|Type of Test|
|:--:|:--:|:--:|:--:|:--:|:--:|
|TST_1|Ignition key At ACC| User button is pressed & held 2 sec|The Red LED is ON|The Red LED is ON|Requirements Based|
|TST_2|Wiper ON|User button pressed|Blue,Green,And Orange led is ON|Blue,Green,And Orange led is ON|Requirements Based|
|TST_3|Wiper OFF|user button pressed|Blue,Green,And Orange led is OFF|Blue,Green,And Orange led is OFF|Requirements Based|
|TST_4|Ignition key At ACC|User button is pressed & held 2 sec |The Red LED is OFF|The Red LED is OFF|Requirements Based|

# Low Level Test Cases
|Test ID|	Description|	Exp.i/p|	Exp.o/p|	Actual o/p|	STATUS|
|:--:|:--:|:--:|:--:|:--:|:--:|
|TST_1|	check if the BUTTTON is pressed|	program execution|	MicrocontrollerEngine starts	LED ON(RED)	PASS|
|TST_2|	check if the BUTTTON is pressed again	|program execution|	WIPER starts and speed of wiper is slow	LED ON(BLUE)	PASS|
|TST_3|	check if the BUTTTON is pressed again	|program execution	|WIPER starts and speed of wiper is moderate	LED ON(GREEN)	PASS|
|TST_4|	check if the BUTTTON is pressed again	|program execution	|WIPER starts and speed of wiper is good	LED ON(ORANGE)	PASS|
|TST_5|	check if the BUTTTON is pressed again|	-	Microcontroller|Engine stops	LED TURNED OFF	PASS|
