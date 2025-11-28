----------- GIT -----------

# Инициализируйте git репозиторий
git init

# Добавьте удаленный репозиторий
git remote add origin https://github.com/compotapp/minikube-local

# Получите изменения из удаленного репозитория
git fetch origin

# Создайте связь с веткой (обычно main или master)
git branch --set-upstream-to=origin/main main

# Или если ветка не существует:
git checkout -b main origin/main

---------------------------