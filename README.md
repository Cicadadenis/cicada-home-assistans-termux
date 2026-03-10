# Cicada Home Assistant в Termux

<p align="center">
  <img src="https://www.home-assistant.io/images/favicon-192x192.png" width="120" alt="Home Assistant">
  <br><br>
  <b>Полноценный Home Assistant прямо на Android без root через Termux + udocker</b>
</p>

## Что вы получите

- Home Assistant → доступен в браузере по адресу  
  **http://localhost:8123/**  
- Не требуется root  
- Не нужны сложные proot-дистрибутивы

## Требования

- Android 7.0+
- Termux (лучше с F-Droid)
- ≈ 2–3 ГБ свободного места
- Стабильный интернет на время первой установки

## Установка (6 команд)

```bash
# 1. Обновляем пакеты
pkg update && pkg upgrade -y

# 2. Ставим git
pkg install git -y

# 3. Скачиваем репозиторий
git clone https://github.com/Cicadadenis/cicada-home-assistans-termux.git

# 4. Заходим в папку
cd cicada-home-assistans-termux

# 5. Устанавливаем udocker
./install_udocker.sh

# 6. Запускаем установку и старт Home Assistant
./home-assistant.sh
```

- Дожидаемся когда пойдут строки зеленого цвета и после этого переходим по адресу
  **http://localhost:8123/**  
