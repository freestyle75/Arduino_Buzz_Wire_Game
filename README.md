# Arduino_Buzz_Wire_Game
Buzz Wire Build using Arduino

# Buzz Wire Game

A simple yet engaging **Buzz Wire Game** built using an Arduino and an LCD display, designed to challenge your hand-eye coordination and steady hand skills.

## How It Works

The game involves navigating a wire loop along a bent wire without touching it.  
- If the loop touches the wire, a **buzzer sounds**, and the LCD displays "Failed".  
- Successfully navigating to the end triggers a **"Well Done!"** message on the LCD.

## Features

- **Real-Time Feedback**:  
  - Displays messages on the **16x2 I2C LCD** for game progress.
- **Buzzer Alert**:  
  - Alerts the player when they fail.
- **Winning Message**:  
  - Congratulates the player upon successful completion.

## Components Used

- **Arduino Uno** (or compatible board)
- **16x2 I2C LCD Display**
- **Buzzer**
- **Connecting Wires**
- **Winning and Buzzer Pins** (sensors or conductive material)

## Circuit Diagram

- Connect the **LCD** to the Arduino using the I2C interface.
- Attach the **buzzer pin** to pin `2` and the **winning sensor pin** to pin `5`.

## How to Run

1. **Connect the components**:  
   Follow the circuit diagram to set up your hardware.
   
2. **Upload the code**:  
   Use the Arduino IDE to upload the code to your Arduino board.

3. **Power up**:  
   Once powered, the game begins with a welcome message: *"Buzz.wire"* and *"good.luck"*.

4. **Play the game**:  
   Navigate the wire loop without triggering the buzzer. If successful, the LCD will congratulate you!

## Acknowledgments

This project is inspired by the classic buzz wire game and made possible using Arduino and basic electronic components. Perfect for beginner-level electronics enthusiasts and hobbyists.

---

Enjoy playing and challenging your friends! 🚀
