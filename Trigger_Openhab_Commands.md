Openhab 2:
http://openhab-fc.snowsd.com:8085/classicui/CMD?AlarmStatus_PondCamera=ON

Openhab 1:
http://openhab-fc.snowsd.com:8085/CMD?AlarmStatus_PondCamera=ON
http://openhab-fc.snowsd.com:8085/CMD?SwitchLivingRoom=OFF

(Tested and confirmed to work...)

Note - that motioneye only fires an "it happened" webhook - nothing to reset afterwards, so openhab will need to reset itself after a specified time period - ideally one that matches the motioneye motion timeout period.
