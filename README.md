# RAWA_CHIPER_V1
RAWA CIPHER V1 — это консольный шифратор сообщений, предназначенный для защиты личных переписок, заметок и текстовых данных с использованием криптографически стойких алгоритмов.// s a console-based message encryptor designed to protect personal correspondence, notes, and text data using cryptographically strong algorithms.
# RAWA CIPHER V1
Проект создан с упором на:

* Высокую скорость работы
* Надёжную криптографическую защиту
* Отсутствие логирования
* Простоту использования

---

## Возможности

* Шифрование текста по паролю
* Расшифровка только при вводе корректного пароля
* Защита от подмены данных
* Base64-формат для удобной передачи
* Поддержка Unicode
* Полностью оффлайн работа

---

## Используемые технологии

RAWA CIPHER V1 применяет современные криптографические стандарты:

* AES-256-GCM
* Scrypt (KDF)
* Base64

---

## Как работает шифрование

1. Пользователь вводит пароль
2. Генерируется случайная соль
3. Из пароля формируется ключ через Scrypt
4. Текст шифруется алгоритмом AES-256-GCM
5. Результат кодируется в Base64

Схема:

```
Текст + Пароль
      |
    Scrypt
      |
AES-256-GCM
      |
   Base64
      |
Зашифрованное сообщение
```

---

## Зависимости

* Python 3.9+
* cryptography
* colorama

Установка зависимости:

```bash
pip install cryptography
pip install colorama
```

---

## Установка

1. Установить Python
2. Установить зависимость
3. Скачать файл проекта
4. Запустить:

```bash
python RAWA_CHIPER_V1.py
```

---

## Лицензия

Свободное использование в образовательных и личных целях.
Автор не несёт ответственности за неправильное использование.

---

/////////////////////////////////////////////////////////////////

The project was created with an emphasis on:

* High-speed operation
* Reliable cryptographic protection
* Lack of logging
* Ease of use

---

## Features

* Text encryption by password
* Decryption only when entering the correct password
* Protection against data substitution
* Base64 format for convenient transmission
* Unicode support
* Completely offline operation

---

## Technologies used

RAWA CIPHER V1 applies modern cryptographic standards:

* AES-256-GCM
* Scrypt (KDF)
* Base64

---

## How encryption works

1. The user enters the password
2. A random salt is generated
3. A key is generated from the password via Scrypt
4. The text is encrypted using the AES-256-GCM algorithm.
5. The result is encoded in Base64

Scheme:

```
Text + Password
      |
    Scrypt
      |
AES-256-GCM
      |
   Base64
      |
Encrypted message
```

---

## Dependencies

* Python 3.9+
* cryptography
* colorama

Installing a dependency:

```bash
pip install cryptography
pip install colorama
```

---

## Installation

1. Install Python
2. Establish a dependency
3. Download the project file
4. Launch:

```bash
python RAWA_CHIPER_V1.py
```

---

## License

Free use for educational and personal purposes.
The author is not responsible for the misuse.

---
