Readme file for DS1307RTC Library

The DS1307RTC library is provided to demonstrate the Arduino Time library.

See the TimeRTC example sketches privided with the Time library download for usage

Some parts (including the Due. tnhe tinyAVR 0/1/2-series, megaAVR 0-series. amd AVR Dx=series (all recently AVRs amd all that will be released going forward) have a peripeheral defined in the io headers called RTc. 

Previously, these would be #umndefined, but that prevemnted functionality of the internal RTC from being used. Mopw. if RTC is defined, we instead call the DS1307RTC object we create `EXT_RTC`. 
