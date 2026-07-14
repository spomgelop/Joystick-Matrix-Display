**Joystick-Controlled LED Matrix Directionn Indicator**

A simple Arduino project that reads the input from an analog joystick and displays a directional arrow (up, down, left, right) on an 8x8 LED matrix. Returning the joystick to center clears the display.

**How it works**
- The joystick's x and Y axes are read via analog pins (A0, A1)
- Threshold values determine direction: pushing the joystick past a certain point in any direction triggers the corresponding arrow pattern.
- the 'LedControl' library drives the 8x8 LED matrix (MAX7219 driver) to render the pattern

**Components used**
- Arduino Uno
- Analog joystick module
- 8x8 Matrix (MAX7219 driver)
- Breadboard and jumper wires

**Demo Simulation**

<img width="752" height="685" alt="image" src="https://github.com/user-attachments/assets/90baac53-21f1-4288-956f-2abccbf18de2" />
<img width="696" height="647" alt="image" src="https://github.com/user-attachments/assets/48c3cc92-459d-4406-a1b6-64e15b6be906" />
<img width="697" height="641" alt="image" src="https://github.com/user-attachments/assets/24930a2b-4f1f-453f-ab7f-1063699b017b" />
<img width="702" height="631" alt="image" src="https://github.com/user-attachments/assets/39360884-1346-4d74-87d5-0e31ee025379" />
<img width="712" height="647" alt="image" src="https://github.com/user-attachments/assets/baa64559-41d5-412e-a698-18425e2d7b0d" />





**Libraries Required**
- [LedControl](https://wayoda.github.io/LedControl/) - Install via Arduino IDE Library Manager

**Future Improvements**
- Utilise the joystick's push-button (SW pin) for additional functionality
- Support diagonal directions
- Adjustable sensitivity/threshold values
