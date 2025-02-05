# mini rack pdu
An inexpensive 10" rack mount AC power distribution unit with remote control and power monitoring via esp32. 
<p float="left">
  <img src="images/pdu_front.jpg" width="48%" />
  <img src="images/pdu_back.jpg" width="48%" />
</p>

Features
- Current Protection
- Current Monitoring
- Switchable Outlets (physical buttons and remote control)
- Web Interface
- Home Assistant Integration

To-Do
- [ ] Build
- [ ] Write software
  - [ ] Control logic
  - [ ] Web interface
  - [ ] API

BOM
- 8 panel mount outlets (<a >https://a.co/d/97mr5YT</a>)
- Power in C14 plug (https://a.co/d/73B9O7r)
- Main power switch/circuit breaker. (https://www.mouser.com/ProductDetail/562-736W-B-301)
- Relay board (https://a.co/d/4Hwa2Mm)
- Current measuring ACS758 (https://a.co/d/4qGEHbB)
- esp32 WT32-ETH01 (https://a.co/d/eftOV7s) (ethernet drawing https://www.huilyn.com/enus/detail_305_1887.html)
- I2c gpio extender (https://www.adafruit.com/product/5346)
- Push buttons (https://a.co/d/blETPMN)
- Leds
- Power board for esp32 and relays. (https://a.co/d/7kuPYSm)
- 3d printed case
