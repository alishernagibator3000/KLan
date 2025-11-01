# 🎮 Brick Shooter Game

Классическая аркадная игра, где нужно разбивать кирпичи мячом.  
Проект создан на Java с использованием JavaFX для изучения основ разработки игр.

<img width="1920" height="1080" alt="Снимок экрана (8)" src="https://github.com/user-attachments/assets/e57036e8-aed8-4fb9-a324-214733eba7bc" />
<img width="1920" height="1080" alt="Снимок экрана (9)" src="https://github.com/user-attachments/assets/728175f3-2599-4ff1-b843-7e7a2da7d2e3" />
<img width="1920" height="1080" alt="Снимок экрана (10)" src="https://github.com/user-attachments/assets/54016c38-ea8c-4f3d-95e3-c38b53422e31" />
<img width="1920" height="1080" alt="Снимок экрана (11)" src="https://github.com/user-attachments/assets/a2f84a94-8da5-4f67-aa53-5a4959b0a3e6" />
<img width="1920" height="1080" alt="Снимок экрана (12)" src="https://github.com/user-attachments/assets/1ba60fb5-921a-4c9e-b834-878d42f3166b" />
<img width="1920" height="1080" alt="Снимок экрана (13)" src="https://github.com/user-attachments/assets/639eb8ca-8bff-451d-a9c1-6d645c4fa0eb" />


---

## 👤 Автор

**Abakirov Alisher**
- Студент 2 курса IT & Business College, группы SCA-24A
- Курс: Operating Systems and Environments (OSE)

---

## ✨ Основные возможности

- 🎯 70 разноцветных кирпичей (7 рядов по 10 штук)
- 🖱️ Управление платформой мышью
- ⚽ Физика отскока мяча
- 💯 Подсчёт очков (+5 за каждый кирпич)
- ❤️ Три жизни
- 🏆 Экраны победы и поражения

---

## 🛠️ Технологии

- **Java 23**
- **JavaFX 17.0.6**
- **Maven 3.8.5**

---

## 📁 Структура проекта

```
BrickShooterGame/
├── src/
│   ├── main/
│   │   ├── java/com/example/brickshootergame/
│   │   │   ├── HelloApplication.java     # Запуск приложения
│   │   │   ├── GameController.java       # Логика игры
│   │   │   ├── GameObjects.java          # Игровые объекты
│   │   │   └── HelloController.java      # (не используется)
│   │   └── resources/
│   │       └── com/example/brickshootergame/
│   │           └── hello-view.fxml       # (не используется)
│   └── module-info.java                  # Модуль JavaFX
├── pom.xml                               # Конфигурация Maven
└── README.md
```

---

## 🎮 Управление

| Действие | Управление |
|----------|------------|
| Движение платформы | Движение мыши влево/вправо |
| Запуск мяча | Клик мыши |
| Старт игры | Кнопка "START GAME" |

---

## 🚀 Установка и запуск

### Требования

- Java 17 или выше
- JavaFX SDK
- IntelliJ IDEA (рекомендуется)

### Запуск

1. Откройте проект в IntelliJ IDEA
2. Перейдите в `File -> Project Structure -> Libraries`
3. Добавьте JavaFX SDK (нажмите `+` -> `Java` -> выберите путь к `javafx-sdk/lib`)
4. Откройте `HelloApplication.java`
5. Нажмите Run для запуска игры

---

## 🎯 Планы на будущее

- [ ] Добавить звуковые эффекты
- [ ] Добавить уровни сложности
- [ ] Сохранение рекордов
- [ ] Бонусы (расширение платформы, дополнительные жизни)
- [ ] Прочные кирпичи (несколько ударов для разрушения)
- [ ] Меню паузы

---

## 📄 Лицензия

Этот проект создан в образовательных целях.  
Вы можете свободно использовать и изменять его для обучения.

---

## 🎓 Что я узнал

В процессе работы над проектом я научился:
- Работать с JavaFX для создания игр
- Реализовывать физику движения и столкновений
- Использовать Timeline для игрового цикла
- Управлять состоянием игры
- Создавать эффекты частиц

---

**"Пожалуйста поставьте 100 баллов, Жениш агай :)
