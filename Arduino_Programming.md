# 2 Functions
  - setup() - executes once
  - void() - executes until arduino off

Program executes in linear fashion

# Variables

- use to store values 
- values can be then used by mentioning Variables
- Global variables are declared outside of setup() and void()
- Local variables are declared inside Functions


# Basic Functions

- pinMode(13,OUTPUT) - tells arduino which pin will be use and in what way input or output
- digitalWrite(13,HIGH) - send HIGH (5V) or LOW signal (0V) to pin 
- delay(1000) - pauses program for 1 sec

# Serial Communication

- Tx and Rx (transmitter pin and receiver pin)
- UART Communication Protocol
- When we Upload program it is uploaded with the help of Rx pin only
- serial Monitor displays the serial Communication which data is sent/recieved

# Serial Functions

- Serial.begin(9600) - begin serial Communication at the rate 9600 bits per second
- Serial.read() - read what communication is taking place
- Serial.print() - print on serial monitor
- Serial.available() - Outputs true when Serial communication is taking place

# Numeric Data Types

- byte - stores 8 bit unsigned no. from 0-255
- byte var = 155;
- word - 16 bit unsigned no . from 0-65535
- short - 16 bit signed no. from -32768-32767
- int - same as short
- long - 32 bit signed no. 
- float - decimal numbers
- double - same as float
