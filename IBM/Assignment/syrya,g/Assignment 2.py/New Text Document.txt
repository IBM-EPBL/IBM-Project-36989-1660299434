'''
Assignment 2
Build a python code,Assume you get temperature
and humidity values and write a condition to continously
detect alarm in case of high temperature
'''

#PROGRAM

def weather(a):
    if temp>40:
        print("It's High temperature")
    elif temp>20:
        print("It's a normal temperature")
    elif temp>0:
        print("It's Cold")
    elif temp<0:
        print("It's freezing cold")
        
temp=int(input())
humi=int(input())
weather(temp)