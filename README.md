### Для работы используется стенд который был сделан в 3й практике, сетевой обмен между машинами и установленный сервер с агентом вазух.
![image](https://github.com/user-attachments/assets/c21d0b2a-abf6-46b7-9127-706a5362a5cf)
![image](https://github.com/user-attachments/assets/35d418f6-9c1b-43e1-b0b1-c501205ab5cb)
### на агента грузим suricata  
![image](https://github.com/user-attachments/assets/be73af91-dca4-4cdf-a287-919593e2c545)
### загружаем правила на suricata
![image](https://github.com/user-attachments/assets/5b454821-dd00-40c7-8351-a0f91fd61587)
### настраиваю конфиг suricata
![image](https://github.com/user-attachments/assets/60888980-2cf4-4f43-b861-e574f452295d)
![image](https://github.com/user-attachments/assets/c88aa031-9ef3-4bfd-bbe3-8190cefa1e91)

### после настройки suricata внесем пути логов в /var/ossec/etc/ossec.conf
![image](https://github.com/user-attachments/assets/a7e656e5-488a-400d-b1ec-02968316a30c)
### проверка suricata
![image](https://github.com/user-attachments/assets/aca4247a-3040-4ad8-b6c0-977f30a4d73d)
### запускаем установленный ранее apache
![image](https://github.com/user-attachments/assets/57160743-3d8b-4457-8064-5c1c6e806cab)

### установка сканера nikto и язык программирования perl
![image](https://github.com/user-attachments/assets/401388be-924e-4213-bf38-899b4e69ef2d)
![image](https://github.com/user-attachments/assets/ddcc6d27-70ea-44f2-a6d5-8db8a10dfeae)
### результат сканирования 
![image](https://github.com/user-attachments/assets/72431a22-4741-4334-ab93-eeafc09cdfa1)

### установка threat hunting tools Yara
![image](https://github.com/user-attachments/assets/33e56919-3352-42f9-a1a6-4ef01f0ee03d)
![image](https://github.com/user-attachments/assets/2ebe43e0-7105-46b5-9ab7-755d85526f4f)
![image](https://github.com/user-attachments/assets/3ea10047-d196-43ef-b048-c4b43345f836)

### теперь создаем конфиг yara.sh и добавим правила в Wazuh
![image](https://github.com/user-attachments/assets/a820d32b-76e1-4e7e-95dc-d3fab4099c91)
![image](https://github.com/user-attachments/assets/bb9053bf-6830-4b09-bce5-01f3c157a30b)
### создаём скрипт malware_downloader.sh е для загрузки образцов вредоносного ПО
![image](https://github.com/user-attachments/assets/05faae63-4f8c-4484-9e1e-370fafbb154d)
### полученные логи на сервере 
![image](https://github.com/user-attachments/assets/79d581ec-20fd-47e3-8385-5393ed5b3cc4)









