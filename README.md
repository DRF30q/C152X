# MSFS C152X Realism Mod
V0.17.5
  

## Installation
Place the "C152X" folder in your community package folder.

The installation does not create a new aircraft selection in the simulator.  The modifications are applied to the Textron Aviation Cessna 152.  Once the package is installed in the community folder, selecting this aircraft in the sim should load the C152X Mod aircraft.   

Note that none of the base files for the default aircraft are directly modified in any way.  Removing the "C152X" folder from the community package folder should remove and deactivate the C152X Realism Mod.

### 0.17.5
Some issues were fixed:
- The yoke cannot be hidden
- Can't start the engine with the Logiteck multipanel
- RPM indicator no longer working
- ATC, ADF displays frequency are shown
- a target appears on the windshield

### 0.17
Some of the current improvements (not exhaustive):
- Modified stall speeds flap up/flap down in accordance with published information.  Aircraft will now stall at a significantly higher speed.
- Numerous changes to engine performance, now in accordance with Lycoming O-235L2C (115HP, 2700RPM) See note below.
- Fuel consumption adjusted.
- Long Range Fuel Tanks 37.5USG total useable. See note below.
- Fuel Gauges correctly calibrated.
- Fuel Gauge indications will vary realistically in out of balance flight (depending on quantity of fuel in tank) and also on the ground when the aircraft is not wings level.
- Flight tested to verify climb, cruise, service ceiling, fuel consumption etc in accordance with published information.
- Oil Temperature Gauge - gauge calibration and oil temperature modelling adjusted.
- Oil Pressure Gauge - gauge calibration and oil pressure modelling adjusted.
- Electrical system - completely remodelled, using documented electrical loads etc.
- Now models realistic battery discharge/charge and subsequent electrical system behaviour. 
- If battery goes flat, various systems will fail at various voltage levels as the battery discharges.
- Ammeter - gauge calibration and behaviour.
- Low voltage light now comes on below ~ 1000 RPM as in real life.
- OAT thermometer now operates regardless of the position of the master switch.
- The overhead (Dome) light can now be dimmed by the dimmer knob below the pilot control yoke.
- The NAV CDI gauges completely revised:
- CDI gauges now respond correctly to: User selected On/Off state of corresponding NAV/COM Radio.
- CDI gauges now respond correctly to:	Power state of corresponding NAV/COM Radio.	
- CDI gauges now power off when Avionics Power (Battery Master Switch) switched off.
- CDI gauges now power off when the applicable NAV/COM Radio is turned off using the Volume/Off knob.
- CDI gauges now power off if the battery discharges and the voltage level supplied to the applicable	
	NAV/COM radio drops below the minimum required for operation.
- CDI gauges, Glideslope/Localiser Needle behaviour adjusted.
- CDI gauges, Glideslope/Localiser Flag behaviour adjusted.
- CDI gauges, NAV Flag behaviour adjusted.
- ADF Radio completely revised Knob behaviour. ADF Modes: BFO/REC/ADF and spring return TEST position.
- ADF Rotatable Card gauge behaviour completely revised:
- ADF Needle is driven to point to the selected NDB station only in ADF Mode. (Note that currently the ADF Mode Knob defaults to BFO Mode and must be manually rotated to ADF Mode.)
- ADF Needle remains in current position in ADF Mode when no signal received from an NDB on the currently selected frequency.
- ADF Needle remains in current position in BFO and REC Modes.
- ADF Needle is slewed in a clockwise direction while ADF Mode Knob held in TEST position.  When released, the ADF Mode Knob spring returns to ADF Mode.
- ADF Needle remains in current position when ADF Radio is turned off using the Volume/Off knob.
- ADF Needle remains in current position if battery discharges and voltage level to the radio drops below the minimum required for operation.
- ADF Volume and ADF Mode Knob position state now loaded from .flt files.  ADF Mode knob defaults to 'ADF' position.
- NAVCOM (KX155) reworked.  Various states including volume/Off state etc now loaded from .flt files.
- NAV Ident / COM Test remain out when pulled.  
- Audio Selector (KA134) completely revised.  Various states now loaded from .flt files.
- Buttons now remain depressed when selected.  
- MIC1/MIC2 selects either COM1 or COM2 as active transmitter.
- BOTH allows selection of reception on both COM1 and COM2.
- NAV1, NAV2, ADF (AOE wtf?) etc select ident audio.
- MKR selects Marker ident audio.  Note:  My testing so far indicates audio received (and light flashes) from Middle Marker, however Outer Marker light flashes but no audio heard.  Not sure if this is a sim issue.
- DME, SPKR buttons now operate but are currently non functional.

### Notes:  
 - The default aircraft panel has a Tachometer with a 2700RPM redline.  As a result I have taken the decision to model the C152 with the corresponding and slightly uprated 115HP engine.  (It is essentially the same engine as the 'standard' C152 Lycoming engine with 110HP/2550RPM redline, with a few extra horsepower gained from the additional RPM.  The standard performance charts eg cruise power settings etc will still be valid. The extra horsepower means slightly better takeoff and go-around performance and a slightly higher service ceiling.  The current version tested in the sim has a service ceiling around 15,500ft.)
 - The default aircraft panel depicted fuel gauges for Long Range Tanks (37.5USG) but the sim data was for Short Range Tanks (24.5USG useable). Again I have taken the decision to model the Long Range Tanks.  This now gives the aircraft a nearly 9 hour endurance and a range of up to 670 nm.  This makes the aircraft much more capable of long range flights in the sim, and I think much more useful.  (Round the world type flight capability. :))
- I have not tested this Mod in any of the activities, lessons etc that may utilise the default aircraft. I can't guarantee that it will not cause issues in some of these situations.  Use at your own risk. :)   

## Changelog
[0.11] - 2020-09-04
Initial release.

[0.12] - 2020-09-05
Corrected situation with no avionics power in certain startup situations.

[0.14] - 2020-09-10
Navigation CDI gauges completely revised.

[0.15] - 2020-09-14
Aircraft name reverted to default.  Flight Training lessons now selectable. 
Navigation ADF Radio and associated gauge completely revised.

[0.16] - 2020-09-19
ADF/NAVCOM/Audio Selection Panel completely revised.  Various states now loaded with .flt files. 

[0.17] - 2020-10-14
Corrected manifest.json
 
## Donation

If you enjoy the mod and would like to show your appreciation, a donation would great :).

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=WLG9J2FFWNH7Y&currency_code=USD)
