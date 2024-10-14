# Project 3: Assembly-Based Real-Time Clock Using STM32F103

## Description
This project involves writing a simple **Real-Time Clock (RTC)** using assembly language on the **STM32F103** microcontroller. It demonstrates expertise in low-level microcontroller programming, utilizing interrupts and low-power modes to maintain precise timekeeping while conserving power.

## Project Goals
- Master low-level programming with assembly language on STM32.
- Implement and optimize power-saving techniques using low-power modes.
- Showcase precise timekeeping with minimal resource utilization.

## Step-by-Step Implementation

### 1. Set Up Development Environment
- Install **Keil MDK** or **STM32CubeIDE** with support for assembly language.
- Configure the STM32F103 microcontroller for bare-metal programming, ensuring minimal dependencies for direct hardware control.

### 2. Write Assembly Code for RTC Setup
- Initialize the **RTC** peripheral using assembly instructions.
- Configure interrupts to update the time every second.
- Utilize **Nested Vector Interrupt Controller (NVIC)** registers for handling RTC interrupts, ensuring efficient time updates.

### 3. Low-Power Mode Implementation
- Implement **sleep mode** using assembly instructions to reduce power consumption.
- Wake up the microcontroller using external interrupts or RTC alarms.
- Measure power consumption and optimize the RTC's impact on battery life for extended operation.

### 4. Display Time Data
- Output time data through the **UART interface** using assembly instructions.
- Verify the timekeeping accuracy using a terminal like **PuTTY**.

### 5. Testing and Optimization
- Test the RTC functionality under various power modes (normal, sleep, deep sleep).
- Optimize the code for size and speed by using direct register manipulation.
- Fine-tune the interrupt handling and low-power configurations for optimal performance.

### 6. Demonstration and Documentation
- Record a video showcasing the RTC in action, including transitions between different low-power modes.
- Document the assembly code, design decisions, and power measurements on **GitHub**.

## Tools and Software Used
- **Keil MDK** or **STM32CubeIDE** for assembly programming.
- **STM32F103** microcontroller.
- **UART terminal** (e.g., PuTTY) for testing and time data verification.
- **GitHub** for version control and detailed documentation.

## Video Demonstration
Check out the [video demonstration](https://www.youtube.com/) of the RTC in action, showcasing its ability to maintain accurate timekeeping while conserving power.

## Contact
For questions or suggestions, feel free to reach out!
- [Your LinkedIn Profile](https://www.linkedin.com/in/your-profile)
- [Email Me](mailto:user@example.com)

## References
- [STM32F103 Reference Manual](https://www.st.com/en/microcontrollers-microprocessors/stm32f103.html)
- [Keil MDK Documentation](https://www.keil.com/docs/pdf/MDK5_UserGuide.pdf)
- [STM32CubeIDE User Guide](https://www.st.com/resource/en/user_manual/dm00611858-stm32cubeide-user-manual-stmicroelectronics.pdf)
