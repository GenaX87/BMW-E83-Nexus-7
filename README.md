# BMW-E83-Nexus-7
Nexus 7 используется как компьютер в BMW X3 (E83) с установленой "Тимуровской" прошивкой на основе Android 4.2.2 (4.2.2 cm-10.1-20130817-USBROM). Она хороша своим PowerEventManager позволяющая уводить планшет в сон при пропадании питания на USB. В планшет (вместо батареи) был встроен понижающий DC 3A преобразователь. Он (mini 3A DC-DC LM2596S) оказался совсем маленьким и почти не греющимся. Его я использовал так же для питания хаба. Планшет питается постоянно и в режиме сна (Firm sleep) почти ничего не потребляет.

Плата Arduino Pro Micro умеет "прикидываться" клавиатурой в Android. Что позволяет эмулировать кнопки плеера Android. Из iBUS BMW сигналы на Arduino поступают при помощи микросхемы L9637D.

#### Фото
![BMW E83 Nexus 7](https://raw.github.com/phpscriptru/BMW-E83-Nexus-7/master/Foto.jpg)

## Installation

Unpack libraries to C:\Users\"some_user"\Documents\Arduino\libraries
