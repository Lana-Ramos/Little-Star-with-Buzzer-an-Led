Twinkle, Twinkle, Little Star - Arduino Project

This Arduino project plays the melody of "Twinkle, Twinkle, Little Star" using a buzzer and LEDs. Each note in the song is associated with a specific LED that lights up when the 
corresponding note is played. This project demonstrates how to combine light and sound in a synchronized show using basic Arduino components.

Components Needed

- Arduino board (e.g., Uno, Nano)
- 6 LEDs
- 6 220Ω resistors
- Buzzer
- 6 jumper wires
- Breadboard
- Arduino IDE

Circuit Diagram

1. Connect each LED to a digital pin on the Arduino (e.g., pins 11, 10, 9, 8, 7, 6).
2. Connect the buzzer to pin 4.
3. Use 220Ω resistors for each LED to limit current and protect the LEDs.
4. Ensure each LED is properly grounded through the Arduino GND pin.

Code Explanation

- LED Control: Each LED is mapped to a specific note of the melody. The LEDs light up in sequence with the corresponding notes.
- Buzzer Control: The 'tone()' function generates the sound for each note. The melody is played with a delay between each note.
- Notes: The notes C, D, E, F, G, and A are assigned to specific frequencies and are played in order to create the melody.

License

This project is open-source. Feel free to modify and distribute it under the [MIT License](LICENSE).
