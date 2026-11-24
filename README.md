
[Rainmeter]
Update=1000
AccurateText=1
DynamicWindowSize=1
BackgroundMode=2
SolidColor=20,25,40,230

[Variables]
Font=Segoe UI
Color=255,255,255

[MeasureDhaka]
Measure=Time
TimeZone=6

[MeasureNewYork]
Measure=Time
TimeZone=-5

[MeasureSanJuan]
Measure=Time
TimeZone=-4

[MeterTitle]
Meter=String
Text= WORLD CLOCK
FontFace=#Font#
FontSize=20
FontColor=80,200,255
X=20
Y=15

[MeterDhaka]
Meter=String
MeasureName=MeasureDhaka
Text=Bangladesh - %H:%M:%S
FontFace=#Font#
FontSize=16
FontColor=#Color#
X=20
Y=65
TimeZone=+6

[MeterNewYork]
Meter=String
MeasureName=MeasureNewYork
Text=New York - %H:%M:%S
FontFace=#Font#
FontSize=16
FontColor=#Color#
X=20
Y=105

[MeterSanJuan]
Meter=String
MeasureName=MeasureSanJuan
Text=San Juan - %H:%M:%S
FontFace=#Font#
FontSize=16
FontColor=#Color#
X=20
Y=145
