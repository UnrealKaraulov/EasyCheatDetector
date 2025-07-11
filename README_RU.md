<div align="center">
  
# 🛡️ Easy Cheat Detector
**Программа сканирования ПК игроков на наличие читов**

![Превью](https://github.com/UnrealKaraulov/EasyCheatDetector/blob/main/ru_anim.gif)

[**English**](README.md#english) | [**Русский**](#russian)

</div>

<a id="russian"></a>
## 💻 Что это?
Easy Cheat Detector (ECD) - программа для сканирования компьютеров игроков на наличие запрещённых программ и модификаций (читы) для игр.

## 🔒 Безопасность
- Программа не обрабатывает и не отправляет персональные данные пользователей
- Все передаваемые данные шифруются (AES-256 + RSA-2048 + XOR)
- Используется защищённое соединение HTTPS

## 📋 Отправляемые данные
1. Запущенные процессы
2. Загруженные модули
3. Активные драйверы
4. Следы читов (установка/запуск/загрузка)
5. SteamID и частичный IP
- Первые 3 пункта удаляются через 24 часа

## 🎮 Поддерживаемые игры
- Counter-Strike 1.6 / CS ZERO
- Minecraft
- CS2
- CS:Source
- RUST (в разработке)

## 📊 Эффективность обнаружения
| Игра | Обнаружение | Статус |
|------|-------------|--------|
| CS 1.6 | 99% | ✅ |
| Minecraft | 60% | ⚠️ |
| CS2 | 30% | ⚠️ |
| CS:Source | 20% | ⚠️ |
| RUST | 0% | ❌ |

## 📥 Загрузки
| Файл | Назначение |
|------|------------|
| [EasyCheatDetector.exe](https://github.com/UnrealKaraulov/EasyCheatDetector/raw/main/EasyCheatDetector.exe) | Основной сканер |
| [EasyCheatViewer.exe](https://github.com/UnrealKaraulov/EasyCheatDetector/raw/main/EasyCheatViewer_x64.exe) | Просмотр отчётов |

## 👥 Разработчики
- **Karaulov**: разработчик программы и базы читов
- **SKAJIbnEJIb**: разработчик сайта, веб-части кода и плагинов

## 🛠️ Поддержка
Нашли необнаруженный чит? Сообщите:
- Telegram: [@karaul0v](https://t.me/karaul0v)  
- Почта: [karaulov@fungun.net](mailto:karaulov@fungun.net)  
- Форум: [https://forum.fungun.net](https://forum.fungun.net)  

<div align="center">
  
[🌐 Официальный сайт](https://fungun.net/ecd/)  
</div>

<!-- 
  Примечание:
  - Предыдущая версия "UnrealCheatFinder" не поддерживается
  - ECD не связан с UnrealDemoScanner
-->
