# Сгенерируйте конфиг Cloudflare WARP для WireGuard за минуту
1. Заходим сюда https://shell.cloud.google.com/
2. Ставим галочку и идём дальше
![image](https://github.com/ImMALWARE/bash-warp-wireguard-generator/assets/53017160/d3eceb2a-4c99-48cd-bcd8-0258b726aa08)
3. Ждём, когда консоль прогрузится
4. Вставляем команду
```bash
curl -sSL https://raw.githubusercontent.com/ImMALWARE/bash-warp-wireguard-generator/main/warp_generator.sh | bash
```
5. Ждём, когда конфиг сгенерируется
6. Копируем конфиг, либо скачиваем файлом по ссылке и импортируем в WireGuard!👍
