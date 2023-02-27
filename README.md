Roller

## Jag vill bara ha en bra CO2-meter

Lettiska Aranet4 är lite dyr men har fantastisk batteritid (år) och kan kopplas ihop med telefon eller en dator om man vill. Den behöver inte heller kalibreras om. Man kan ha den på ett ställe, eller ta med sig. Fungerar lika bra.

Man kan köpa den direkt från tillverkaren här: <https://shop.aranet.com/europe/product/aranet4-home>

## Jag tycker drygt 2000 kronor är lite dyrt, finns det inget billigare?

De 2000 kronorna kan dock vara väl värda att spendera, istället för att köpa något billigare som man kanske inte blir nöjd med. Men det finns billigare som är stabila och bra. Dostmann har två stycken, Mini och Coach, som ger stabila värden. De kostar 700-900 kronor. Tyvärr har de inget batteri, utan måste drivas från USB om det är så att man vill ta dem med sig. Ström kan man ju fixa från en Powerbank. Det finns en Dostmann kalibreringsfri som har batteri, men recensioner på Amazon klagar på dålig kvalitet och överhettning.

Här kan man köpa TFA Dostmann AirCO2ntrol mini enligt Pricerunner:
* <https://www.pricerunner.se/pl/345-5201699/Elverktyg/TFA-AirControl-Mini-CO2-priser>

TFA Dostmann AirCO2ntrol Coach:
* <https://www.pricerunner.se/pl/590-3200141055/Termometrar-Vaederstationer/TFA-Dostmann-31.5009.02-priser>
(coach finns också på Amazon.se)

![Bild från https://nousaerons.fr/aero-score/](https://raw.githubusercontent.com/co2koll/co2koll.github.io/master/nous.png)

Bild från <https://nousaerons.fr/aero-score/>

Det finns många billiga CO2-mätare som måste kalibrera om sig varje eller varannan dag. Det innebär att de måste utsättas för luft som är helt genomventilerad, eller så får man ta mätaren utomhus. Nackdelen med en sådan mätare är att den annars kan visa fel, och det är inte bra om man vill undvika att bli smittad. Aranet4 och de Dostmann som är nämnda ovan behöver inte frisk luft, utan håller sin kalibrering utan sådant. Det känns tryggare t ex om man har mätaren i en lokal som inte vädras helt ut varje dygn eller där folk finns dygnet runt som t ex i ett hem. Det handlar ju också om att undvika smitta här, inte undvika ont i huvudet pga lite muggig luft, så man vill ju att mätaren alltid visar någorlunda rätt.

![TFA mini, högst upp, Moes FB-CO2, nedanför](https://raw.githubusercontent.com/co2koll/co2koll.github.io/master/kalib.jpeg)


Det finns 3 gånger mer utandningsluft i lokalen än vad den undre koldioxidmätaren visar. Problemet för den undre mätaren, en Moes FB-CO2, är att den behöver genomventilering varje dygn för att inte tappa sin orientering om hur mycket koldioxid som finns i luften. Den övre koldioxidmätaren, en TFA Dostmann mini, har intern stabil kalibrering. Båda kostar runt 800kr.
FB-CO2 är bra på andra sätt, batteri, Wi-Fi och Tuya IoT, men måste vädras varje dygn!


## Jag vill posta mätningar på webben

Det finns några sajter som publicerar mätningar på karta. Men oklart hur uppdaterade mätningarna är.

* <https://co2trackers.com/home>

För att integrera en CO2-mätare som kör Tuya med Home Assistant, se instruktioner här, testat och fungerar med Moes FB-CO2 <https://www.home-assistant.io/integrations/tuya/>

För en ren gör-det-själv-lösning med att publicera ett diagram på Mastodon från en TFA Dostmann Mini, se t ex <https://github.com/co2koll/tfa-airco2ntrol-mini> .


## Jag är totalnörd och vill bygga ihop prylar

En plattform som verkar populär är ESP32. 

Några länkar till att mäta från olika CO2-sensorer, som Aranet4, TFA Dostmann m fl. Också länkar till sensorer, kort med mera. Ursäkta röran.

* <https://github.com/kasparsd/sensor-pilot>
* <https://github.com/Anrijs/Aranet4-Python>
* <https://gitlab.com/webthings/co2-monitor-adapter>
* <https://github.com/MathieuSchopfer/tfa-airco2ntrol-mini>
* <https://github.com/schinken/esp8266-co2monitor>
* <https://www.hackerspace-bamberg.de/Co2_Monitor>
* <https://www.sherbers.de/monitor-co2-concentration-over-time-with-elasticsearch/>
* <https://github.com/koenvervloesem/ESPHome-Air-Quality-Monitor>
* <https://github.com/unparagoned/cloudtuya>
* <https://github.com/PaulAnnekov/tuyaha>
* <https://github.com/nalajcie/tuya-sign-hacking>
* <https://iotdesignpro.com/projects/iot-based-smart-energy-meter>
* <https://hackaday.io/project/5301-reverse-engineering-a-low-cost-usb-co-monitor/log/17909-all-your-base-are-belong-to-us>
* <https://github.com/maddindeiss/co2-monitor>
* <https://github.com/heinemml/CO2Meter>
* <https://github.com/vshmoylov/libholtekco2>
* <https://github.com/lnicola/co2mon>
* <https://gitlab.com/nobodyinperson/co2monitor>
* <https://chrpaul.de/2020/02/carbon-dioxide-monitor.html>
* <https://www.mouser.se/new/sensirion/sensirion-scd40/>
* <https://www.fierceelectronics.com/components/co2-sensor-accurate-without-self-calibration>
* <https://breathesafeair.com/carbon-dioxide-monitors/#Manual_Recalibration>
* <https://foosel.net/blog/2022-01-03-tfa-dostmann-meets-esphome/>
* <https://www.printables.com/model/119968-airco2ntrol-mini-backplate-with-wemos-d1-mini/comments>
* <https://www.co2.click/ecommerce/en/Model-C.html>
* <https://www.cnx-software.com/2022/06/27/esp32-board-with-150mbps-4g-lte-modem-also-supports-rs485-can-bus-and-relay-expansion/>

------

