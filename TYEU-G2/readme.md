Tuya TYEU-G2 swap WiFi module into ESP8266



TYEU-G2 Modified Tasmota Template

{"NAME":"TYEU-G2_Mod","GPIO":[32,1,7616,1,0,0,0,0,225,224,33,0,320,0],"FLAG":0,"BASE":18}

GPIO_00 =  0032 = Button-1  # left button
GPIO_01 =  0001 = User
GPIO_02 =  7616 = Heartbeat_i   # left-side middle LED
GPIO_03 =  0001 = User
GPIO_04 =  0000 = None
GPIO_05 =  0000 = None
GPIO_09 =  0000 = None
GPIO_10 =  0000 = None
GPIO_12 =  0225 = Relay-2
GPIO_13 =  0224 = Relay-1
GPIO_14 =  0033 = Button-2  # right button
GPIO_15 =  0000 = None
GPIO_16 =  0320 = Led_i-1   # left-side right LED
GPIO_17 =  0000 = None


{"NAME":"Generic","GPIO":[1,1472,1,1504,1,1,1,1,1,1,1,1,1,1],"FLAG":0,"BASE":18}


# Edge Led1 Led2 Led3    Led3 Led2 Led1  Edge
      RF433 GP02 GP16
      