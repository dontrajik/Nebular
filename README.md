I use ATC1441's UART flasher website:
(https://atc1441.github.io/ATC_TLSR_Paper_UART_Flasher.html)

|NEBULAR |Flasher|
|-----------|-----------------|
|    GND    |    GND          |
|    VCC    |    3V3          |
|    SWS    |    TXD          |
|    NRST   |    GND          |

Baud rate 460800, 3s wait

Connect -> unlock -> select FW -> Write

# !!! UNPLUG NRST IN THE ACTIVATION PHASE OF THE FLASHING !!!

If regular fw not working try the [SSD version](https://github.com/dontrajik/Nebular/blob/main/IF_ALPHA_OR_INVERSE_NOT_GOOD_TLSR_HS_BWY_35_SSD.bin).
