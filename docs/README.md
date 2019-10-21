# <p align="bottom"><img height="50" width="50" src="https://github.com/tuxd3v/pwm_driver/blob/master/docs/fan.svg" /> | Pwm Hardware Driver..</p>
---
Pwm Driver to drive a fan

It could be used in any board, with supply power header pins, and a Control pin for pwm signal..
The board files are in file 'FAN5V-PWM_CTL.zip'


#### Table of contents
* [Characteristics](#characteristics)
* [Requirements](#requirements)
* [Observations](#observations)
* [Donations](#donations)
* [Credits](#credits)

### Characteristics:
----
#####  PWM Driver:

![Front Pcb:](https://github.com/tuxd3v/pwm_driver/blob/master/docs/f-cu.png)
![Back Pcb:](https://github.com/tuxd3v/pwm_driver/blob/master/docs/b-cu.png)

##### Explanation:
    
```lua
   A pwm pin, from your SBC, will controll, the pulses emited to the driver,
   Wich in turn, will make the fan be driven faster or slower, depending on the duty cycle..
   It will be used with ATS, to control the fan..
```

## Requirements:
----
* Any SBC capable to offer the voltage or current required by the fan..
* 1N4001 Diode
* STT6N3LLH6 N-MOSFET
* 1x3 2.54mm Male pin Header
* 1x2 2.54mm Male pin Header

## Observations:
----
This Board have been produced with the help of Kicad Software.
You can find kicad Documentation in docs/kicad.pdf

### Donations
----
This project, is been made availlable by me, has a way to have a active cooling tool, for Our SBCs..

If you want to help this project, consider a donation..
```lua
 - Magi Address    : 96H3wSX8e5sqJ1tHpXjhJrppKhsLQEWFMz
 - Monero Address  : 47gzrS7JU5E7tUF9YcdgXw68DhbJokuHTWKSr42LcmU4RTFFvCoU8W7NDjauef5kGQY5WRZXfoVWENutt3afKv9YDufEgJx
 - AEON Address    : WmtL2wph84vb5inWpMoXFucwBmDtF4BsLLjWvP4LEd435tvjpfcUTjegSXKnrT3FjATzo8X8ouSwVArooxmauniP2TLKCXQdc
 - VertCoin Address: vtc1qmck0q88enwneha75cpfcys6eyst4rnsr8h2uk8
 - Ryo Address     : RYoKsxn7kT4DZVagVtmTuT5wwvrQ2f38pJ8AcE2jcUyogcNVFZ2syeN
 - BitCoin Address : 1GuBhkustzsCLUbFhRLcppp9Pf4KW9TxXQ
 - Ethereum Address: d468db56e89c883C4046D50A2261D5CE4dF4eFCD
```
### Credits
----
pwm_driver      : tuxd3v

Boards Images	: tuxd3v

Fan Icon	: `[ freepik ] | https://www.flaticon.com/authors/freepik`
