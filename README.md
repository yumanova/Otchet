# Otchet

# Отчет о проделанной работе

### Автор: Юманова Эльвира
Ссылка на репозиторий с уроком про животных: https://github.com/yumanova/wild_animals

Ссылка на репозиторий с уроком про геометрическую библиотеку: https://github.com/yumanova/geometric_lib

#### Ход работы
* git clone https://github.com/smartiqaorg/geometric_lib
* git checkout feature
* git checkout develop
* git log --all --graph
* git checkout main
* git merge develop --no-ff
* git reset --hard HEAD^
* git merge develop --ff
* git checkout release
* git rebase -i main 
* notepad docs/README.md
* git add docs/README.md
* git rebase --continue
* notepad docs/README.md
* git add docs/README.md
* git rebase --continue
* git checkout main
* git merge release
* git remote remove origin
* git remote add origin https://github.com/yumanova/geometric_lib.git
* notepad history.md
* git add history.md
* git commit -m 'Created history.md'
* git push origin --all
