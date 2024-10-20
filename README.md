# Arduino Projects by Marcello Ardika Raharja

Welcome to the Arduino projects repository. This collection includes various projects written in C++ for Arduino, showcasing basic electronics and programming concepts.

## Project List
## Project 1: Buzzer Melody Player

### Overview
The **Buzzer Melody Player** is an Arduino-based project that plays a melody using a buzzer. The project is programmed to play specific musical notes in a sequence, creating a tune that can be heard through the buzzer. The project demonstrates basic control of a piezo buzzer using Arduino and C++ to generate different frequencies corresponding to musical notes.

### Features
- **Melody Playback:** The code plays a sequence of notes, simulating a melody through the buzzer.
- **Note Definition:** Each musical note (C, D, E, F, G, A, B) is associated with a specific frequency, which is output to the buzzer.
- **Timing Control:** Delays are used to control the duration of each note and the pauses between notes, creating a rhythm.
- **Customizable:** The melody and timing can be easily modified to create different tunes.

### Code Functionality
1. **Pin Setup:** The buzzer is connected to pin 5 of the Arduino, set as an output pin.
2. **Note Functions:** Individual functions (`C()`, `D()`, `E()`, etc.) are defined to play specific notes by setting the frequency and duration using the `tone()` function.
3. **Main Melody Loop:** The `loop()` function calls these note functions in a specific sequence, with delays in between to form a melody.
4. **Tone Generation:** The `tone()` function generates the required frequency for each note, and the `delay()` function controls the length of each note and the pauses between them.

---

## Project 2: RGB LED Color Fader

### Overview
The **RGB LED Color Fader** is an Arduino project that controls an RGB LED to smoothly transition between colors. The project uses Pulse Width Modulation (PWM) to adjust the intensity of each color (red, green, and blue) and create a fading effect. This project demonstrates how to create a smooth color transition using basic Arduino programming techniques.

### Features
- **Smooth Color Transition:** The RGB LED transitions smoothly between different colors by gradually changing the intensity of the red, green, and blue components.
- **PWM Control:** Uses the `analogWrite()` function to control the brightness of each color channel, allowing for fine-tuned color blending.
- **Customizable Speed:** The transition speed can be adjusted by changing the delay values in the code.
- **RGB Mixing:** The project demonstrates how to mix different amounts of red, green, and blue light to create a wide range of colors.

### Code Functionality
1. **Pin Setup:** The RGB LED is connected to three Arduino pins (9, 10, 11), each corresponding to one color channel (red, green, blue).
2. **Color Setting Function:** The `setRGB()` function takes three parameters (red, green, blue) to set the brightness of each color channel.
3. **Color Fading Loop:** The `loop()` function gradually increases and decreases the brightness of each color channel in a sequence to create a smooth transition between colors.
4. **PWM Output:** The `analogWrite()` function is used to output a PWM signal to each color channel, adjusting the brightness of the LED.

## Getting Started

### Prerequisites
- Arduino IDE installed
- Arduino board (e.g., Uno, Mega)
- Required components (e.g., LEDs, resistors, buzzer)

**Note:** Copying, forking, and cloning this repository are strictly forbidden and not allowed.

## Contact

For any inquiries, please contact:

- **Maintainer Name:** [Marcello Ardika Raharja]
- **Email:** [ardikamarcel@gmail.com]

Thank you for visiting the Arduino Project repository!
