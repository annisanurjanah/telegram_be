<br />
<p align="center">

  <h3 align="center">Telegram Application</h3>
  <p align="center">
    <image align="center" width="100" src='/images/telegramrest.jpg' />
  </p>
  <p align="center">
    <a href="#">View Demo</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Requirements](#requirements)
  - [Installation](#installation)
  - [Setup .env example](#setup-env-example)
- [Rest Api](#rest-api)
- [Contributing](#contributing)
- [Related Project](#related-project)
- [Contact](#contact)

<!-- ABOUT THE PROJECT -->

## About The Project

Telegram is a web-based chat application. This server can manage all functions and endpoints in the telegram application such as creating, adding, updating and deleting messages. Apart from private chat, this application also provides a group chat feature. Login authentication, register and get user profile information and can edit user profiles. This app is built using Socket.io, ReactJS, and ExpressJS.

### Built With

- [Node.js](https://nodejs.org/en/)
- [Express.js](https://expressjs.com/)
- [JSON Web Tokens](https://jwt.io/)
- and other

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

- [nodejs](https://nodejs.org/en/download/)

| Third Party    | npm install        |
| -------------- | ------------------ |
| [Express]      | npm i express      |
| [Nodemon]      | npm i nodemon      |
| [Morgan]       | npm i morgan       |
| [PostgresSQL]  | npm i pg           |
| [Dotenv]       | npm i dotenv       |
| [CORS]         | npm i cors         |
| [Eslint]       | npm i eslint       |
| [Http-errors]  | npm i http-errors  |
| [Helmet]       | npm i helmet       |
| [Bcryptjs]     | npm i bcryptjs     |
| [Multer]       | npm i multer       |
| [Uuid]         | npm i uuid         |
| [Jsonwebtoken] | npm i jsonwebtoken |
| [Socket.io]    | npm i socket.io    |

[express]: http://expressjs.com
[Nodemon]: https://www.npmjs.com/package/nodemon
[Morgan]: https://www.npmjs.com/package/morgan
[PostgresSQL]: https://node-postgres.com
[Dotenv]: https://www.npmjs.com/package/dotenv
[CORS]: https://www.npmjs.com/package/cors
[Eslint]: https://eslint.org
[Http-errors]: https://www.npmjs.com/package/http-errors
[Helmet]: https://helmetjs.github.io
[Bcryptjs]: https://www.npmjs.com/package/bcryptjs
[Multer]: https://www.npmjs.com/package/multer
[Uuid]: https://www.npmjs.com/package/uuid
[Jsonwebtoken]: https://www.npmjs.com/package/jsonwebtoken
[Socket.io]: https://www.npmjs.com/package/socket.io

### Requirements

- [Node.js](https://nodejs.org/en/)
- [Postman](https://www.getpostman.com/) for testing

### Installation

- Clone This Back End Repo

```
git clone https://github.com/Shaniara28/Telegram_be
```

- Go To Folder Repo

```
cd telegram-be
```

- Install Module

```
npm install
```

- <a href="#setup-env-example">Setup .env</a>
- Starting application

```npm run start:dev

```

### Setup .env example

Create .env file in your root project folder.

```env
# Postgre SQL Configuration
PGDATABASE
PGHOST
PGPASSWORD
PGPORT
PGUSER
PORT
SECRETE_KEY_JWT

CLOUDINARY_NAME
CLOUDINARY_API_KEY
CLOUDINARY_API_SECRET
```

## Endpoint List

[![Run in Postman](https://run.pstmn.io/button.svg)](https://documenter.getpostman.com/view/26334344/2s93XyUPKH)

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Related Project

:rocket: [`Backend Telegram`](https://github.com/Shaniara28/telegram_be)

:rocket: [`Frontend Telegram`](https://github.com/Shaniara28/telegram_fe)

:rocket: [`Demo Telegram`](#)

<!-- CONTACT -->

## Contact

My Email : Saniarizkiagustin@gmail.com

Project Link: [https://github.com/Shaniara28/telegram_be](https://github.com/Shaniara28/telegram_be)
