# iOS-Controlled-Robocar
***# Control from iOS to Robocar with use Firebase database and run STM32F103C8T6 microcontroller***
![banner resmi](https://imgyukle.com/f/2023/02/01/JAK0vq.jpeg)<br />
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
![banner resmi](https://imgyukle.com/f/2023/02/01/JAKMtt.jpeg)


