# ESP8266_SpaceInvaders

/*
 * Modified by Billy Cheung to convert to button controlled instead of joystick controlled.
 * 2019 Jul 31
 /*
 Pins for buttons
 
GPIO13  D7——   Rightbutton-----  .GND
GPIO12  D6——   Left button-----  .GND
GPIO14  D5——   UP   button-----  .GND
GPIO2   D4——   Down button-----  .GND
Reset   ------Reset button----=  .GND
GPIO0   D3——   A    button-----  .GND

GPIO15  D8——Piezo Speaker/headphone--GND

 8266        i2c SSD1306 Oled
=============================
3.3V        -----VCC
GND         -----GND
GPIO5    D1 -----SCL
GPIO4    D2—-----SDA

Libraries used:
https://github.com/ThingPulse/esp8266-oled-ssd1306   version 4.0.0

 ssd1306xled Library for SSD1306 oled display 128x64


 */

*
 * >>>>>  T-I-N-Y  S-P-A-C-E   I-N-V-A-D-E-R-S for ESP8266   GPL v3 <<<<
 *                   This version by Tobozo https://github/com/tobozo
 *                   New display library + logic refactoring (still in progress)
 *
 * Original version:
 *
 * >>>>>  T-I-N-Y  S-P-A-C-E   I-N-V-A-D-E-R-S for ATTINY85  GPL v3 <<<<
 *                   Programmer: Daniel Champagne 2018
 *                   Contact EMAIL: phoenixbozo@gmail.com
 *            https://sites.google.com/view/arduino-collection
 *
 *  Tiny Space Invaders is free software: you can redistribute it and/or modify
 *  it under the terms of the GNU General Public License as published by
 *  the Free Software Foundation, either version 3 of the License, or
 *  (at your option) any later version.
 * 
 *  This program is distributed in the hope that it will be useful,
 *  but WITHOUT ANY WARRANTY; without even the implied warranty of
 *  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 *  GNU General Public License for more details.
 *  
 *  You should have received a copy of the GNU General Public License
 *  along with this program.  If not, see <http://www.gnu.org/licenses/>.
 *
 */
