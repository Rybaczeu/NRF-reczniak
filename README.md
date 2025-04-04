# 📻 NRF-ręczniak

**Podręczny node Meshtastic oparty na płytce FakeTec**  

Ten projekt to kompaktowy, energooszczędny moduł komunikacyjny oparty na mikroprocesorze Nordic Semiconductor oraz firmware Meshtastic. Idealny do użytku terenowego — niezależny od telefonu, z dodatkowymi funkcjami i czujnikami.

---

## 🔧 Z czego się składa?

- 🔌 **Płytka**: [FakeTec V4](https://github.com/gargomoma/fakeTec_pcb/issues/16#issue-2780231821)  
- 📡 **Moduł LoRa**: HT-RA62 lub RA-01SH  
- 🖥️ **Wyświetlacz OLED**: Różne warianty kolorystyczne  
- 🔋 **Akumulator**: LG MH1 18650 3200 mAh z zewnętrznym BMS  
  - Wersja **PRO** posiada dwa akumulatory  
- 🔘 **Enkoder obrotowy**: Do obsługi *Canned Messages* (predefiniowane wiadomości bez użycia telefonu)  
- 🔉 **Brzęczyk pasywny PWM**: Powiadomienia dźwiękowe, możliwość ustawienia melodyjek  
- 🌡️ **Czujniki AHT20 + BMP280** (tylko w wersji PRO): Pomiar temperatury, wilgotności i ciśnienia  
- 📶 **Antena**: Gizont 167 mm (SWR ~1.0–1.3)

---

## 🔋 Czas pracy i funkcjonalności

- Moduł na pojedynczym akumulatorze działa bezproblemowo przez **12+ dni**, a wersja **PRO** nawet **24+ dni**  
- Zmodyfikowana antena Bluetooth (30 mm drucik) zapewnia stabilne połączenie z aplikacją  
- Enkoder umożliwia nawigację po menu *Canned Messages*, co pozwala na szybką i niezależną komunikację  
- Brzęczyk sygnalizuje nowe wiadomości — możesz zaprogramować własne dźwięki dzięki obsłudze PWM  
- Czujniki środowiskowe (AHT20 + BMP280) rejestrują aktualne dane pogodowe w okolicy

---

## 📸 Zdjęcia

<p float="left">
  <img src="https://github.com/user-attachments/assets/b9798a35-5fb6-4e54-90b2-8c28fe8425ec" alt="NRF-ręczniak - widok 1" width="30%" />
  <img src="https://github.com/user-attachments/assets/3ff9ce18-3de3-4c27-901f-67a4434ba50b" alt="NRF-ręczniak - widok 2" width="30%" />
  <img src="https://github.com/user-attachments/assets/b4d851e5-690a-4d46-85b7-ccf205c1c074" alt="NRF-ręczniak - widok 3" width="30%" />
</p>
---

## 🔌 Ładowanie

Moduł ładowany jest przez port **USB-C**, z maksymalnym prądem ładowania wynoszącym **500 mA**.

---

## 🛠️ TODO

- 🔧 Stacja ładująca ze złączem magnetycznym, umożliwiająca ładowanie akumulatora prądem do **3 A**
