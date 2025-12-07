# ФИТ-2024 НМ. Кулаков Андрей. DevOps. ЛР6
# Часть1
## Создаём структуру (папки и файлы)

<img width="339" height="298" alt="image" src="https://github.com/user-attachments/assets/43dde9f0-9c33-4e6d-87d3-68af43bcb40a" />

## Из файлов
- handler/main.yml-для перезапуска nginx
- tasks/main.yml-для самих задач
- site.conf.j2-шаблон конфига сайта
- index.conf.j2-шаблон страницы сайта
## Запуск плейбука и проверки

<img width="974" height="416" alt="image" src="https://github.com/user-attachments/assets/bbf62d18-4e89-4d15-a8b9-520d2d8b5c69" />
<img width="883" height="394" alt="image" src="https://github.com/user-attachments/assets/dc20f201-7397-45f9-9759-2bd6e7bec73a" />
<img width="974" height="823" alt="image" src="https://github.com/user-attachments/assets/a8bc1adf-6783-4b2e-b48d-a72ff9b6d6a4" />

# Часть2
## Для начала в самом GiteHube внесём ключ ssh от ВМ

<img width="974" height="323" alt="image" src="https://github.com/user-attachments/assets/4f07d821-599e-47ea-a2ad-384fe49bbf51" />

## Проверяем свзяь с гитом и клонируем

<img width="974" height="173" alt="image" src="https://github.com/user-attachments/assets/a7be012a-e26b-4cfb-941e-b5b443090584" />
<img width="920" height="213" alt="image" src="https://github.com/user-attachments/assets/8edf4cd6-f516-43b0-b42c-14abfb317a2d" />

## Делаем два файла скриптов в папке github/workflows
- devops_course_pipeline.yml-тестовый сценарий
- lint.yml-сценарий проверяет код на ошибки(на скрине видно, что есть ошибка отсутствие прописаной версии)
  
<img width="974" height="443" alt="image" src="https://github.com/user-attachments/assets/133f3042-8828-4b47-9d9c-58df70299b30" />
<img width="974" height="443" alt="image" src="https://github.com/user-attachments/assets/56c898b4-cdeb-4122-95db-3ff8af9a6808" />


