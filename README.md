# Домашнее задание Тесты

## Действия для запуска приложения

Склонируйте репозиторий 

```bash
git clone https://github.com/ilyamolokov/shri2023-testing-homework.git
```

В корне папки проекта выполните команду `npm i` затем команду `npx playwright install`

Выполнить билд проекта `npm run build`

Запустите командой `npm run start`

Приложение запустится на [http://localhost:3000/hw/store](http://localhost:3000/hw/store).

В проекте два вида тестов юнит и e2e - их можно запустить одной командой `npm run test`

Если хотите запустить тесты по отдельности это можно сделать следующими командами

`npm run test:unit` запустить юнит тесты

`npm run test:e2e` запустить e2e тесты

При первичном запуске е2е тесты дефолтно упадут - это будет сетапом который создат эталонные скриншоты(Я не стал добавлять эталонные скриншоты сразу в проект т.к. у меня и у проверяющего могут использоваться разные ОС и разрешения экрана, а это может дать непредсказуемый результат) 

🐘