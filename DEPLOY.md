# 🚀 Развертывание на Vercel

## Быстрый старт:

### 1. Зарегистрируйтесь на Vercel
- Перейдите на [vercel.com](https://vercel.com)
- Войдите через GitHub

### 2. Загрузите проект
- Нажмите "New Project"
- Импортируйте этот репозиторий
- Или загрузите ZIP файл

### 3. Настройте домен
- В настройках проекта → Domains
- Добавьте `unkly.wtf`
- Настройте DNS записи

## 🌐 Настройка DNS для unkly.wtf:

### Если домен на Cloudflare:
```
Type: CNAME
Name: @
Value: cname.vercel-dns.com
```

### Если домен на другом регистраторе:
```
Type: A
Name: @
Value: 76.76.19.61

Type: CNAME  
Name: www
Value: cname.vercel-dns.com
```

## 📁 Структура файлов:
```
/
├── index.html
├── script.js
├── style.css
├── vercel.json
└── assets/
    ├── discord.png
    ├── telegram.png
    └── ...
```

## ✅ После развертывания:
1. Сайт будет доступен по адресу: `https://your-project.vercel.app`
2. Добавьте домен `unkly.wtf` в настройках
3. Настройте DNS записи у регистратора домена
4. Готово! 🎉
