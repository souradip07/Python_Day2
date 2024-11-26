# Python_Day2
#Variables
voltage = 5  
current = 2  

#Input/Output Operations
name = input("Enter your name: ")  
print(f"Welcome, {name}!")  

#Program to Calculate Resistance
voltage = float(input("Enter voltage (V): "))  
current = float(input("Enter current (I): "))  
resistance = voltage / current  
print(f"The resistance is {resistance:.2f} ohms.")  


#Project: Voltage Divider Calculator
r1 = float(input("Enter the resistance R1 (ohms): "))  
r2 = float(input("Enter the resistance R2 (ohms): "))  
vin = float(input("Enter the input voltage (V): "))  

vout = (r2 / (r1 + r2)) * vin  
print(f"The output voltage is {vout:.2f} V.")  


