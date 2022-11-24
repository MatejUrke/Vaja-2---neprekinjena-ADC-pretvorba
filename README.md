# Vaja-2---neprekinjena-ADC-pretvorba

1. Cilj naloge: S pomočjo programskega okolja STM32CubeIDE in HAL knjižnicami sprogramirajte mikroprocesor tako, da bo izvajal neprekinjene ADC pretvorbe z izbranim potenciometrom. Takšna pretvorba je primerna za hitro in nenehno branje vhodne vrednosti.
2. postopek:
- Nucleo-L476RG
- izbran pin je PA0 na plošči je A0
- Poleg pina se izpiše ADC1_IN1.
- spreminjajo se druge vrednosti npr. 64 MHz namesto 170 MHz.
- preskalirana = 16Mhz. V mikrosekundah pa 16.84ms.

PINOUT:
![Posnetek zaslona 2022-11-24 112227](https://user-images.githubusercontent.com/97598727/203761925-34d364ec-f9d1-4aeb-b0a7-0507ebdeae25.png)

Slika vezave z potenciometrom:
![image_67183617](https://user-images.githubusercontent.com/97598727/203762579-88c954fb-6d19-4074-9e8f-f4ab3dfbdbaa.JPG)

KOMENTAR:

Imela sva problem pri delovanju potenciometra, ter z kodo.

KODA:

