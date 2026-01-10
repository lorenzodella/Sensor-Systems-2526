## Homework02
- **TOPICS:** Microphone, LED, GPIO (interrupts, RW),
- Modify the status (switch on / off) of the NUCLEO green LED, every time you snap your fingers.
- *original version*

## Homework02_b
- **TOPICS:** LED, PWM
- Make the NUCLEO green LED blink at a 1 Hz rate using PWM generation on the corresponding channel.
- *original version*

## Homework03
- **TOPICS:** Microphone, Speaker, PWM, GPIO (interrupts), HAL_Delay
- Play a song using the speaker when the microphone detects a loud sound. Using HAL_Delay.
- *original version*

## Homework03_b
- **TOPICS:** Microphone, Speaker, PWM, Timer (IT mode), GPIO (interrupts)
- Play a song using the speaker when the microphone detects a loud sound. WITHOUT using HAL_Delay.
- *corrected version*

## Homework04
- **TOPICS:** USART (TX DMA mode), Timer (IT mode)
- Send a string containing your name and your year of birth followed by a new line every second using USART DMA.
- *corrected version*

## Homework04_b
- **TOPICS:** LCD, Timer (IT mode)
- Write on the LCD the name of each member of your group, one per line, in alphabetical order.
- *corrected version*

## Homework05
- **TOPICS:** USART (RX_ToIdle DMA mode), LCD
- Try sending from the PC via UART a string of variable length that is displayed on the LCD.
- *corrected version*

## Homework05_b
- **TOPICS:** Potentiometer, ADC (IT mode), USART (TX)
- Acquire the potentiometer voltage using a timer to trigger a conversion at a regular conversion rate of 1 Hz and sending the value to a remote terminal.
- *corrected version*

## Homework05_c
- **TOPICS:** Potentiometer, ADC (IT mode), LCD (drawbar)
- Acquire the potentiometer voltage using a timer to trigger a conversion at a regular conversion rate of 1 Hz and showing the value on the LCD.
- *corrected version*

## Homework06_a
- **TOPICS:** Potentiometer, Temperature sensor, Vref, ADC (DMA circular mode), USART (TX DMA mode)
- Acquire three voltages (Potentiometer, Temperature sensor, Vref) every 1s and send them to a remote terminal.
- *corrected version*

## Homework06_b
- **TOPICS:** LDR, ADC (DMA circular mode, HalfCpltCallback), USART (TX DMA mode)
- Acquire LDR resistance value every ms and to send its average value to a remote terminal every 1s. Then convert the resistance value to a lux level and send that to the remote terminal.
- *corrected version*

## Homework07
- **TOPICS:** LM75 (Temperature sensor), I2C (TX-RX DMA mode), USART (TX DMA mode)
- Read the temperature measured by the LM75 and send it to a remote terminal every 1 second. Read all 11 bits within an interrupt routine.
- *corrected version*

## Homework08
- **TOPICS:** Accelerometer, I2C, USART (TX DMA mode)
- Read the acceleration measured by the accelerometer and send it to a remote terminal every 1 second. Using timer interrupts and UART DMA.
- *corrected version*

## Homework08_b
- **TOPICS:** Accelerometer, I2C (TX-RX DMA mode), USART (TX DMA mode)
- Read the acceleration measured by the accelerometer and send it to a remote terminal every 1 second. Using timer interrupts, I2C DMA and UART DMA.
- *corrected version*