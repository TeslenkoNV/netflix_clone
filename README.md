Клон Netflix

## Описание
Этот проект представляет собой клон Netflix, созданный с использованием TypeScript, React и Next.js. В проекте реализована аутентификация пользователей с помощью NextAuth, стилизация интерфейса выполнена с помощью Tailwind CSS, а данные хранятся в базе данных, управляемой Prisma и MongoDB.

## Технологии
- TypeScript
- React
- Tailwind CSS
- Next.js
- Prisma
- MongoDB
- NextAuth

## Установка и запуск

1. Клонируйте репозиторий:
    ```bash
    git clone https://github.com/TeslenkoNV/netflix_clone
    ```

2. Перейдите в директорию проекта:
    ```bash
    cd netflix_clone
    ```

3. Установите зависимости:
    ```bash
    npm install
    ```

4. Настройте переменные окружения. Создайте файл `.env.local` в корне проекта и добавьте ваши переменные окружения:
    ```env
    MONGODB_URI=your-mongodb-uri
    NEXTAUTH_SECRET=your-nextauth-secret
    ```

5. Запустите проект:
    ```bash
    npm run dev
    ```

6. Откройте браузер и перейдите по адресу [http://localhost:3000](http://localhost:3000) для просмотра приложения.

## Ссылки
- [Демонстрация]()
- [Код проекта на GitHub](https://github.com/TeslenkoNV/netflix_clone)
