# Cyscom CTF

Modern cyberpunk styled CTFd platform using the Pixo theme.

---

# Features

- Cyberpunk UI
- Responsive design
- Docker based setup
- Custom homepage
- Custom logo support

---

# Installation

## Clone Repository

```bash
git clone https://github.com/Hikmal-source/Cyscom-CTF.git
```

## Move Into Folder

```bash
cd Cyscom-CTF
```

## Run Docker

```bash
docker compose up -d
```

## Open Browser

```text
http://localhost:8000
```

---

# Theme Installation

```bash
git clone https://github.com/hmrserver/CTFd-theme-pixo.git ./CTFd/themes/pixo
```

Restart Docker:

```bash
docker compose restart
```

Activate theme:

```text
Admin Panel → Config → Themes → pixo
```

---

# Customization

Edit homepage:

```text
CTFd/themes/pixo/templates/index.html
```

Change logo:

```text
CTFd/themes/pixo/static/img/logo.png
```

