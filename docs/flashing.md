# Introduction

To make your new board work, you need to put the MCU firmware onto the board.

??? info "What is an MCU?"

    MCU stands for "Microcontroller Unit" and is the processor on each board. Usually boards connected to Klipper are
    called "MCU boards", but often it's abbreviated as "mcu". So whenever you read "MCU", it can either mean the whole
    board or the processor itself, depending on the context.

??? info "Klipper vs. Klippy confusion"
    Klipper consists of 2 parts:

     - The host code, also known as "klippy", runs on a Linux computer like a Raspberry Pi, Banana Pi, any other
       single-board computer or even an old laptop - typically referred to as "host". This part is responsible for
       managing all connected boards, calculating movements as well as interpreting G-code commands and translating them
       into syncronized movements for all connected boards.
     - The klipper firmware, which runs on the MCU. It communicates with klippy on the host, receives it's commands and
       executes them at the exact time required.
         
# Flashing Preparations

# Initial Flash

# Update Flash

# After the flash

1. Power off the board
2. Unplug the USB 5V Jumper
3. Plug in any devices you have unplugged
4. Power on the board