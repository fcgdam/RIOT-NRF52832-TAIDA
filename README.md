# RIOT Taida Century NRF52832 

This is the RIOT-OS board definition for the Taida Century NRF52832 board that can be bought on sites like eBay, Aliexpress and so on.

# How to use

Copy the nrf52-taida folder and subfolders to the boards subdirectory of the RIOT-OS instalation.
Change on the makefile the board definition to:

 BOARD ?= nrf52-taida

For example, just go to examples/nimble-gatt, and on the makefile just change the board to *nrf52-taida*.
Compile, flash and it should work right away.
