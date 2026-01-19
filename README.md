# Sensor System 2025-2026: lab topics

## Homework02 - Microphone and LED
- **TOPICS:** Microphone, LED, GPIO (interrupts, RW),
- Modify the status (switch on / off) of the NUCLEO green LED, every time you snap your fingers.
- *original version*

## Homework02_b - LED PWM
- **TOPICS:** LED, PWM
- Make the NUCLEO green LED blink at a 1 Hz rate using PWM generation on the corresponding channel.
- *original version*

## Homework03 - Play song (HAL_Delay)
- **TOPICS:** Microphone, Speaker, PWM, GPIO (interrupts), HAL_Delay
- Play a song using the speaker when the microphone detects a loud sound. Using HAL_Delay.
- *original version*

## Homework03_b - Play song
- **TOPICS:** Microphone, Speaker, PWM, Timer (IT mode), GPIO (interrupts)
- Play a song using the speaker when the microphone detects a loud sound. WITHOUT using HAL_Delay.
- *corrected version*

## Homework04 - UART TX
- **TOPICS:** USART (TX DMA mode), Timer (IT mode)
- Send a string containing your name and your year of birth followed by a new line every second using USART DMA.
- *corrected version*

## Homework04_b - LCD
- **TOPICS:** LCD, Timer (IT mode)
- Write on the LCD the name of each member of your group, one per line, in alphabetical order.
- *corrected version*

## Homework05 - UART RX
- **TOPICS:** USART (RX_ToIdle DMA mode), LCD
- Try sending from the PC via UART a string of variable length that is displayed on the LCD.
- *corrected version*

## Homework05_b - Potentiometer
- **TOPICS:** Potentiometer, ADC (IT mode), USART (TX)
- Acquire the potentiometer voltage using a timer to trigger a conversion at a regular conversion rate of 1 Hz and sending the value to a remote terminal.
- *corrected version*

## Homework05_c - Potentiometer and LCD
- **TOPICS:** Potentiometer, ADC (IT mode), LCD (drawbar)
- Acquire the potentiometer voltage using a timer to trigger a conversion at a regular conversion rate of 1 Hz and showing the value on the LCD.
- *corrected version*

## Homework06 - ADC (multiple readings)
- **TOPICS:** Potentiometer, Temperature sensor, Vref, ADC (DMA circular mode), USART (TX DMA mode)
- Acquire three voltages (Potentiometer, Temperature sensor, Vref) every 1s and send them to a remote terminal.
- *corrected version*

## Homework06_b - Light sensor
- **TOPICS:** LDR, ADC (DMA circular mode, HalfCpltCallback), USART (TX DMA mode)
- Acquire LDR resistance value every ms and to send its average value to a remote terminal every 1s. Then convert the resistance value to a lux level and send that to the remote terminal.
- *corrected version*

## Homework07 - Temperature sensor
- **TOPICS:** LM75 (Temperature sensor), I2C (TX-RX DMA mode), USART (TX DMA mode)
- Read the temperature measured by the LM75 and send it to a remote terminal every 1 second. Read all 11 bits within an interrupt routine.
- *corrected version*

## Homework08 - Acceleromenter
- **TOPICS:** Accelerometer, I2C, USART (TX DMA mode)
- Read the acceleration measured by the accelerometer and send it to a remote terminal every 1 second. Using timer interrupts and UART DMA.
- *corrected version*

## Homework08_b - Accelerometer (I2C DMA mode)
- **TOPICS:** Accelerometer, I2C (TX-RX DMA mode), USART (TX DMA mode)
- Read the acceleration measured by the accelerometer and send it to a remote terminal every 1 second. Using timer interrupts, I2C DMA and UART DMA.
- *corrected version*

## Homework09 - LED Matrix
- **TOPICS:** LED Matrix, SPI (TX DMA mode)
- Transmit a letter to the LED matrix using SPI and a timer interrupt. Alternate between two letters (or one letter and one symbol).
- *corrected version*

## Homework10 - Keyboard
- **TOPICS:** Keyboard, Timer (IT mode), USART (TX DMA mode)
- Scan each column and read the keyboard using a timer interrupt and send the corresponding character to the PC using UART.
- *corrected version*

## Homework10_b - Encoder
- **TOPICS:** Encoder, Timer (encoder mode), USART (TX DMA mode)
- Read the encoder position and send to the PC the rotation speed in rpm.
- *corrected version*

## Homework11_TX - IR and Keyboard
- **TOPICS:** IR Communication, Keyboard, PWM, Timer (IT mode), USART (TX IR mode)
- Scan the pushbutton matrix and send the data corresponding to the pressed button via IR UART.
- *original version*

## Homework11_RX - IR and LED Matrix
- **TOPICS:** IR Communication, LED Matrix, SPI (TX DMA mode), Timer (IT mode), USART (RX IR mode)
- Receive the IR UART data and display the corresponding character on the LED matrix.
- *original version*

## Homework11_b - IR TX+RX
- **TOPICS:** IR Communication, Keyboard, PWM, LED Matrix, SPI (TX DMA mode), Timer (IT mode), USART (TX-RX IR mode)
- Integrate IR UART TX and RX in the same board
- *corrected version*
