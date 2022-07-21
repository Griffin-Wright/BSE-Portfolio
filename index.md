# Gesture Controlled Car

Over 2 and a half weeks, I built a car that could recieve information from a breadboard on my hand through bluetooth, using this given rotation information to move in different directions. It also includes a screen which could show distance and rotation information, an ultrasonic sensor that can sense walls in front of the car, 4 motors and many other parts.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Griffin W. | Success Academy HSLA | Electrical Engineering or Math | Sophomore


![Grofin](https://user-images.githubusercontent.com/108823975/180269760-3946c0e1-f231-402c-8ecc-08f76032d647.jpeg)

# Final Milestone
My final milestone was somewhat bittersweet, as although I did finish the gesture controlled car, learning more about code than I had ever before, there were some unforseen issues that occured largely as a result of timing or more mechanical problems that prevented it from living up to my standards. The main issue was the wheels, which took 4+ hours to attatch, only to ultimately fail and prevent the car from fully functioning. Since the second milestone I spent a day attatching the new bluetooth sensors, which was difficult but eventually worked, and also attatching the wheels, which (as I've already with coding and problem solving, two skills that possibly weren't extremely present with me before.

<iframe width="560" height="315" src="https://www.youtube.com/embed/MorFOFMXimQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Second Milestone
My second Milestone didn't include much, as at this point I was still waiting for replacement Bluetooth modules to connect my motors to the gyro, but I did some work on fixing the gyro, ensuring it gave accurate information. Fixing the gyro involved a lot of messing around with the sensitivity of the axis, along with switching the directionality of it. Soon after this milestone a lot of the code got deleted due to an accidental crash, leading to a lot of it being rewritten and a few developments as a result. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/YAaq02JERwc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# First Milestone  
My first Milestone was hooking up the motors to the H-Bridge motor controller, along with developing basic code to recognize information sent in the Serial reader of the Arduino Uno. I set the motors up so that when I input a w command, they would all move forward, an s would move them back, an a would move them to the left and a d would move them to the right. This was likely the easiest portion of the project, but at this point it was still controlled from my computer, something that in the end I would have to change. I also set up the Arduino micro to a gyro an accelerometer, which would notice the information of distance and rotation and turn it into readable 'w', 's', 'a', or 'd' commands that would later be read by the Arduino Uno and send information to the motors.
<iframe width="560" height="315" src="https://www.youtube.com/embed/hU7XnTTD7rI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


# Bill of Materials:
  Note: Materials of base project, may not include modifications or some changes.
|:--:|:--:|:--:|:--:|:--:|:--:|
| **Part** | **Quantity** | **Description** | **Reference Designator** | **Cost** | **Website** |
|:--:|:--:|:--:|:--:|:--:|:--:|
| Robot Kit | 1 | Chassis, Battery Pack, DC Motors, Wheels, etc. | M1, M2 | 19.99 | [amazon](https://www.amazon.com/gp/product/B06VTP8XBQ)
|:--:|:--:|:--:|:--:|:--:|:--:|
| Bluetooth Module | 2 | Serial Communication | HC-05 | 19.98 | [amazon](https://www.amazon.com/HiLetgo-Wireless-Bluetooth-Transceiver-Arduino/dp/B071YJG8DR)
|:--:|:--:|:--:|:--:|:--:|:--:|
| Accelerometer | 1 | Measure Linear Acceleration Along Axis | ADXL345 | 13.59 | [amazon](https://www.amazon.com/Wishiot-ADXL345-Accelerometer-Inclination-Raspberry/dp/B09T6VJWNY/ref=sr_1_2_sspa?keywords=adxl345&qid=1656710211&sr=8-2-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFZUVlSVVZaVU1VOVgmZW5jcnlwdGVkSWQ9QTA0NjkxNTRLRzJVTjNOU1VHVzcmZW5jcnlwdGVkQWRJZD1BMDEwNTE1NzFPVFAxQzVINjdWMEgmd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)
|:--:|:--:|:--:|:--:|:--:|:--:|
| Arduino Uno | 1 | Microcontroller Board | R3 | 23.00 | [arduino](https://store.arduino.cc/products/arduino-uno-rev3)
|:--:|:--:|:--:|:--:|:--:|:--:|
| Arduino Micro | 1 | Microcontroller Board | R3 | 20.70 | [arduino](https://store.arduino.cc/products/arduino-micro)
|:--:|:--:|:--:|:--:|:--:|:--:|
| Jumper Wires | 1 | Connection Wires | N/A | 6.98 | [amazon](https://www.amazon.com/Elegoo-EL-CP-004-Multicolored-Breadboard-arduino/dp/B01EV70C78)
|:--:|:--:|:--:|:--:|:--:|:--:|
| Dual H Bridge | 1 | Control Direction of DC Motors | L298N | 6.99 | [amazon](https://www.amazon.com/Qunqi-Controller-Module-Stepper-Arduino/dp/B014KMHSW6/ref=asc_df_B014KMHSW6/?tag=hyprod-20&linkCode=df0&hvadid=167139094796&hvpos=&hvnetw=g&hvrand=13469222211329594770&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032008&hvtargid=pla-306436938191&psc=1)
|:--:|:--:|:--:|:--:|:--:|:--:|
| Breadboard | 1 | Build Circuits Without Soldering | N/A | 11.98 | [amazon](https://www.amazon.com/dp/B07DL13RZH/ref=redir_mobile_desktop?_encoding=UTF8&aaxitk=b163d500edcc33b8ecdb35867663512a&content-id=amzn1.sym.53aae2ac-0129-49a5-9c09-6530a9e11786%3Aamzn1.sym.53aae2ac-0129-49a5-9c09-6530a9e11786&hsa_cr_id=4991273630901&pd_rd_plhdr=t&pd_rd_r=e6730cd8-8e3e-463d-932b-2c49d394f510&pd_rd_w=jX1If&pd_rd_wg=pAAek&qid=1656710515&ref_=sbx_be_s_sparkle_mcd_asin_0_img&sr=1-1-a094db1c-5033-42c6-82a2-587d01f975e8)
|:--:|:--:|:--:|:--:|:--:|:--:|
| Resistors | 1 | Control Flow of Electrical Current | N/A | 10.99 | [amazon](https://www.amazon.com/BOJACK-Values-Resistor-Resistors-Assortment/dp/B08FD1XVL6/ref=sr_1_2_sspa?crid=27KYFJ2PLSL8G&keywords=resistor&qid=1656710541&s=industrial&sprefix=resist%2Cindustrial%2C143&sr=1-2-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUE1UTlIUDRJRElBSlomZW5jcnlwdGVkSWQ9QTA0ODQ1ODUyVzBGOEhZN1hJSVNPJmVuY3J5cHRlZEFkSWQ9QTAyMjA5NTdGT1c4RjFYSTkxNTUmd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

# Tools Required

|:--:|:--:|:--:|
| **Tool** | **Cost** | **Website**
|:--:|:--:|:--:|
| Soldering Iron | 15.99 | [amazon](https://www.amazon.com/Soldering-Kit-Temperature-Desoldering-Electronics/dp/B07GTGGLXN/ref=asc_df_B07GTGGLXN/?tag=hyprod-20&linkCode=df0&hvadid=241999416883&hvpos=&hvnetw=g&hvrand=137463208067721732&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9031525&hvtargid=pla-590653449503&psc=1)
| Screwdriver Kit | 6.99 | [amazon](https://www.amazon.com/Small-Screwdriver-Set-Mini-Magnetic/dp/B08RYXKJW9)

# Schematics
  Again, note that these are the Schematics for a gesture controlled car, not necessarily for mine with the included modifications.
![Schematics](https://user-images.githubusercontent.com/82551067/176963218-7c0eecbe-7689-48f5-b6ea-48579ae6fb1c.jpg)

# Code
```arduino
// this is the code for the Arduino Uno (Motors)
int motor1pin1 = 2;
int motor1pin2 = 3;
int motor2pin1 = 4;
int motor2pin2 = 5;
#include <SoftwareSerial.h>
#define tx 13
#define rx 12
SoftwareSerial configBt(rx, tx);
char c = ' ';
#define echoPin 7
#define trigPin 6
long duration; // variable for the duration of sound wave travel
int distance; // variable for the distance measurement
void forward() {
  digitalWrite(motor1pin1, LOW);
  digitalWrite(motor1pin2, HIGH);
  digitalWrite(motor2pin1, LOW);
  digitalWrite(motor2pin2, HIGH);
}
void backward() {
  digitalWrite(motor1pin1, HIGH);
  digitalWrite(motor1pin2, LOW);
  digitalWrite(motor2pin1, HIGH);
  digitalWrite(motor2pin2, LOW);
}
void right() {
  digitalWrite(motor1pin1, LOW);
  digitalWrite(motor1pin2, HIGH);
  digitalWrite(motor2pin1, HIGH);
  digitalWrite(motor2pin2, LOW);
}
void left() {
  digitalWrite(motor1pin1, HIGH);
  digitalWrite(motor1pin2, LOW);
  digitalWrite(motor2pin1, LOW);
  digitalWrite(motor2pin2, HIGH);
}
void stop() {
  digitalWrite(motor1pin1, LOW);
  digitalWrite(motor1pin2, LOW);
  digitalWrite(motor2pin1, LOW);
  digitalWrite(motor2pin2, LOW);
}
void setup() {
  pinMode(motor1pin1, OUTPUT);
  pinMode(motor1pin2, OUTPUT);
  pinMode(motor2pin1, OUTPUT);
  pinMode(motor2pin2, OUTPUT);
  Serial.begin(9600);
  configBt.begin(38400);
  pinMode(tx, OUTPUT);
  pinMode(rx, INPUT);
pinMode(trigPin, OUTPUT); // Sets the trigPin as an OUTPUT
pinMode(echoPin, INPUT); // Sets the echoPin as an INPUT
Serial.begin(9600); // // Serial Communication is starting with 9600 of baudrate speed
Serial.println("Ultrasonic Sensor HC-SR04 Test"); // print some text in Serial Monitor
Serial.println("with Arduino UNO R3");
}
void loop() {
  if (configBt.available() > 0) {
    c = configBt.read();
  }
  digitalWrite(trigPin, LOW);
  delayMicroseconds(2);
  digitalWrite(trigPin, HIGH);
  delayMicroseconds(10);
  digitalWrite(trigPin, LOW);
  duration = pulseIn(echoPin, HIGH);
  distance = duration * 0.034 / 2;
  Serial.print("Distance: ");
  Serial.print(distance);
  Serial.println(" cm");
  switch (c) {
    case 'w':
      if(distance<=25){
       if(distance>0){ 
       stop();
       }
       else{
        forward();
        delay(500);
        c = ' ';
       }
      break;
      }
      else{
        forward();
        delay(500);
        c = ' ';
      }
    case 'a':
      left();
      delay(100);
      c = ' ';
      break;
    case 's':
      backward();
      delay(500);
      c = ' ';
      break;
    case 'd':
      right();
      delay(100);
      c = ' ';
      break;
    default:
      stop();
  }
}
```

```arduino
// this is the code for the Arduino Micro (gyro)
#include <Wire.h>
#include <MPU6050.h>
MPU6050 mpu;
#include <LiquidCrystal_I2C.h>
//initialize the liquid crystal library
//the first parameter is the I2C address
//the second parameter is how many rows are on your screen
//the third parameter is how many columns are on your screen
LiquidCrystal_I2C lcd(0x27, 16, 2);
void setup() 
{
  Serial.begin(115200);
  Serial.println("Initialize MPU6050");
  while(!mpu.begin(MPU6050_SCALE_2000DPS, MPU6050_RANGE_2G))
  {
    Serial.println("Could not find a valid MPU6050 sensor, check wiring!");
    delay(500);
  }
  mpu.calibrateGyro();
  mpu.setThreshold(15);
  checkSettings();
  lcd.init();
  lcd.backlight();
  lcd.noAutoscroll();
  Serial1.begin(38400);
}
void checkSettings()
{
  Serial.println();
  
  Serial.print(" * Sleep Mode:        ");
  Serial.println(mpu.getSleepEnabled() ? "Enabled" : "Disabled");
  
  Serial.print(" * Clock Source:      ");
  switch(mpu.getClockSource())
  {
    case MPU6050_CLOCK_KEEP_RESET:     Serial.println("Stops the clock and keeps the timing generator in reset"); break;
    case MPU6050_CLOCK_EXTERNAL_19MHZ: Serial.println("PLL with external 19.2MHz reference"); break;
    case MPU6050_CLOCK_EXTERNAL_32KHZ: Serial.println("PLL with external 32.768kHz reference"); break;
    case MPU6050_CLOCK_PLL_ZGYRO:      Serial.println("PLL with Z axis gyroscope reference"); break;
    case MPU6050_CLOCK_PLL_YGYRO:      Serial.println("PLL with Y axis gyroscope reference"); break;
    case MPU6050_CLOCK_PLL_XGYRO:      Serial.println("PLL with X axis gyroscope reference"); break;
    case MPU6050_CLOCK_INTERNAL_8MHZ:  Serial.println("Internal 8MHz oscillator"); break;
  }
 Serial.print(" * Gyroscope:         ");
  switch(mpu.getScale())
  {
    case MPU6050_SCALE_2000DPS:        Serial.println("2000 dps"); break;
    case MPU6050_SCALE_1000DPS:        Serial.println("1000 dps"); break;
    case MPU6050_SCALE_500DPS:         Serial.println("500 dps"); break;
    case MPU6050_SCALE_250DPS:         Serial.println("250 dps"); break;
  } 
}
void loop()
{
  Vector rawGyro = mpu.readRawGyro();
  Vector normGyro = mpu.readNormalizeGyro();
  if(normGyro.YAxis>50){
    if(normGyro.YAxis>80){
    }
    else(Serial1.write("d"));
  }
  if(normGyro.YAxis<-50){
    if(normGyro.YAxis<-80){
    }
    else(Serial1.write("a"));
  }
  if(normGyro.XAxis>50){
    if(normGyro.XAxis>80){
    }
    else(Serial1.write("s"));
  }
  if(normGyro.XAxis<-50){
    if(normGyro.XAxis<-80){
    }
    else(Serial1.write("w"));
  }
    if(normGyro.YAxis>50){
    if(normGyro.YAxis>80){
    }
    else(Serial.write("d"));
  }
  if(normGyro.YAxis<-50){
    if(normGyro.YAxis<-80){
    }
    else(Serial.write("a"));
  }
  if(normGyro.XAxis>50){
    if(normGyro.XAxis>80){
    }
    else(Serial.write("s"));
  }
  if(normGyro.XAxis<-50){
    if(normGyro.XAxis<-80){
    }
    else(Serial.write("w"));
  }
  lcd.setCursor(0,0);
  lcd.print("X-Axis");
  lcd.print(normGyro.XAxis);
  lcd.setCursor(0,1);
  lcd.print("Y-Axis");
  lcd.print(normGyro.YAxis);
  delay(500);
  lcd.clear();
}
```

```arduino
// sets up the Bluetooth Module for the Uno
// This is for the Arduino Uno
// Set up the first bluetooth module

#include <SoftwareSerial.h>

#define tx 2
#define rx 3

SoftwareSerial configBt(rx, tx);

void setup()
{
  Serial.begin(38400);
  configBt.begin(38400);
  pinMode(tx, OUTPUT);
  pinMode(rx, INPUT);
}

void loop()
{
  if (configBt.available())
  {
    Serial.print((char)configBt.read());
  }
  if (Serial.available())
  {
    configBt.write(Serial.read());
  }
}
```

```arduino
// sets up the bluetooth for the micro
// This is for the Arduino Micro
// Set up the other bluetooth module

void setup()
{
  Serial.begin(38400);
  Serial1.begin(38400);
}

void loop()
{
  if (Serial1.available())
  {
    Serial.print((char)Serial1.read());
  }
  if (Serial.available())
  {
    Serial1.write(Serial.read());
  }
}
```
