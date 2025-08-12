# Power-Distribution-Board
The code for the custom power distribution board in the Avanti Office.

What this project does
This project is a 16 port remote controlled individually addressable 600W dual power supply, used to power 12 nvidia jetson orin nanos and 3 nvidia orin AGX computers on the server rack in the office. The 2 8 way relays and ws2812b leds for each DC port is controlled by a luckfox rv1106 connected serially through a txs0108e level shifter to an arduino nano. This project uses python flask to incorporate a web remote so users can simply type in the IP of the rv1106 and control the system. 
