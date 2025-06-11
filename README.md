# PUSH-BUTTON-COUNTER

*COMPANY* : CODTECH IT SOLUTION

*NAME* : AVANI D K

*INTERN ID* : CT04DG131

*DOMAIN* : EMBEDDED SYSYTEMS

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH

# TASK DESCRIPTION

### Project Description:
Push Button Counter with LCD Display
This project demonstrates a simple yet educational use of Arduino to create a digital counter system using a push button and a 16x2 LCD display. It is ideal for beginners who want to learn basic embedded systems concepts such as input handling, output display, and digital logic implementation with Arduino.

The main purpose of this project is to increment a counter every time a push button is pressed, and to display the count on an LCD screen. The design helps users understand how microcontrollers interface with external components like switches and display modules. It also introduces key programming concepts like debouncing, pin configuration, and serial monitoring for debugging.

The project was created and simulated using Tinkercad Circuits, a free online platform that allows users to design and test Arduino-based projects without the need for physical components. This makes it highly accessible and easy to replicate for learning or demonstration purposes. Even those without access to an Arduino board or LCD display can interact with the simulation and observe how each component behaves in real time.

 How It Works
A digital input pin on the Arduino is connected to a push button. When the button is pressed, the Arduino detects the change in signal and increments a counter variable stored in memory. The updated value of the counter is then sent to a 16x2 LCD screen, which displays the count in real time. The LCD is wired in 4-bit mode to reduce the number of required digital pins, and its contrast is controlled using a 10kΩ potentiometer.

The push button is configured with Arduino's internal pull-up resistor to keep the circuit simple and avoid floating input values. This setup reads a LOW signal when pressed, making it easier to detect presses reliably. A short delay is also used after a button press to prevent false triggers due to button bouncing.

The LCD is interfaced using the LiquidCrystal library, a standard Arduino library that simplifies communication with HD44780-compatible LCDs. Six digital pins are used for data and control lines (RS, E, D4–D7), and the RW pin of the LCD is grounded to keep it in write mode. The LCD backlight and power pins are connected to 5V and GND respectively to ensure proper brightness and operation.

In addition, users can expand the project by adding features such as a reset button, count-down mode, or EEPROM storage to retain values across resets. These extensions provide a good opportunity for learners to explore concepts like digital write logic, conditional branching, and memory management on microcontrollers.

 *Learning Outcomes*
This project offers hands-on experience in:

Digital input/output handling using Arduino

LCD interfacing in 4-bit mode

Using internal pull-up resistors

Implementing button debouncing

Basic program flow control using if statements

Serial debugging with Serial.print()

Simulating circuits using Tinkercad

Modular thinking through potential feature upgrades

It is also a great foundation for more advanced projects like menu systems, multi-button setups, or digital user interfaces. Students working on mini-projects, prototypes, or simple interactive devices can benefit from understanding this pattern of user input and visual output.

 *Applications*
While simple in nature, this project models the basic principles behind more complex systems such as:

Digital event counters

Inventory clickers

People counters at entryways

Scoreboards and timer-based applications

DIY electronics counters for labs or workshops

 *Tools & Technologies Used*
Arduino Uno

16x2 LCD Display

Push Button

10kΩ Potentiometer

Tinkercad Circuits (for simulation)

Arduino IDE (for coding)

# OUTPUT

![Image](https://github.com/user-attachments/assets/c6663821-ef5c-4e29-889b-a31908be7f19)
