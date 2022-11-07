# DS1220-replacement-PCB
Replaces a Dallas / Maxim DS1220 but without the need of a coin cell battery

This is a replacement for the Dallas DS1220 non-volatile NVRAM used in many early 90s devices.
The battery in those eventually goes bad and the memory content will become corrupt or even lost.
The result is a very expensive but non working unit.

I did many repairs of old HP 546xx series oscilloscopes and they all have those Dallas NVRAM ICs soldered onto the mainboard.
First I replaced those with the 1:1 part of Maxim but they also have a battery bult in.
I wanted to design a solution without the need of a coun cell battery.

Pictures are from the repair of my ancient HP 54601A oscilloscope.

Replaces the original Dallas DS1220 NVRAM but without the need of a coin cell battery.
The use of a F-RAM FM16W08 makes it possible.
The power supply of the F-RAM can go up to 5.5V and makes it 100% TTL compatible without the need of additional level shifters.
According to the datasheet the FM16W08 has a 151 year data retention.

No liability is assumed for damage to devices or persons.
Desoldering the original Dallas IC is no problem for the specialist.
The hobbyist should be equipped with good tools and know what he is doing.
Otherwise ask someone to help.
