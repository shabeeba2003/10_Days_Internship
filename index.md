#DAY 2 

##EXPERIMENT 1 BLINK OF LED

![LED](https://github.com/shabeeba2003/10_Days_Internship/blob/main/img/day2exp1led.png)

##EXPIRIMENT 2 BLINK OF SWITCH LED

![LED](https://github.com/shabeeba2003/10_Days_Internship/blob/main/img/day2%20exp2%20led.png)
---

#DAY 3

##EXPERIMENT 1 BLINK OF LED

[tinker this](https://www.tinkercad.com/things/ibIIrtEel17-frantic-uusam/editel)
---

##EXPERIMENT 2 POWER SUPPLY OF LED

[tinker this](https://www.tinkercad.com/things/8exKWYeaVAz-brave-snaget-turing/editel)
---

##EXPERIMENT 3 ARDUINO OF LED

##Program

// C++ code
//
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}

[tinker thiS](https://www.tinkercad.com/things/jU45JyGHF9G-cool-lappi-krunk/editel?tenant=circuits)
---

##EXPIREMENT 4  TWO LED OF ARDUINO

#PROGRAM

// C++ code
//
void setup()
{
  pinMode(12/13, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  digitalWrite(12, LOW);
  delay(500); // Wait for 1000 millisecond(s)
  digitalWrite(13, LOW);
  digitalWrite(12, HIGH);
  delay(500); // Wait for 1000 millisecond(s)
}

[tinker this](https://www.tinkercad.com/things/7h6tVYaHo2l-funky-juttuli/editel)
---

##EXPIREMENT 5 FOUR DANCING LED

#PROGRAM

// C++ code
//
void setup()
{
  pinMode(13/12/7/8, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  digitalWrite(12, LOW);
  digitalWrite(7, LOW);
  digitalWrite(8, LOW);
  delay(500); // Wait for 1000 millisecond(s)
  digitalWrite(12, HIGH);
  digitalWrite(7, LOW);
  digitalWrite(8, LOW);
  digitalWrite(13, LOW);
  digitalWrite(LED_BUILTIN, LOW);
  delay(500); // Wait for 1000 millisecond(s)
  digitalWrite(7, HIGH);
  digitalWrite(12, LOW);
  digitalWrite(8, LOW);
  digitalWrite(13, LOW);
  digitalWrite(LED_BUILTIN, LOW);
  delay(500); // Wait for 1000 millisecond(s)
  digitalWrite(8, HIGH);
  digitalWrite(12, LOW);
  digitalWrite(7, LOW);
  digitalWrite(13, LOW);
  digitalWrite(LED_BUILTIN, LOW);
  
}

[tinker this](https://www.tinkercad.com/things/l1jFiDOAu51-sizzling-snaget/editel)
---

#ASSIGNMENT

##7 SIGMENT LED

[TINKER THIS](https://www.tinkercad.com/things/cGJbMBO1Zdh-sizzling-hango-albar/editel?tenant=circuits)
---

#DAy 5

##EXPERIMENT 1

##ANALOG SIGNAL

#program

const int potpin =A0;
void setup()
{
  Serial.begin(9600);
}

void loop()
{
  int potValue=analogRead(potpin);
  Serial.println(potValue);
  delay(100); 
}

[tinker this](https://www.tinkercad.com/things/kHhyWzlLarm-shiny-vihelmo-hillar/editel)
---

##EXPERIMENT  2

##ARDUINO 7 SEGMENT LED

void setup()
{
  pinMode(8, OUTPUT);
  pinMode(7, OUTPUT); 
  pinMode(6, OUTPUT);
  pinMode(5, OUTPUT); 
  pinMode(4, OUTPUT);
  pinMode(3, OUTPUT); 
  pinMode(2, OUTPUT);
}
void loop()
{
 
  digitalWrite(3, HIGH);  
  digitalWrite(4, HIGH);  
  digitalWrite(2, LOW);
  digitalWrite(5, LOW);
  digitalWrite(6, LOW);
  digitalWrite(7, LOW);
  digitalWrite(8, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  
  digitalWrite(2, HIGH);  
  digitalWrite(3, HIGH);  
  digitalWrite(4, HIGH);  
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, HIGH);
  digitalWrite(8, LOW);
  delay(1000); // Wait for 1000 millisecond(s) 
  
  
  digitalWrite(2, HIGH);  
  digitalWrite(3, HIGH);  
  digitalWrite(4, LOW);  
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, LOW);
  digitalWrite(8, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)

  

  digitalWrite(2, HIGH);  
  digitalWrite(3, HIGH);  
  digitalWrite(4, HIGH);  
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, LOW);
  digitalWrite(8, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
               
  digitalWrite(2, HIGH);  
  digitalWrite(3, LOW);  
  digitalWrite(4, LOW);  
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  
  digitalWrite(2, HIGH);  
  digitalWrite(3, HIGH);  
  digitalWrite(4, LOW);  
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, LOW);
  digitalWrite(8, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  
  digitalWrite(2, LOW);  
  digitalWrite(3, LOW);  
  digitalWrite(4, LOW);  
  digitalWrite(5, HIGH);
  digitalWrite(6, LOW);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  
  digitalWrite(2, HIGH);  
  digitalWrite(3, LOW);  
  digitalWrite(4, HIGH);  
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  
  digitalWrite(2, HIGH);  
  digitalWrite(3, HIGH);  
  digitalWrite(4, HIGH);  
  digitalWrite(5, LOW);
  digitalWrite(6, LOW);
  digitalWrite(7, LOW);
  digitalWrite(8, LOW);
  delay(1000); // Wait for 1000 millisecond(s)

  

}

[tinker this](https://www.tinkercad.com/things/luEVQK6SoOx-copy-of-7seg-manual/editel?tenant=circuits)
---

#DAY 6

## 3D DESIGNING TO CAR

[tinker this](https://www.tinkercad.com/things/jfrPnuXCj14-spectacular-bigery/edit)
---

#DAY 7

##***ROBOTICS***
---

#DAY 8

##7 SEGMENT DISPLAY TO POTENTIOMETER

const int potpin =A0;
void setup()
{
  Serial.begin(9600);
  
  pinMode(8, OUTPUT);
  pinMode(7, OUTPUT); 
  pinMode(6, OUTPUT);
  pinMode(5, OUTPUT); 
  pinMode(4, OUTPUT);
  pinMode(3, OUTPUT); 
  pinMode(2, OUTPUT);
}

void loop()
{
  int potValue=analogRead(potpin);
  Serial.println(potValue);
  delay(100);
 
 
  digitalWrite(2, HIGH);  
  digitalWrite(3, HIGH);  
  digitalWrite(4, HIGH);  
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, HIGH);
  digitalWrite(8, LOW);
  delay(potValue); // Wait for 1000 millisecond(s) 
  
  
  
  digitalWrite(3, HIGH);  
  digitalWrite(4, HIGH);  
  digitalWrite(2, LOW);
  digitalWrite(5, LOW);
  digitalWrite(6, LOW);
  digitalWrite(7, LOW);
  digitalWrite(8, LOW);
  delay(potValue); // Wait for 1000 millisecond(s)   
 

  
  
  
  digitalWrite(2, HIGH);  
  digitalWrite(3, HIGH);  
  digitalWrite(4, LOW);  
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, LOW);
  digitalWrite(8, HIGH);
  delay(potValue); // Wait for 1000 millisecond(s)

  

  digitalWrite(2, HIGH);   
  digitalWrite(3, HIGH);  
  digitalWrite(4, HIGH);  
  digitalWrite(5, HIGH);
  digitalWrite(6, LOW);
  digitalWrite(7, LOW);
  digitalWrite(8, HIGH);
  delay(potValue); // Wait for 1000 millisecond(s)     
 
  
  
  digitalWrite(2, LOW);  
  digitalWrite(3, LOW);  
  digitalWrite(4, HIGH);  
  digitalWrite(5, LOW);
  digitalWrite(6, LOW);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  delay(potValue); // Wait for 1000 millisecond(s)
  
  
  digitalWrite(2, HIGH);  
  digitalWrite(3, LOW);  
  digitalWrite(4, HIGH);  
  digitalWrite(5, HIGH);
  digitalWrite(6, LOW);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
   delay(potValue); // Wait for 1000 millisecond(s)
  
  
  digitalWrite(2, HIGH);  
  digitalWrite(3, LOW);  
  digitalWrite(4, HIGH);  
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  delay(potValue); // Wait for 1000 millisecond(s)
  
  digitalWrite(2, HIGH);  
  digitalWrite(3, HIGH);  
  digitalWrite(4, HIGH);  
  digitalWrite(5, LOW);
  digitalWrite(6, LOW);
  digitalWrite(7, LOW);
  digitalWrite(8, LOW);
  delay(potValue); // Wait for 1000 millisecond(s)

  
  digitalWrite(2, HIGH);  
  digitalWrite(3, HIGH);  
  digitalWrite(4, HIGH);  
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  delay(potValue); // Wait for 1000 millisecond(s)
  
  
  digitalWrite(2, HIGH);  
  digitalWrite(3, HIGH);  
  digitalWrite(4, HIGH);  
  digitalWrite(5, HIGH);
  digitalWrite(6, LOW);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  delay(potValue); // Wait for 1000 millisecond(s)
  
}

 
 [tinker this](https://www.tinkercad.com/things/l40nhJ8Affp-brilliant-leelo/editel)]
 ---
