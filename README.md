SNARC_PTH_V1.3
==============

Please see https://github.com/LemElec/SNARC_Demo_Code for the demo firmware and software

The SNARC is a board developed by me, Lawrence “Lemming” Dixon, originally for HSBNE but now I am offering it to other people or groups who are interested in a cheap and easy to implement RFID based access control system.

A SNARC can be used for driving door strikes or mag plates directly for doing access control to a building or room, or it can be used with relays/contactors/magnetic e-stops to control access to machines.

The SNARC is designed to be as simple as possible to implement, but also as flexible as possible. It uses an ATMega 328p microcontroller hooked to a Wiznet wiz820io Ethernet module. All the pins of the ATMega are either used on-board for various functions or broken out to various headers around the board. Functionally the board is very similar to an Arduino, it can be used for a basic locally authenticated RFID system, or it can be a fully networked access control system with other sensors attached to the board for data logging or environmental monitoring. The board is also quite small at 40mm x 65mm (some components overhang the edges slightly) Approximate height of the board is about 25mm to the top of the tallest component.

Copyright 2013 Lawrence "Lemming" Dixon. Copyright and related rights are licensed under the Solderpad Hardware License, Version 0.51 (the “License”); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://solderpad.org/licenses/SHL-0.51. Unless required by applicable law or agreed to in writing, software, hardware and materials distributed under this License is distributed on an “AS IS” BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.


