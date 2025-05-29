# hfss-microstrip-50ohm

can be easily fabricated on PCBs so it's the most widely used antenna.
![image](https://github.com/user-attachments/assets/b946fdf6-970e-4abc-b398-1ebcdf2076be)
by varying the position of microstrip transmission line, we can do the impedance matching of transmission line and the antenna.
L= lambda/2 (usually) why?
Microstrip antenna does not radiates from the side of L, it radiates just from the side of W. why? if we increase W we increase the radiation and also we will modify the impedance matching by changin the sizeof W.
what should be the height of dielectric? the higher, the more radiation but until some extent. limitation is: h<0.05lambda, this is true for most dielectric materials but some materials are different and let us have higher radiations.
operating freq= C/(2L*sqrt(epsilon_r))
E field= depends on W and L but usually L is fixed. so just W.
so W controls input impedance (Inversly), BW (directly), Radiation pattern (directly)


Limitation: 
1. narrow bw
2. gain around 3-7 db by single patch
3. radiation into half plane
4. low power handling capacity
5. it excites surface wave
