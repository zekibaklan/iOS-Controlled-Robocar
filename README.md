# iOS-Controlled-Robocar
Control from iOS to Robocar with use Firebase database and run STM32F103C8T6 microcontroller

Projenin Amacı

STM32 kartı kullanarak UI(User Interface) ile donanımın haberleşmesini sağlayan bir uygulama geliştirmektir. 
Realtime Database kullanılacak olup veri gönderme işlemi Swift ile,veri çekme işlemi NodemCU üzerinden gerçekleşecektir. 
Donanım kısmında C,UI için Swift kullanılacak olup,
STM32 – NodemCU haberleşmesi için C ile kod yazmak üzere,
UI – Firebase haberleşmesi için Swift ile Firebase tanımlaması yapılmıştır 
STM32 - donanım haberleşmesi için UART bağlantısı yapılacak ve UI üzerinde tanımlanan yönler ile robocarın yönü  ve ışıkları kontrol edilecektir.
