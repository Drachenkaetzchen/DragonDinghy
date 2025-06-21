# Getting Started

## Board Overview

<figure class="inline end" markdown="span">
  ![Board Diagram](images/Board%20Diagram.png){style="border: 2px solid black;"}
  <figcaption>Board Overview</figcaption>
</figure>

It's a good idea to familiarize yourself with the board layout before continuing. Here's an overview diagram:




## Operation Modes

You can operate the board via USB, CAN or as CAN Bridge, depending on your requirements.

=== "USB"
    The "classic" mode of operation. Requires an USB cable as well as 24V and GND connections. Typical usage scenarios:

    * Board is operated in your electronics bay
    * You don't have a CAN setup

=== "CAN"
    Operation within a CAN network. Requires a CAN interface. Typical usage scenarios:

    * Board is operated outside of your electronics bay
    * You already have a CAN setup

=== "CAN Bridge"
    Operation as a CAN Bridge.  

    * Board is operated inside of your electronics bay
    * You want to save a dedicated CAN interface