В данном задании я написал ваш скрипт который потом запускается как сервис вместе с системой, прилагаю 3 скриншота 

<img width="1290" height="101" alt="image" src="https://github.com/user-attachments/assets/bf7f96aa-3331-4648-9cf9-97547ada46fd" />
<img width="638" height="49" alt="image" src="https://github.com/user-attachments/assets/51d24a27-5337-45f3-b45c-3051a2407734" />
<img width="1548" height="285" alt="image" src="https://github.com/user-attachments/assets/13d39551-f876-4fd5-bf44-c768a2d77050" />

Затем после всего этого прилагаю скриншот статуса моей службы 

<img width="918" height="408" alt="image" src="https://github.com/user-attachments/assets/f3301a28-83bd-41fc-8434-43a08ffd7b83" />

Далее прилагаю содержимое лога после двух загрузок 

<img width="696" height="233" alt="image" src="https://github.com/user-attachments/assets/9fc3bfa0-ddae-4f35-afe3-9d338df551ce" />

Type=oneshot строга говорит как запускать службу юниту Строка WantedBy=multi-user.target говори куда прикрепить юнит для запуска 
