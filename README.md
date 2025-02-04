# Four-DC-Motors
![image](https://github.com/user-attachments/assets/6a58ca22-dd6e-4527-9ad4-76a89c3ec085)


1. **Arduino Uno:**  
   - The main microcontroller that sends control signals to the motor drivers.

2. **L293D Motor Driver ICs (2 units):**  
   - Dual H-Bridge motor drivers used to control the four DC motors.
   - Each L293D controls two motors.
   - Receives control signals from the Arduino to determine the motor speed and direction.

3. **Four DC Motors:**  
   - Connected to the outputs of the L293D chips.
   - Their direction and speed are controlled by the Arduino.

4. **9V Battery:**  
   - Powers the motors and is connected to the breadboard’s power rail.

5. **Breadboard:**  
   - Used for organizing and connecting the circuit components.

### **How It Works:**
- **The Arduino sends control signals to the L293D chips** through digital pins, which define the direction of each motor.
- **Power is supplied by the 9V battery**, distributed to the motors through the motor driver ICs.
- **Each motor has two wires, which determine its rotation direction:**
  - Sending **HIGH to one input and LOW to the other makes the motor rotate in one direction**.
  - Reversing the signals **makes the motor rotate in the opposite direction**.

### **Possible Applications:**
- Building an **autonomous robot** 🤖🚀
- Creating a **line-following or remote-controlled car**
- Experimenting with **motor control systems**

