# Covid-19 A Method that can Sanitize your Money (Work in progress...)

This project work on when .

## Components Used

### Hardware

### Software

1. VS Code (Arduino IDE Extension)

## Schematic

<img src=""></img>

## Result

## Code

```javascript
/*
* Author : Mohd Aman Ansari
* embed
* https://embed.org.in
*/
#include <LiquidCrystal.h>
 
#define rs 7 
#define en 6 
#define d4 2
#define d5 3  
#define d6 4 
#define d7 5 
// initialize the library with the numbers of the interface pins
LiquidCrystal lcd(rs, en, d4, d5, d6, d7);
 
void setup() 

{
   
  lcd.begin(16, 2);
  lcd.clear(); 
  lcd.setCursor(1,0); 
  lcd.print("Sanitizing Machine");
  delay(300); 

  lcd.setCursor(0,1);
  lcd.print("Covid 19"); 
 
  delay(5000); 
   
 
 }

 
void loop() 
 
 {
    
  lcd.begin(16, 2);
  lcd.clear(); 
  lcd.setCursor(1,0); 
  lcd.print("Sanitizing Machine");
  delay(300); 

  lcd.setCursor(0,1);
  lcd.print("Covid 19"); 
 
  delay(5000); 
 
 }

```
