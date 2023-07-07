# telegram
https://t.me/DevOpsMarathon

Завдань буде чимало, рекомендую підібрати нормальний темп і не згоріти.
Дедлайнів по завданням немає, кожен має працювати в своєму темпі але працювати стабільно і постійно.

# Передумови, знання необхідні для того аби стартувати основний проект:
- Linux. Необхідно розуміти основні концепти, вміти працювати в консолі, знати основні команди. Рекомендую один із багатьох відео на Youtube, наприклад https://www.youtube.com/playlist?list=PL0lO_mIqDDFUwVWvVitxG2oXA6a-Nq-Qq
- Docker. можна також шукати матеріали на ютубі. Після того як ви опануєте основи, можна користуватись ChatGPT з докером.
- Docker Crash Course for Absolute Beginners [NEW]
- Мережі. Виглядає хорошим курс: https://www.educative.io/module/An5VrvSlLQN6R6N8y/10370001/4813190514343936
На виході потрібне розуміння веб серверів, що таке порти як http та https працює.
Типове запитання на інтерв’ю по цій темі: Що відбувається після того, як юзер вводить адресу сайту в рядку браузера. Як і куди по мережі йде запит, DNS, як відбувається віддача контенту з сервера.
- Git and GitHub. GitHub actions: GitHub Actions Tutorial - Basic Concepts and CI/CD Pipeline with Docker
- AWS. 
  - Найперші кроки і реєстрація аккаунту:
  - https://dou.ua/forums/topic/44131
  - Для початку цей Безкоштовний курс на Cloud Guru https://learn.acloud.guru/course/intro-to-aws/overview
  - Потім цей безкоштовний: https://www.udemy.com/course/aws-iam-training/

Потім пройти хоча б один із курсів по AWS про які я писав на каналі або опанувати осови самостійно знайшовши один із курсів для початківців на Youtube. Наприклад https://www.youtube.com/playlist?list=PLg5SS_4L6LYsxrZ_4xE_U95AtGsIB96k9


# Проект розбитий на завдання:
## 1. Початок. Ви повинні взяти будь-який opensource проект.
  - Find any Linux-based web app and deploy it on localhost (any language)
  - Create GitHub Public Repo. Push Code to the repo.
  - Create GitHub Actions Pipeline that builds the app and runs tests.

##  2.Завдання:
  - Зареєструвати AWS акаунт, подивитися що таке Фрі Тір і як він використовується.
  - Розгорнути Апку на AWS. Самим простим способом, наприклад на ec2 сервері.
  - В github actions має бути деплой степ на амазон

Як результат, має бути паблік Амазон IP на якій буде твій сайт, і відповідно, коли будеш комітати код то GitHub actions автоматично задеплоїть зміни на Амазон.

Перед тим як брати будь який амазон сервіс подивися якого вартість і чи входить він у Free Tier, це гарна звичка. Ти наразі маєш брати лише Free Tier, і ні за що не платити, якщо за щось платиш то щось неправильно робиш або пропустив по неуважності.
Це завдання можна зробити мільйоном різних способів, роби це найлегшим чином яким лише можеш.

## 3. Розгортання:
  - Розгортання апки з використанням ECS або EKS(EKS платний)
  - Підключити базу данних(RDS) і зв'язок з нею 
  - Адаптувати пайплайн під це завдання

## 4. Підключаємо Terraform, якщо цього не було зроблено до цього моменту. 
  - Все що зробив в амазоні повинно створюватись тераформом, а не вручну. Він має створити тобі: всі необіхдні мережі, секюріті групи, інстанси, базу, все що використовує твоя апка.
  - Деплой тераформи на Амазон з локалу
  - Тераформ в гітхаб екшинс


## 5. Логування і сповіщення:
  - Прикріпити логування на апку(CloudWatch)
  - Навісити алярм на що небудь, щоб приходили повідомлення на пошту
  - Додати будь-яку кастомну метрику
  - Ну і це все використовуючи тераформ.

## 6. Оформити свій GitHub профіль. 
  - Написати Readme документ де буде описано:
    - що саме за проект ви зробили
    - які технології використали
    - намалювати архітектуру проекту.

# 7. The Best AWS Cloud Projects To Get You Hired (For Beginners)
Рекомендую ознайомитись з наступним відео також:
  - https://youtu.be/5RVT3BN9Iws
  - Солюшн Архітект з Амазону розповідає про три проекти, виконання яких дозволить здобути практичні навички роботи з AWS сервісами. 
В описі до відео є посилання на безкоштовні мануали по виконанню кожного із проектів.
Раджу виконати ці три після того як викнаєте головний проект із доки.
Хоча якщо комусь ці три будуть зрозуміліші ніж той, який зпропонував я, можете починати з них.

# 8. Python and/or Bash скриптинг. 
Не частина проекту але також варто опанувати основи. Будь-який хороший спеціаліст повинен вміти писати скрипти на Python and/or Bash.


# Додатковий / альтернативний шлях вивчення:
Є чудова платформа Cloud Guru, яка надає не тільки лекції, а ще й оточення для виконання лабораторних робіт по темі.
Ви можете пройти там LEARNING PATH по напрямку девопс: https://acloudguru.com/learning-paths/devops
Пройти перші три рівні мало б бути достатньо для позиції джуніора.
Є також профільні напрями типу AWS DevOps: https://acloudguru.com/learning-paths/aws-devops

Із мінусів - платформа платна, 35$ в місяць, а також повністю все англійською.


# Додаткові / Альтернативні роадмапи розвитку: 
- The 2023 DevOps Engineer and SRE RoadMap from Medium: https://medium.com/javarevisited/the-2018-devops-roadmap-31588d8670cb
- DevOps roadmap from the roadmap.sh: https://roadmap.sh/devops
- Another detailed DevOps roadmap: https://github.com/milanm/DevOps-Roadmap

- From Zero to DevOps Engineer - DevOps Roadmap for YOUR specific background https://youtu.be/G_nVMUtaqCk
Також раджу ознайомитись з іншими відео на цьому каналі, корисний матеріал

- Можливо, найкращий англомовний канал на технічні теми де є відео на всі необхідні hard-skills для DevOps: https://www.youtube.com/@TechWorldwithNana

- Kubernetes: https://youtube.com/playlist?list=PLy7NrYWoggjziYQIDorlXjTvvwweTYoNC	

- Рейтинг книг по ДевОпс за версією ДОУ: https://dou.ua/lenta/articles/top-books-2022/?from=doufp#devops

- Complete Linux Training Course to Get Your Dream IT Job 2023
  - https://www.udemy.com/course/complete-linux-training-course-to-get-your-dream-it-job/
  - Цей самий курс від цього викладача але дешевше - https://utclisolutions.com/courses?_ga=2.24951737.2054885387.1677057276-1351064761.1677057276

- Git українською: https://learngitbranching.js.org/?locale=uk

- Сервіс для реєстрації щоб не придумувати кожного разу нову пошту https://temp-mail.org/en/

- Каталог безкоштовних курсів української на Прометеусі: 
https://prometheus.org.ua/courses-catalog/

- Збірка корисних матеріалів, виглядає як альтернативний шлях вивчення, але без виконання проекту
https://learntocloud.guide/docs/Welcome

- Збірка безкоштовних тестів по різноманітним технологіям: https://www.testpreplab.com/AWS-Certified-Cloud-Practitioner-free-practice-test/

- Спеціалізація Google IT Support Professional Certificate.
Виглядає як те що треба аби розібратися з мережами і адмініструванням. https://www.coursera.org/professional-certificates/google-it-support

- Матриця компетенцій згідно із https://youtu.be/liCoNksG_hM
https://github.com/den-vasyliev/SRE-Competency-Matrix


https://docs.google.com/document/d/1qZy7NsOT_Jt6cOC9X_N-PpUwETn5wqUgBlTrhgHzAx4/edit

# docsource
https://docs.google.com/document/d/1qZy7NsOT_Jt6cOC9X_N-PpUwETn5wqUgBlTrhgHzAx4/edit
