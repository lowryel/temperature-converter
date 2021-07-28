# temperature-converter
#python based app to convert temperature from fahrenheit to celsius and frm celsius to kelvin
"""
This program sees to convert temperature from Fahrenheit to Degree Celsius and from
Celsius to Kelvin
"""
# The program gets an input from the user in Fahrenheit
def convert_tempt():
    Tf = input('Enter temperature in Fahrenheit: ')
    return Tf
#This accepts the input and convert to Celsius
def Celsius(Tf):
    Tc = 5 / 9 * (float(Tf) - 32)
    print("Celsius: ", Tc)
    return Tc
#Then this accept the value obtained in Celsiusand convert to Kelvin
def Kelvin(Tc):
    Tk = float(Celsius(Tc)) + 273.15
    print("Kelvin:", Tk)

Kelvin(convert_tempt())
