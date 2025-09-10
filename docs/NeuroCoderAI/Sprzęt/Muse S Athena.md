#### **I) Sprzęt:**

Muse S Athena** (ten model jest dostępny dla EU):  
[https://eu.choosemuse.com/products/muse-s-athena?variant=54629657248079](https://eu.choosemuse.com/products/muse-s-athena?variant=54629657248079 "https://eu.choosemuse.com/products/muse-s-athena?variant=54629657248079")

- dongle (jeśli korzystamy z Windowsa do analizy pomiarów):  
[https://pl.farnell.com/silicon-labs/bled112-v1/bluetooth-module-v4-0-91dbm/dp/2930668?gross_price=true&utm_source=chatgpt.com](https://pl.farnell.com/silicon-labs/bled112-v1/bluetooth-module-v4-0-91dbm/dp/2930668?gross_price=true&utm_source=chatgpt.com "https://pl.farnell.com/silicon-labs/bled112-v1/bluetooth-module-v4-0-91dbm/dp/2930668?gross_price=true&utm_source=chatgpt.com")
Czyli V1 z obsługą BLE i BGAPI (Interfejsy USB Host - emulacja portu Virtual COM)

#### **II) Software:**

a) Formularz aplikacji do SDK Muse:  
[https://choosemuse.com/pages/developers](https://choosemuse.com/pages/developers "https://choosemuse.com/pages/developers")  
Jest to jedna z opcji dostania się do danych (ale tylko przez iOS/Android).

b) Można skorzystać też z darmowych narzędzi działających na Windows, Linux lub nawet MacOS (jest wsparcie dla Muse S ale nie jestem pewna co do wsparcia dla Muse S Athena - choć powinny być kompatybilne):  
- BlueMuse → potrzebny do utworzenia strumienia LSL (w Windows):  
[https://github.com/kowalej/BlueMuse](https://github.com/kowalej/BlueMuse "https://github.com/kowalej/bluemuse")  
- LabRecorder → do zapisu danych EEG do pliku:  
[https://github.com/labstreaminglayer/App-LabRecorder](https://github.com/labstreaminglayer/App-LabRecorder "https://github.com/labstreaminglayer/app-labrecorder")  
- pylsl → opcjonalny — jeśli chcemy sterować eksperymentem, odbierać dane 'w kodzie':  
[https://github.com/labstreaminglayer/pylsl/tree/main/src/pylsl/examples](https://github.com/labstreaminglayer/pylsl/tree/main/src/pylsl/examples "https://github.com/labstreaminglayer/pylsl/tree/main/src/pylsl/examples")

Instrukcja jak to działa (BlueMuse, pylsl):  
[https://medium.com/@yang.zhao_22068/viewing-your-brain-with-muse-8f1584de00ad](https://medium.com/@yang.zhao_22068/viewing-your-brain-with-muse-8f1584de00ad "https://medium.com/@yang.zhao_22068/viewing-your-brain-with-muse-8f1584de00ad")

c) Ewentualnie prostsza, lekko płatna (73 zł) apka/alternatywa do dostania się do surowych danych eeg (ale tylko na urządzenia mobilne) - na pewno wspiera Muse S i Muse S Athena:  
https://mind-monitor.com/
https://mind-monitor.com/FAQ.php#footnote-optics

#### **III) Zastosowania:**   
Można stosować nie tylko w badaniach snu i relaksacji ale także radzi sobie przy np. BCI/neurofedbacku i innych badaniach, i sensor fNIRS daje sporo możliwości
