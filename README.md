# 4chan-relay-shield-arduino
How to interact with Ks0251 keyestudio 4-channel Relay Shield
## Links
https://wiki.keyestudio.com/Ks0251_keyestudio_4-channel_Relay_Shield
## Sample Code
```
/*
  DANCE OFF

  This is a HOW-TO for the 
  Ks0251 keyestudio 4-channel Relay Shield

  I believe they did not have the right
  sample to teach others. So I made this one.
  
*/
void setup() {
  pinMode(4, OUTPUT); // 4th Relay
  pinMode(5, OUTPUT); // 3rd Relay
  pinMode(6, OUTPUT); // 2nd Relay
  pinMode(7, OUTPUT); // 1st Relay
}

void loop() {
  // 4th Relay
  digitalWrite(4, HIGH); //   
  delay(100); //                       
  digitalWrite(4, LOW); //    
  delay(100); // 
  // 3rd Relay  
  digitalWrite(5, HIGH); //   
  delay(200); //                       
  digitalWrite(5, LOW); //    
  delay(200); // 
  // 2nd Relay
  digitalWrite(6, HIGH); //   
  delay(300); //                       
  digitalWrite(6, LOW); //    
  delay(300); // 
  // 1st Relay
  digitalWrite(7, HIGH); //   
  delay(400); //                       
  digitalWrite(7, LOW); //    
  delay(400); //                     
}

```
