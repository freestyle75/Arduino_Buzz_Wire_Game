#include <LiquidCrystal_I2C.h> 

LiquidCrystal_I2C lcd(0x27, 16, 2); 
const int buzzerPin = 2; 
const int winnigPin = 5;
void setup() {
  lcd.init();
  lcd.begin(16, 2); 
  pinMode(buzzerPin, INPUT);
  pinMode(winnigPin, INPUT);
}

void loop() {
lcd.setCursor(0, 0);
  lcd.print("Buzz.wire"); 
  lcd.setCursor(0, 1);
  lcd.print("good.luck");
  int buzzerState = digitalRead(buzzerPin); 
  int winnigState = digitalRead(winnigPin);
  if (buzzerState == HIGH) {
    lcd.clear();
    lcd.setCursor(0, 0);
    lcd.print("Failed"); 
    delay(500);
    lcd.clear();
    lcd.setCursor(0, 0);
    lcd.print("Keep going");   
    
  }
  if (winnigState == HIGH){
    lcd.clear();
    lcd.setCursor(0, 0);
    lcd.print("Well Done!"); 
    






  }
  
  delay(100); // Delay between readings to avoid flickering
}


