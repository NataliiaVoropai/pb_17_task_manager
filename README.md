# Task Manager

## Local Development

Clone the repository

```bash
git clone <repository_url>
```

Create a virtual environment

```bash
python -m venv venv
```

Install dependencies

```bash
pip install -r requirements.txt
```

### TODO

- Змінити формат виведення тасок на `[✔️] <index> - <title>`
- Змінити нумерацію тасок для виводу із 1 (але видалення має працювати правильно з точки зору юзера) - Anastasiia S
- При виході задавати два окремі питання 1 - чи дійсно користувач хоче вийти, а якщо так 2 - чи хоче він експортувати задачі
- Правильно оброблювати ввід користувача на дії “видалити” та “відмітити як зроблене” - валідувати індекс

## Git Feature Branch Workflow

1. Create a new branch

```bash
git checkout -b feature_branch_name
```

2. Make changes

3. Commit changes

```bash
git add .
git commit -m "commit message"
```

4. Push changes

```bash
git push origin feature_branch_name (if the branch does not exist on the remote repository)
OR
git push (if the branch already exists on the remote repository)
```

5. Create a pull request on GitHub