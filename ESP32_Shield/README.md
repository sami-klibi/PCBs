a custom shield designed for the ESP32, aimed at centralizing and simplifying the control of various system components. This board integrates several essential elements:

    🧠 A dedicated slot for the ESP32, ensuring a clean and stable integration of the microcontroller.

    🔄 A TMC2209 stepper motor driver, used for quiet and precise motor control.

    🔋 An LM2596 voltage regulator, selected with the help of the datasheet [5], to provide a stable power supply to the system.

    🔔 An integrated buzzer for simple audible alerts.

    💡 Status indicator LEDs, to visually monitor the state and operation of the system.

The shield also includes several connection ports:

    ⛓️ A port for a limit switch used for homing and position detection.

    🔗 An I2C communication port for connecting servo motor driver boards (e.g., PCA9685).

    🔌 A port for the stepper motor connection.

    🌬️ A port for a cooling fan, ensuring efficient thermal management.

This shield provides a centralized, compact, and efficient management solution for the system’s hardware, reducing wiring complexity and improving physical integration within the enclosure.
 ### Routing
![Routing](ESP32_Shield/images/routing)
