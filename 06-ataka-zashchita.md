В части А я "Взломал" GRUB потому что на нем не стояло пароля и я поменял пароль на рут пользователя  это делается очень просто ! Прилагаю скриншоты 

<img width="722" height="101" alt="image" src="https://github.com/user-attachments/assets/16204bb5-8f5d-40f0-81c6-dbaa3c6ddc46" />
<img width="249" height="74" alt="image" src="https://github.com/user-attachments/assets/4e5a37db-6e2d-4b19-a05b-3ddeb107da0a" />
<img width="527" height="142" alt="image" src="https://github.com/user-attachments/assets/144b6554-5dbe-418d-80cd-a7eeba4ae058" />

Все это сработало потому что я не запоролил сам GRUB и он был абсолютно без защиты 

В Части Б я уже ставил защиту на GRUB. Прилагаю скриншоты 

<img width="1519" height="251" alt="image" src="https://github.com/user-attachments/assets/afd7e2bd-9c65-4d96-a298-2c7b9c2bea09" />
<img width="473" height="196" alt="image" src="https://github.com/user-attachments/assets/840bec3a-f85a-47e1-a0e4-8080f5f97cdf" />

На втором скриншоте видно что когда я зашел в файлы GRUB меня не пустило 

Пароль GRUB защищает от редактирования параметров запуска а не защищает от если извлекут диск и подключат к другой машине 
Потому что нужно защитить как загрузчик GRUB так и secure BOOT так и сам носитель 
