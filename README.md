# Caesar Cipher Encoder 🔐

This is a simple Python program that allows users to **encode** or **decode** messages using the classic **Caesar Cipher** encryption technique.

## 🧠 Features
- Encode messages using shift logic.
- Decode messages easily with the reverse shift.
- Handles spaces, symbols, and non-alphabet characters properly.
- Loop control: gives the option to rerun without restarting.
- Visual logo on startup for an enhanced CLI experience.

## 🚀 How It Works
The Caesar Cipher works by shifting each letter in the input text a certain number of places down or up the alphabet. This program lets users define that shift.

## 🧩 File Structure
- `main.py` – Main logic for user interaction and Caesar algorithm.
- `art.py` – Contains the ASCII logo displayed at the start of the program.
-  Clone the repo and run: python main.py

```bash
🔍 Preview
          
 ,adPPYba, ,adPPYYba,  ,adPPYba, ,adPPYba, ,adPPYYba, 8b,dPPYba,  
a8"     "" ""     `Y8 a8P_____88 I8[    "" ""     `Y8 88P'   "Y8  
8b         ,adPPPPP88 8PP"""""""  `"Y8ba,  ,adPPPPP88 88          
"8a,   ,aa 88,    ,88 "8b,   ,aa aa    ]8I 88,    ,88 88          
 `"Ybbd8"' `"8bbdP"Y8  `"Ybbd8"' `"YbbdP"' `"8bbdP"Y8 88   
            88             88                                 
           ""             88                                 
                          88                                 
 ,adPPYba, 88 8b,dPPYba,  88,dPPYba,   ,adPPYba, 8b,dPPYba,  
a8"     "" 88 88P'    "8a 88P'    "8a a8P_____88 88P'   "Y8  
8b         88 88       d8 88       88 8PP""""""" 88          
"8a,   ,aa 88 88b,   ,a8" 88       88 "8b,   ,aa 88          
 `"Ybbd8"' 88 88`YbbdP"'  88       88  `"Ybbd8"' 88          
              88                                             
              88           

Type 'encode' to encrypt, type 'decode' to decrypt:
> encode
Type your message:
> hello world
Type the shift number:
> 5
Here is the encoded result: mjqqt btwqi
