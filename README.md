<img width="1600" height="900" alt="hoax-ctf-cover" src="https://github.com/user-attachments/assets/11020351-8d5b-40a0-9b4c-afc25c864d10" />
# HOAX CTF

HOAX is a story-driven Capture The Flag challenge built around exploration rather than simply following a list of vulnerabilities.

You'll encounter a mixture of:

* 🌐 Web challenges
* 🐧 Linux exploration
* 🔐 Privilege escalation
* 🧩 Hidden clues and puzzles
* 🗃️ Filesystem investigation
* 🕵️ Small details that may matter more than they seem

The challenge is designed so that each discovery leads naturally toward the next part of the system.

---

## Requirements

* Docker
* Docker Compose
* A browser
* A Linux terminal

---

## Setup

Download the latest release from the [Releases](https://github.com/witboric/hoax_CTF/releases) page.

Download the following file:

```text
hoax-ctf.tar.gz
```

### 1. Load the Docker image

```bash
docker load -i hoax-ctf.tar.gz
```

### 2. Start the challenge

```bash
docker compose up -d
```

### 3. Open the web interface

Open the following address in your browser:

```text
http://localhost:8080
```

### 4. Access the terminal

```bash
docker exec -it hoax-ctf /usr/local/bin/hoax-terminal
```

The terminal environment is part of the challenge, so don't expect everything inside it to behave like a normal machine.

---

## Objective

Find the hidden flags and piece together what HOAX is trying to tell you.

Not every clue is presented directly.

Sometimes the interesting part isn't the file itself, but **why it's there**.

---

## Difficulty

**Intermediate**

### Recommended knowledge

* Basic Linux commands
* Basic web technologies
* Browser DevTools
* Filesystem navigation
* Basic privilege escalation concepts
* Curiosity :)

You don't need to know everything beforehand. The challenge is meant to reward investigation.

---

## Disclaimer

HOAX is an intentionally vulnerable CTF environment.

Run it locally and only against systems you own or have explicit permission to test.

---

## Credits

Created by **axis**

Built for learning, experimentation, and anyone who enjoys breaking things just to understand how they work.
