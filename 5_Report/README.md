# M3_Wiper_Control_System

## About the project WCS

## Abstract
This project is about Wiper_Control_System. The wipers are a small part of your car, but they have a big impact on your driving and overall safety. They remove rain, snow, dirt, pollen, frost and other debris quickly and smoothly at the push of a button! The windshield wiper motor moves the windshield wiper arms across the windshield. 
If there are no wipers, of course, the rainwater that wets the glass will condense and the condition of the glass will become unclear. Not only that, dirt that sticks to the windshield for a long time, of course, is very difficult to remove. If left untreated, of course, will hinder the driver’s view and create a high risk of driving accident. 
A wiper control system for an automotive wiper controls the operational speed of a wiper in accordance with rain conditions.It useful in the automotive unit the main purpose of the system is to clean the windscreen sufficiently to provide suitable visibility at all times.


## Introduction
The project is about Wiper_Control_System. The wipers are a small part of your car, but they have a big impact on your driving and overall safety. They remove rain, snow, dirt, pollen, frost and other debris quickly and smoothly at the push of a button! The windshield wiper motor moves the windshield wiper arms across the windshield.

The three main types of wiper blades are: conventional, flat and hybrid. If your car came with conventional windscreen wipers, they can be replaced with flat or hybrid wipers for a performance and visual upgrade.

Wiper system works When the wiper switch is in the off position, the wiper will not function. When the wiper switch is in low-speed mode, the wiper will work at low speed. Accordingly, when the wiper switch is in high-speed mode, the wiper will work at a fairly high speed.

## Used Components
* STM32 (32-bit microcontroller)
* 4 LED'S
* One Switch
* Required Software

## | Identifying features |

* When the button is pressed once the car will start (Ignition key postion at ACC)
* When the button is pressed again the wiper will start(Wiper On)
* When the button is pressed again the wiper will off(Wiper Off)
* When the button is pressed thrice the car will stop(Ignition key position at Lock)

## | 4W's & 1H |
# What
 * Wiper control system.
# Where 
* Inside and out side the car.
# When
* When the weather condition is bad (like in rain and snow) the wiper is activate and clean the car window.
# Who
* Driver or who is controlling the car.

# How
* By using STM32 microcontroller.

## | S.W.O.T ANALYSIS |

 # Strengths

* No human interaction with car

* Manages all commands with one key automatically

# Weakness
* Encryption in data Weaknesses

* Unable to monitor status of car

* Range is limited
# Opportunities
* Wait for certain time after every command to press new command Opportunities

* The Scope of this sytem is huge in car control

* Can be used where the car need thesed command
# Threats
* Less cost Threats

* When new command is given without completing the current command it will not take current command

## Folder Structure
Folder             | Description
-------------------| -----------------------------------------
`0_Abstract`       | About Project
`1_Requirements`   | Documents containing requirements 
`2_Design`         | Documents specifying design details of circuit
`3_Implementation` | All required codes and documentation
`4_TestCases`      | low and High level Requirements
`5_Report`         | Report all the details about project
`6_Output`         | Documents with Images

## Learning Platforms
* Youtube
* Future skills


## | Requirements |
## High Level Requirements
| ID | Description | Status |
|------| ------| ------|
|`HLR1`  |	It will start the car | Implemented
|`HLR2`  |	It will start the wiper | Implemented
|`HLR3`  |	It shall seen speed of the wiper work | Implemented
|`HLR4`  |	It will stop the wiper | Implemented
|`HLR5`  |	It will stop the car | Implemented

## Low Level Requirements
| ID | Description | Status |
|---| ------| ------|
|`LLR1` | If the User button is pressed Once, the red LED will be on| Implemented
|`LLR2` | If the User Button is pressed TWICE, Blue,Green,Orange LED's come ON at a time with set of frequency| Implemented
|`LLR3` | If the User Button is pressed THIRD time, ON All LED's in CLOCKWISE manner an speeed will increase| Implemented
|`LLR4` | If the User Button is pressed FOURTH time ,all LED's on anticlock manner| Implemented
|`LLR5` | If the User Button is pressed FIVTH times, the red LED will be off| Implemented


## OFF CONDITION
![STM32 OFF Condition](https://user-images.githubusercontent.com/101381519/168338545-303ec50f-63db-457d-a587-724cbac0e37d.jpeg)

## ON CONDITION
![RED LED ON](https://user-images.githubusercontent.com/101381519/168338650-2d96a74f-bcfe-4699-8d87-8c16ada8d0fe.jpeg)

![ORANGE LED ON](https://user-images.githubusercontent.com/101381519/168338697-8ba871f4-bd03-4c0e-95fb-702af330315e.jpeg)

![GREEN LED ON](https://user-images.githubusercontent.com/101381519/168338738-8b783453-aec8-4d35-9141-fa657c843250.jpeg)

![RED LED ON](https://user-images.githubusercontent.com/101381519/168338777-6d135300-dc4c-4858-8e84-d89fb3fda69b.jpeg)


