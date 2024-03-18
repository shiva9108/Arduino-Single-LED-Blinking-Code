# Arduino-Single-LED-Blinking-Code


This Arduino project demonstrates the basic functionality of blinking a single LED using the Arduino IDE. The LED blinks on and off in intervals of three seconds.

## Installation

1. Clone this repository to your local machine using `git clone https://github.com/shivaganesht/Arduino-Single-LED-Blinking-Code.git`
2. Open the project in the Arduino IDE.

## Usage

1. Connect your Arduino board to your computer.
2. Upload the code to your Arduino board.
3. The LED connected to the built-in pin on the Arduino board will start blinking at intervals of three seconds.

## Code Overview

```cpp
void setup()
{
    pinMode(LED_BUILTIN, OUTPUT); // Set the built-in LED pin as an output
}

void loop()
{
    digitalWrite(LED_BUILTIN, HIGH); // Turn the LED on
    delay(3000); // Wait for three seconds
    digitalWrite(LED_BUILTIN, LOW); // Turn the LED off
    delay(3000); // Wait for three seconds
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
