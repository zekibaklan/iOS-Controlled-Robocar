## iOS-Controlled-Robocar
# ***Control From iOS to Robocar With Use Firebase Realtime Database and Run STM32F103C8T6 Microcontroller***
**Projenin Amacı**

STM32 kartı kullanarak UI(User Interface) ile donanımın haberleşmesini sağlayan bir uygulama geliştirmektir. 
Realtime Database kullanılacak olup veri gönderme işlemi Swift ile,veri çekme işlemi NodemCU üzerinden gerçekleşecektir. 
Donanım kısmında C,UI için Swift kullanılacak olup,
STM32 – NodemCU haberleşmesi için C ile kod yazmak üzere,
UI – Firebase haberleşmesi için Swift ile Firebase tanımlaması yapılmıştır 
STM32 - donanım haberleşmesi için UART bağlantısı yapılacak ve UI üzerinde tanımlanan yönler ile robocarın yönü  ve ışıkları kontrol edilecektir.
Engel gördüğünde duracaktır.

**UP BUTTON**: UI üzerinden robotun ileri yönde gitmesini sağlar.<br />
**DOWN BUTTON**: Robotun geri yönde gitmesini sağlar.<br />
**LEFT BUTTON**: Robotun sol’a dönmesini sağlar.<br />
**RIGHT BUTTON**: Robotun sağ’a dönmesini sağlar.<br />
**FLASH BUTTON**: Robotun anlık ışıkları aç-kapat fonksiyonu(Sellector) çalışır.<br />
![banner resmi](https://r.resimlink.com/iGwcT3WZ8Ms.png)<br /><br />

**Bağlantı Şeması**
![banner resmi](https://r.resimlink.com/QDgOzR.png)<br /><br />





