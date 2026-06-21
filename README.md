# The Zumo 2040 Challenge!
## Overview
This challenge is meant as a quick low friction way to enter the world of Mini Sumo:
* Utilizes an existing Mini Sumo robot kit.
* No need to design the mechanical or electronic portions of the robot.
* Concentrate on Mini Sumo strategies, algorithms, and code instead.

## The Challenge Robot
![Zumo 2040 Robot](pololu-zumo-2040.png)

The [Pololu Zumo 2040 Robot](https://www.pololu.com/category/308/zumo-2040-robot) will be used for this challenge. Either of the following versions can be used by contestants. The one to use will depend on whether the contestant wants to build the bot themselves or not:
* **Kit Version**
  * 1 x [Zumo 2040 Robot Kit (No Motors)](https://www.pololu.com/product/5010)
  * 2 x [75:1 Micro Metal Gearmotor HP 6V with Extended Motor Shaft](https://www.pololu.com/product/2215)
* **Preassembled Version**
  * 1 x [Zumo 2040 Robot (Assembled with 75:1 HP Motors)](https://www.pololu.com/product/5012)

## The Challenge Rules
* Adhere to the **Autonomous 500g Mini Sumo** variant of the [SRS Sumo Rules](https://robothon.org/rules-sumo/).
* Use a [Pololu Zumo 2040 Robot](https://www.pololu.com/category/308/zumo-2040-robot) as outlined in the [the-challenge-robot section](#the-challenge-robot).
* If you build the [Zumo 2040 Robot Kit](https://www.pololu.com/product/5010) then you must install the **Clear Wide Angle IR LEDs** in **Step 27** of the [Zumo Assembly Instructions](https://www.pololu.com/docs/0J87/all#3). This matches the LEDs used in the [Zumo 2040 Robot (Assembled with 75:1 HP Motors)](https://www.pololu.com/product/5012).
* No changes to the stock **Zumo 2040 Robot** are currently permitted.
  * No mechanical modifications or additions allowed.
  * No electronic modifications or additions allowed.
* It is however acceptable to install headers on the mainboard to allow for debugging and future expansion when soldering other headers to the mainboard for a kit built Zumo.
* Challengers are **encouraged** to **modify/improve/replace** the **software** provided by Pololu as much as possible!!
* Contestants are free to choose between Alkaline and NiMH batteries for their bots during competition runs.

## The Challenge Goals
* Increase interest in Mini Sumo.
* Increase the number of contestants in the [Robothon & More](https://robothon.org/summer-2026-robothon-event/) event on **August 22nd, 2026** in the **Capital Hill** region of Seattle, WA. For that event the Challenge bots will compete against Mini Sumo bots which aren't restricted by the additional rules of this challenge.
* Present a path for at least one of the contestants to get into the design of their own custom Mini Sumo robots that would be competitive in existing Mini Sumo contests such as at the SRS Robothon events.
## Related Links
* [Pololu Zumo 2040 User's Guide](https://www.pololu.com/docs/0J87/all)
* [Pololu Zumo 2040 C/MicroPython Libraries](https://github.com/pololu/zumo-2040-robot)
* [3π+ 2040 Arduino Library](https://github.com/adamgreen/pololu-3pi-plus-2040-arduino-library) - Mostly compatible with Zumo 2040
* [SRS Sumo Rules](https://robothon.org/rules-sumo/)

## Future Challenge Possibilities
* Could allow for remote robot competitions:
  * Contestants would submit their custom **.uf2** firmware images to event organizers.
  * Each firmware image submitted would be turned into 2 contestants, one to run on each of 2 physical robots.
  * These 2 contestant versions would be used in an attempt to reduce the influence of one physical robot on the final winner since each submitted firmware gets to compete on both physical robots.
  * To obtain unique 1st, 2nd, and 3rd place finishers, only a submissions's best result would be kept and the other discarded.
* Contest organizers could relax restrictions on electronic changes in the future to allow for additional sensors and/or different mainboards but the mechanical components would still be required to remain stock.
