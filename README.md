# Pulse Width Modulator using Verilog
## Developing a PWM of variable duty cycle using Verilog.

As its name suggests, pulse width modulation speed control works by driving the motor with a series of “ON-OFF” pulses and varying the duty cycle, the fraction of time that the output voltage is “ON” compared to when it is “OFF”, of the pulses while keeping the frequency constant.

This verilog code implements a pulse width modulator with a pulse of time period 20 seconds and a default duty cycle of 50 percent. The duty cycle can be increased or decreased by a factor of 10 %. The test bench first increases the duty cycle to 60% and then to 70%, bringing it down to 60% again to illustrate the functioning of the program.
