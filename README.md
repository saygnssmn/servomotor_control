# servomotor_control_with-uart
Bu projede SG90 servo motoru bilgisayar üzerindeki tuşlarla kontrol edilmektedir. Kontrol UART haberleşmesiyle sağlanmaktadır. Klavye üzerinden 1 tuşuna basılması 0.5ms' lik , 2 tuşuna basılması 1ms'lik, 3 tuşuna basılması 2.5ms'lik pwm sinyali üretmektedir. Proje UART haberleşmesinin ve PWM sinyallerinin anlaşılmasında yardımcı bir projedir. Herhangi bir soru için sygnssmn@hotmail.com mail adresime mail atabilirsiniz.

In this project, SG90 servo motor is controlled by keys on the computer. Control is provided by UART communication. Pressing 1 on the keyboard produces a 0.5ms pwm signal, pressing 2 produces a 1ms pwm signal and pressing 3 produces a 2.5ms pwm signal. The project is an auxiliary project in understanding UART communication and PWM signals. For any questions, you can mail to my mail address sygnssmn@hotmail.com.

Hardware: STM32-F103C8T6 Microcontroller, SG90 servo motor.
IDE: STM32CubeIDE 1.1.0
