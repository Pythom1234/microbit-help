| Název registrů | Adresa | Bitová maska | Popis                          |
|-----------------|--------|--------------|--------------------------------|
| ENABLE<PON>     | 0x80   | 0x01         | Power ON                       |
| ENABLE<PEN>     | 0x80   | 0x04         | Proximity Enable               |
| ENABLE<PIEN>    | 0x80   | 0x20         | Proximity Interrupt Enable     |
| ENABLE<GEN>     | 0x80   | 0x40         | Gesture Enable                  |
| ENABLE<AEN>     | 0x80   | 0x02         | ALS Enable                      |
| ENABLE<AIEN>    | 0x80   | 0x10         | ALS Interrupt Enable            |
| ENABLE<WEN>     | 0x80   | 0x08         | Wait Enable                     |
| CONTROL<PGAIN>  | 0x8F   | 0x0C         | Proximity Gain Control          |
| CONTROL<LDRIVE> | 0x8F   | 0xC0         | LED Drive Strength              |
| CONTROL<AGAIN>  | 0x8F   | 0x03         | ALS Gain Control                |
| CONFIG1<LOWPOW> | 0x8D   | 0x40         | Low Power Clock Mode            |
| CONFIG1<WLONG>  | 0x8D   | 0x02         | Wait Long Enable                |
| CONFIG2<CPSIEN> | 0x90   | 0x40         | Clear diode Saturation Interrupt Enable |
| CONFIG2<PSIEN>  | 0x90   | 0x80         | Proximity Saturation Interrupt Enable |
| CONFIG2<LEDBOOST> | 0x90 | 0x30         | Proximity/Gesture LED Boost     |
| CONFIG3<PCMP>   | 0x9F   | 0x20         | Proximity Gain Compensation Enable |
| CONFIG3<PMSK_U> | 0x9F   | 0x08         | Proximity Mask UP Enable        |
| CONFIG3<PMSK_D> | 0x9F   | 0x04         | Proximity Mask DOWN Enable      |
| CONFIG3<PMSK_L> | 0x9F   | 0x02         | Proximity Mask LEFT Enable      |
| CONFIG3<PMSK_R> | 0x9F   | 0x01         | Proximity Mask RIGHT Enable     |
| STATUS<PGSAT>   | 0x93   | 0x40         | Proximity Saturation            |
| STATUS<PINT>    | 0x93   | 0x20         | Proximity Interrupt             |
| STATUS<PVALID>  | 0x93   | 0x02         | Proximity Valid                 |
| STATUS<CPSAT>   | 0x93   | 0x80         | Clear Diode Saturation          |
| STATUS<AINT>    | 0x93   | 0x10         | ALS Interrupt                   |
| STATUS<AVALID>  | 0x93   | 0x01         | ALS Valid                       |
| STATUS<PGSAT>   | 0x93   | 0x40         | Gesture Saturation              |
| PDATA           | 0x9C   |              | Proximity Data                  |
| PERS<APERS>     | 0x8C   | 0x0F         | ALS Interrupt Persistence      |
| PERS<PPERS>     | 0x8C   | 0xF0         | Proximity Interrupt Persistence |
| POFFSET_UR      | 0x9D   |              | Proximity Offset UP/RIGHT       |
| POFFSET_DL      | 0x9E   |              | Proximity Offset DOWN/LEFT      |
| PILT            | 0x89   |              | Proximity low threshold         |
| PIHT            | 0x8B   |              | Proximity high threshold        |
| PPULSE<PPLEN>   | 0x8E   | 0xC0         | Proximity Pulse Length          |
| PPULSE<PPULSE>  | 0x8E   | 0x3F         | Proximity Pulse Count           |
| ATIME           | 0x81   |              | ALS ADC Integration Time        |
| WTIME           | 0x83   |              | Wait Time                       |
| AILTL           | 0x84   |              | ALS low threshold, lower byte   |
| AILTH           | 0x85   |              | ALS low threshold, upper byte   |
| AIHTL           | 0x86   |              | ALS high threshold, lower byte  |
| AIHTH           | 0x87   |              | ALS high threshold, upper byte  |
| CDATAL          | 0x94   |              | Clear Data, Low byte            |
| CDATAH          | 0x95   |              | Clear Data, High byte           |
| RDATAL          | 0x96   |              | Red Data, Low byte              |
| RDATAH          | 0x97   |              | Red Data, High byte             |
| GDATAL          | 0x98   |              | Green Data, Low byte            |
| GDATAH          | 0x99   |              | Green Data, High byte           |
| BDATAL          | 0x9A   |              | Blue Data, Low byte             |
| BDATAH          | 0x9B   |              | Blue Data, High byte            |
| CICLEAR         | 0xE5   |              | Clear Channel Interrupt Clear  |
| PICLEAR         | 0xE5   |              | Proximity Interrupt Clear       |
| AICLEAR         | 0xE7   |              | All Non-Gesture Interrupt Clear |
| GPENTH          | 0xA0   |              | Gesture Proximity Entry Threshold |
| GEXTH           | 0xA1   |              | Gesture Exit Threshold          |
| GPULSE<GPULSE>  | 0xA6   | 0x3F         | Pulse Count                     |
| GPULSE<GPLEN>   | 0xA6   | 0xC0         | Gesture Pulse Length            |
| GFLVL           | 0xAE   |              | Gesture FIFO Level              |
| GSTATUS<GFOV>   | 0xAF   | 0x02         | Gesture FIFO Overflow           |
| GSTATUS<GVALID> | 0xAF   | 0x01         | Gesture Valid                   |
| GCONFIG1<GFIFOTH>| 0xA2   | 0xC0         | Gesture FIFO Threshold           |
| GCONFIG1<GEXMSK>| 0xA2   | 0x3C         | Gesture Exit Mask               |
| GCONFIG1<GEXPERS>| 0xA2  | 0x03         | Gesture Exit Persistence        |
| GCONFIG2<GGAIN> | 0xA3   | 0x60         | Gesture Gain Control            |
| GCONFIG2<GLDRIVE>| 0xA3  | 0x18         | Gesture LED Drive Strength      |
| GCONFIG2<GWTIME>| 0xA3   | 0x07         | Gesture Wait Time               |
| GCONFIG3<GDIMS> | 0xAA   | 0x03         | Gesture Dimension Select        |
| GCONFIG4<GFIFO_CLR>| 0xAB| 0x04         | Gesture FIFO Clear              |
| GCONFIG4<GIEN>  | 0xAB   | 0x02         | Gesture Interrupt Enable        |
| GCONFIG4<GMODE> | 0xAB   | 0x01         | Gesture Mode                    |
| GFIFO_U         | 0xFC   |              | Gesture FIFO Data, UP           |
| GFIFO_D         | 0xFD   |              | Gesture FIFO Data, DOWN         |
| GFIFO_L         | 0xFE   |              | Gesture FIFO Data, LEFT         |
| GFIFO_R         | 0xFF   |              | Gesture FIFO Data, RIGHT        |
| GOFFSET_U       | 0xA4   |              | Gesture Offset, UP              |
| GOFFSET_D       | 0xA5   |              | Gesture Offset, DOWN            |
| GOFFSET_L       | 0xA7   |              | Gesture Offset, LEFT            |
| GOFFSET_R       | 0xA9   |              | Gesture Offset, RIGHT           |
