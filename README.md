# Marlin-DBot Configuration

Configuration files for my D-Bot CoreXY printer. Use with caution as my setup may be different to yours. Things to pay attention to are stepper configuration, thermal PID settings, axis and end-stop directions.

Enables a number of optional features including:
 * BLTouch probe and bi-linear auto bed-levelling
 * S-Curve acceleration 
 * Linear Advance
 * Babystepping (aka Z-probe height adjustment)
 * RepRapDiscount Full Graphic LCD display
 * Cancel objects

Confirmed working for Marlin `2.0.x`, specifically `2.0.5.3`

You need to take these files and copy (link) them into the `Marlin` sub-directory of the Marlin firmware repo. These files replace the existing `.h` files in that directory. If you are interested in my modifications use your favourite git diff tool to see what I have changed.

