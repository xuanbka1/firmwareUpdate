# firmwareUpdate use mqtt

firmware:https://raw.githubusercontent.com/xuanbka1/firmwareUpdate/main/ver_ping.bin

firmware:https://raw.githubusercontent.com/xuanbka1/firmwareUpdate/main/FASE_V1A000.bin


+version V1A0000 + xem commit version của bản này

topic pub: 


payment/server/deviceID/debug


topic sub:


payment/device/deviceID/debug


Phiên bản đang sử dụng: FASE, LTE/4G fallback 2G. support GNSS

**+ topic publish**
payment/device/%s/ping

payment/device/%s/cash

payment/device/%s/response

payment/device/%s/qr

payment/device/%s/config

payment/device/%s/debug

**+ topic subcribes**

payment/server/%s/ping

payment/server/%s/qr

payment/server/%s/control

payment/server/%s/update

payment/server/%s/config

payment/server/%s/debug


