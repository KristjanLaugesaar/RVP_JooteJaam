# Arendusblogi

Enne komponentide valimist, on olemas juba toiteplokk 24v 150w ja ka jootekolvi otsad ning käepide.

## 10. okt

Kuna jootekolb hakkab 24v pealt töötama, siis on vaja loogika jaoks välja mõelda, millega pinge saada 24v pealt 3.3v peale.
Selleks sobiks buck converter. Nagu näiteks MC3x063A, mis võib olla nii buck, boost kui ka inverting topoloogiaga konverter.

Mikroprotsessori valik. Idee on kasutada ESP32 SoCi. Kuna mul ei ole vaja wifi ega bluetooth ühendusi siis saan valida väiksema paketiga kiibi. 
ESP32-PICO-D4 on väga võimekas moodul. Sellel on 4MB flashi, mis on rohkem kui piisav selle projekti jaoks. PWM, et juhtida mosfeti ning liides ekraani ühendamise jaoks.

Tipu sees oleva termopaari mõõtmiseks on olemas MAX31855 kivi. Sellel on sisse ehitatud külma ühenduskoha kompenseerimine. See suhtleks mooduliga üle spi ühenduse.

REX012832 oled ekraan, 124x32 pikslit.

