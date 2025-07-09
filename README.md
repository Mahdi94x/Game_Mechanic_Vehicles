# Game_Mechanic_Vehicles

Developed with Unreal Engine 5.6.0

Based on the course Unreal Engine 5 Blueprints - The Ultimate Developer Course by Stephen Ulibarri  

This project demonstrates a fully functional Chaos Vehicle setup in Unreal Engine 5.4, featuring torque curves, animation blueprints, and player-driven input for controlling a physically simulated car.

## 📂 Project Structure  
/Vehicles  
  ├── Blueprints  
  │   └── BP_Vehicle (Main playable car)  
  ├── Wheels  
  │   ├── BP_FrontWheel  
  │   └── BP_RearWheel  
  ├── Animation  
  │   └── ABP_Vehicle (Animation blueprint using WheelController)  
  ├── Curves  
  │   └── FC_Torque (Torque curve asset)  
  ├── Input  
  │   ├── IMC_Vehicle (Input Mapping Context)  
  │   └── IA_* (Throttle, Steering, Brake, etc.)  

## 🎮 Features  
✅ Custom torque curve asset defining power delivery across RPMs.  
✅ Modular wheel blueprints for front and rear wheels.  
✅ Animation Blueprint using WheelController for real-time wheel animation.  

✅ Full input mapping (keyboard + gamepad):  
 - Throttle / Brake  
 - Steering  
 - Handbrake  
 - Mouse/Stick camera look

✅ Vehicle physics tuning:  
 - Chassis width, height, and center of mass  
 - Suspension visualization via speed bumps

✅ Easily swappable drive types (FWD / RWD / AWD)  
✅ Customizable transmission with gear ratio tuning  

## 🧩 Input Setup
All vehicle actions are handled using Enhanced Input System.  
Actions:  
 - IA_Throttle (W / Gamepad RT)
 - IA_Brake (S / Gamepad LT)
 - IA_Steering (A/D / Gamepad Left Stick)
 - IA_Look (Mouse / Gamepad Right Stick)
 - IA_Handbrake (Space / Gamepad Face Bottom)

## 📌 Requirements
Unreal Engine 5.0 or later  
PC or compatible gamepad for full input test  
Enhanced Input Plugin (Enabled by default in UE5.4)  
Chaos Vehicles UE plugin  
