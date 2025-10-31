# TransliterateAI
A multilingual transliteration and OCR framework

TransliterateAI is a simple yet powerful project that identifies text from regional Indian languages and converts it into another script chosen by the user.  
The idea is to make it easier for travelers, drivers, and people visiting other states to read local signboards or information written in unfamiliar scripts.

---

Background
India is home to dozens of languages and writing systems.  
While this diversity is beautiful, it can be confusing for people who travel across states.  
Many drivers, tourists, or workers face difficulties reading local text because they can’t understand the script — even though they might understand the language when written in their own script.

The aim of this project is to solve that problem by reading the text (OCR) and showing it in a familiar script.

Example use cases:
- A driver from Andhra Pradesh can read Punjabi signboards in Telugu script.  
- A pilgrim from Kerala visiting Tirupati can read directions written in Malayalam script instead of Telugu.

---

Features
- Reads printed text from images using OCR  
- Supports multiple Indian scripts  
- Converts recognized text into another script (transliteration, not translation)  
- Lightweight and extendable framework  
- Can be connected to a simple frontend for testing  

---

Tech Stack
- Language: Python  
- Backend: FastAPI  
- OCR Engine: Tesseract  
- Libraries: Pillow, pytesseract, requests
- Frontend: Basic HTML and CSS (for testing)  

---

Project Phases:-
 1. OCR Setup | Basic OCR for Hindi and English |
 2. Multilingual OCR | Add more Indian languages |
 3. Transliteration | Build logic to map one script to another |
 4. UI Integration | Add simple upload and result interface |
 5. Testing | Measure accuracy with different scripts |
 6. AI Extension | Explore ML-based transliteration later |

---

License:-
This project is released under the **MIT License**.

---

Acknowledgements:-
- Tesseract OCR  
- FastAPI  
- Open-source contributors and datasets  

---

Author:-
Name: Shashank P
Email: yjmshashank16@gmail.com  



