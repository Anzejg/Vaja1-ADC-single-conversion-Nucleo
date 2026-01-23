# Vaja1-ADC-single-conversion-Nucleo

Slikovni izrezek PINOUT:

<img width="649" height="538" alt="image" src="https://github.com/user-attachments/assets/ab23b7cc-a6bb-49e2-ad5e-22bb7056698c" />


IZREZEK ADC3, configuration:

<img width="681" height="671" alt="image" src="https://github.com/user-attachments/assets/4d9393f4-d79b-43b4-b117-628a8c4d82c8" />

Slika vezave potenciometra:

<img width="768" height="1024" alt="image" src="https://github.com/user-attachments/assets/8a383be4-2432-4ebf-be92-11743bd7f88e" />












ODGOVORI NA VPRAŠANJA:

2. B)
   Zelena LED: pin PA5

   modra tipka: pin PC13

   C) Naša razvojna ploščica ima 3 ADC pretvornike

   D) Opozorilna trikotnika ob  ADC1 in ADC2 nakazujeta na konflikt virov, saj so nekateri pini, potrebni za ADC vhode, že zasedeni z drugimi  napravami. To težavo odpravimo tako, da na pinih PA2, PA3 in PA5 onemogočimo trenutne funkcije, s čimer sprostimo pot za delovanje ADC.

   E) V ADC3 so štirje vhodi: IN1, IN2, IN3 in IN4

    F)  Poleg pina se izpiše: ADC3_IN1. To je pin PC0

   I) Ostale možne ločljivosti pretvorbe in območja vrednosti so :
   
6-bitna, od 0 do 63,

10-bitna, od 0 do 1023,

12-bitna, od 0 do 4095.
   

   KOMENTAR:
Program deluje po pričakovanjih. Debugger nama sprva ni deloval zato sva se odločila da bova vrednosti prikazovala preko STM Studia. Preko STM Studia pa je delovalo odlično kot je prikazano na video posnetku. Na posnetku pa je lepo vidno kako se 8-bitna vrednost spreminja od 0 do 255 z vrtenjem potenciometra.
   
