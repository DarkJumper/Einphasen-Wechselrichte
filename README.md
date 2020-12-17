# Steuerung einer Einphasenasynchronmaschine

_Im Rahmen des Projektes soll ein einfaches PWM Modul entwickelt werden, mit dem ein 1-Phasen-Asynchronmotor drehzahlvariabel angesteuert wird. Mit diesem soll es möglich sein, einen 1-Phasen-Asynchronmotor anzusteuern._

## Systemanforderung

1.  Option 1
    - Systemworkbench (Eclipse)
    - STM32CubeMX
2.  Option 2
    - STM32CubeIDE

## Wechselrichter Libary

Um Berechnungen und den Prescaler zu ändern, wurde aus Übersichtsgrunde eine Libary erstellt. `Wechselrichter.c`
