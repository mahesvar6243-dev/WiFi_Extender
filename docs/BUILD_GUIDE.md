Components:

  1) ESP32 Module
  2) NRF24L01 x2
  3) 10uf capacitors x2
  4) connecting wires(as required)

Software Requirements:
   Arduino IDE

connections for the VSPI :

| nRF24L01 | ESP32            
| -------- | --------
| VCC      | 3.3V          
| GND      | GND               
| CE       | GPIO 4      
| CSN      | GPIO 5      
| SCK      | GPIO 18    
| MOSI     | GPIO 23   
| MISO     | GPIO 19   

| nRF24L01 | ESP32             
| -------- | --------
| VCC      | 3.3V
| GND      | GND       
| CE       | GPIO 16
| CSN      | GPIO 15
| SCK      | GPIO 14
| MOSI     | GPIO 13
| MISO     | GPIO 12



