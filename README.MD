# Desabilitar o botão do meio do mouse para evitar que fique colando onde nao deve.
# para listar
xinput --list

#no meu exemplo é:Virtual core pointer                    	id=2	[master pointer  (3)]
⎜   ↳ Virtual core XTEST pointer              	id=4	[slave  pointer  (2)]
⎜   ↳ COUGAR COUGAR 450K  Gaming Keyboard Mouse	id=13	[slave  pointer  (2)]
⎜   ↳ COUGAR COUGAR 450K  Gaming Keyboard Consumer Control	id=15	[slave  pointer  (2)]

⎜   ↳ Microsoft Microsoft® 2.4GHz Transceiver v7.0 Mouse	id=18	[slave  pointer  (2)]

⎜   ↳ Microsoft Microsoft® 2.4GHz Transceiver v7.0 Consumer Control	id=19	[slave  pointer  (2)]
⎜   ↳ Microsoft Microsoft® 2.4GHz Transceiver v7.0 Consumer Control	id=20	[slave  pointer  (2)]
⎜   ↳ ELAN0504:00 04F3:3091 Mouse             	id=23	[slave  pointer  (2)]
⎜   ↳ ELAN0504:00 04F3:3091 Touchpad          	id=24	[slave  pointer  (2)]
⎣ Virtual core keyboard                   	id=3	[master keyboard (2)]
    ↳ Virtual core XTEST keyboard             	id=5	[slave  keyboard (3)]
    ↳ Power Button                            	id=6	[slave  keyboard (3)]
    ↳ Video Bus                               	id=7	[slave  keyboard (3)]
    ↳ Acer Wireless Radio Control             	id=8	[slave  keyboard (3)]
    ↳ Video Bus                               	id=9	[slave  keyboard (3)]
    ↳ Power Button                            	id=10	[slave  keyboard (3)]
    ↳ Sleep Button                            	id=11	[slave  keyboard (3)]
    ↳ COUGAR COUGAR 450K  Gaming Keyboard     	id=12	[slave  keyboard (3)]
    ↳ COUGAR COUGAR 450K  Gaming Keyboard System Control	id=14	[slave  keyboard (3)]
    ↳ COUGAR COUGAR 450K  Gaming Keyboard     	id=16	[slave  keyboard (3)]
    ↳ Microsoft Microsoft® 2.4GHz Transceiver v7.0	id=17	[slave  keyboard (3)]
    ↳ Microsoft Microsoft® 2.4GHz Transceiver v7.0 System Control	id=21	[slave  keyboard (3)]
    ↳ HD User Facing: HD User Facing          	id=22	[slave  keyboard (3)]
    ↳ AT Translated Set 2 keyboard            	id=25	[slave  keyboard (3)]
    ↳ Acer WMI hotkeys                        	id=26	[slave  keyboard (3)]
    ↳ COUGAR COUGAR 450K  Gaming Keyboard Consumer Control	id=27	[slave  keyboard (3)]
    ↳ Microsoft Microsoft® 2.4GHz Transceiver v7.0 Consumer Control	id=28	[slave  keyboard (3)]
    ↳ Microsoft Microsoft® 2.4GHz Transceiver v7.0 Consumer Control	id=29	[slave  keyboard (3)]



# ache o id do mouse e depois 
xinput set-button-map 18 1 0 3 4 5 6 7 8 9 10
