# GY-521 (MPU6050) Motion Sensor Module

A compact and user-friendly breakout board featuring the **MPU6050** sensor — a 6-DOF (Degrees of Freedom) motion tracking device combining a **3-axis accelerometer** and a **3-axis gyroscope**.

---

## 📦 What's Inside

- MPU6050 sensor (accelerometer + gyroscope)
- 3.3V Voltage regulator (e.g., HX9193-33)
- I2C pull-up resistors (SCL, SDA)
- Bypass capacitors for noise filtering
- Power indicator LED
- Breadboard-friendly header pins

---

## 📌 Key Features

- 6-axis motion sensing (linear + angular)
- I2C interface (SDA, SCL) for communication
- Operating voltage: 3.3V to 5V
- Default I2C address: `0x68` (or `0x69` with AD0 HIGH)
- Built-in power LED for quick debugging

---

## 📐 Pinout

| Pin  | Function                  |
|------|---------------------------|
| VCC  | Power input (3.3V–5V)     |
| GND  | Ground                    |
| SCL  | I2C clock line            |
| SDA  | I2C data line             |
| XDA  | Auxiliary I2C data (unused) |
| XCL  | Auxiliary I2C clock (unused)|
| AD0  | Address selector          |
| INT  | Interrupt output (optional)|

---

## 🔌 Connecting to Arduino Uno

| MPU6050 Pin | Arduino Uno Pin |
|-------------|------------------|
| VCC         | 5V               |
| GND         | GND              |
| SDA         | A4               |
| SCL         | A5               |

> ✅ *Note: Use 4.7kΩ pull-up resistors for SDA and SCL lines if not already included on the module.*

---

## 🧠 I2C Basics

- 2-wire protocol (SDA, SCL)
- Master-slave architecture
- Supports multiple devices on the same bus
- Speeds: Standard (100kHz), Fast (400kHz), High (3.4MHz)

---

## 🛠️ Applications

- 🤖 Robotics – balancing, motion sensing
- ✈️ Drones – orientation and flight control
- 🎮 Game Controllers – gesture input
- ⌚ Wearables – step counting, motion detection
- 📱 Smartphones – auto-rotate, UI interaction

---

## 📚 Resources

- [MPU6050 Datasheet (PDF)](https://invensense.tdk.com/wp-content/uploads/2015/02/MPU-6000-Datasheet1.pdf)
- [GY-521 Schematic (External)](https://www.electronicwings.com/nodemcu/mpu6050-interfacing-with-nodemcu)
- [I2C Protocol Basics (Tutorial)](https://learn.sparkfun.com/tutorials/i2c)

---

## ✅ License

MIT License — feel free to use, modify, and distribute.

---

## 🙋‍♀️ Author

**Sumaiya khan**  


