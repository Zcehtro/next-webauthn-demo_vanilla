# README

- [README](#readme)
  - [Settings for this repository](#settings-for-this-repository)
  - [Tools required to run this project](#tools-required-to-run-this-project)

## Settings for this repository

.env.local

```env
NEXTAUTH_SECRET=(random 44 character string)
```

## Tools required to run this project

Fake SMTP server

- Smtp4dev

```docker
docker run --name=smtp4dev -p 2525:25 -p 3080:80 rnwood/smtp4dev
```

- MongoDB server
