---
type: note
id: FUND-GIT-01
level: beginner
status: draft
tags:
  - ctf/fundamentals
  - git
---

# Git и GitHub — основы

## Цель
Уметь получать материалы, создавать ветки, сохранять изменения и предлагать их через Pull Request.

## Основные команды
```bash
git status
git pull
git switch -c docs/MY-TASK
git add path/to/file.md
git commit -m "docs: improve lesson"
git push -u origin docs/MY-TASK
```

## Правила
- Перед работой проверь `git status`.
- Не коммить секреты и личные данные.
- Не используй `git push --force` на общих ветках.
- Не делай `reset --hard`, пока не проверил незакоммиченные изменения.
- Для общих материалов используй Pull Request.

## Практика
- [ ] Клонировать учебный репозиторий.
- [ ] Создать ветку и изменить тестовую заметку.
- [ ] Создать коммит и отправить ветку.
- [ ] Открыть Pull Request.

## Связанные заметки
- [[Правила работы с материалами]]
