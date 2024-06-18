# LED Diagnostics

## 5VL and 3.3V lit, 5V off

### Possible Cause
USB 5V Jumper in place and more than 200mA consumption on the 5V rail.

### Explanation
When powering the board via USB (=the 5V USB jumper is in place), you cannot draw more than 200mA from the
5V rail. You should only set the 5V USB jumper if you intend to initially flash the board - once you have flashed
Klipper or Katapult, you should use the respective run-time flashing methods. See [Flashing](flashing.md)

### Solutions

Either perform an [initial flash](flashing.md#initial-flash) or

1. Power off the board
2. Unplug the USB 5V Jumper
3. Perform the [update flash](flashing.md#update-flash)

