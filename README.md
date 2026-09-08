# Guess Word

A simple and fun word guessing game.

## 🎮 Play

**Play Online:**

- [https://guoxue.moosasa.com](https://guoxue.moosasa.com)

## ✨ Features

* 30 random questions per game
* Simple left / right answer selection
* Score tracking
* Weekly ranking
* Sound effects and background music
* Mobile-friendly
* Supports multiple languages

## 📁 Project Structure

```text
guess-word/
├── assets/
│   ├── audio/
│   │   ├── bgm.mp3
│   │   ├── click.mp3
│   │   ├── correct.mp3
│   │   ├── wrong.mp3
│   │   └── complete.mp3
│   │
│   ├── scenes/
│   │   ├── home.scene
│   │   ├── game.scene
│   │   ├── result.scene
│   │   ├── complete.scene
│   │   └── rank.scene
│   │
│   └── scripts/
│       ├── component/
│       │   └── choose_btn.ts
│       │
│       ├── controller/
│       │   ├── home_controller.ts
│       │   ├── game_controller.ts
│       │   ├── result_controller.ts
│       │   ├── complete_controller.ts
│       │   └── rank_controller.ts
│       │
│       ├── manager/
│       │   ├── game_manager.ts
│       │   ├── audio_manager.ts
│       │   ├── i18n_manager.ts
│       │   ├── ad_manager.ts
│       │   ├── toast_manager.ts
│       │   └── storage_manager.ts
│       │
│       ├── model/
│       │   ├── game_result.ts
│       │   └── question.ts
│       │
│       ├── data/
│       │   └── question_data.ts
│       │
│       └── service/
│           ├── api_client.ts
│           └── game_service.ts
│
├── settings/
├── package.json
└── README.md
```

### Client

```text
Controller
    ↓
Manager
    ↓
Service
    ↓
ApiClient
```

## 🛠 Tech Stack

* Cocos Creator 3.8
* TypeScript
* HTML5
* REST API
* Google Analytics 4
* Google AdSense

## 🌍 Languages

* 繁體中文
* 简体中文

## 📸 Screenshots

### Home

<img src="screenshots/home.png" width="280">

### Game

<img src="screenshots/game.png" width="280">

### Result

<img src="screenshots/result.png" width="280">

### Complete

<img src="screenshots/complete.png" width="280">

### Ranking

<img src="screenshots/rank.png" width="280">

## 📱 Platform

* Mobile Web
* Desktop Web

## 📄 License

Private project.
