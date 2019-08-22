# OpenServo
Open source servo with feedback using arduinos and modified standard servos

Current Main Developers:
- Richard
- James

Currently in early phases with basic hardware testing

The project hopes to develop a useful way for people to modifiy standard off-the-shelf servo motors to give feedback on their position in a useful way.

The project hopes to use a programmable logic controller to read the position of a servo directly from the internal electronics: either the error signal from the comparitor. or the analogue voltage from the potentiometer.

Current microcontrollers being investigated are PIC chips, arduinos and raspberry pis

Future goals for the project are to allow a small arduino or PIC chip to allow easy access to the position of many motors via i2c/spi/uart/other serial from another device for async control and state management that is not sensitive to power loss
