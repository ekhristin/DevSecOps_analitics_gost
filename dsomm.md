# DSOMM: practices grouped by domains (table)

Source activities: dependency-tree.md from DSOMM Data

## Build and Deployment

| ID | Activity (EN) | Translation (RU) |
|---:|---|---|
| 0 | Pinning of artifacts | Пиннинг/привязка артефактов |
| 1 | Defined build process | Определенный процесс сборки |
| 2 | SBOM of components | SBOM для компонентов |
| 3 | Signing of code | Подпись кода |
| 4 | Signing of artifacts | Подпись артефактов |
| 5 | Automated deployment process | Автоматизированный процесс развертывания |
| 6 | Defined deployment process | Определенный процесс развертывания |
| 8 | Inventory of production components | Инвентаризация компонентов production |
| 9 | Inventory of production artifacts | Инвентаризация артефактов production |
| 10 | Handover of confidential parameters | Передача конфиденциальных параметров |
| 11 | Environment depending configuration parameters secrets | Секреты конфигурационных параметров с учетом окружения |
| 12 | Inventory of production dependencies | Инвентаризация зависимостей production |
| 13 | Rolling update on deployment | Постепенное (rolling) обновление при развертывании |
| 14 | Same artifact for environments | Использование одного и того же артефакта для разных окружений |
| 15 | Usage of feature toggles | Использование feature toggles (фичефлагов) |
| 16 | Blue/Green Deployment | Blue/Green развертывание |
| 18 | Automated merge of automated PRs | Автоматическое объединение автоматизированных PR |
| 19 | Automated PRs for patches | Автоматизированные PR для патчей |
| 20 | Automated deployment of automated PRs | Автоматизированное развертывание автоматизированных PR |
| 96 | Evaluation of the trust of used components | Оценка уровня доверия к используемым компонентам |
| 111 | Usage of a maximum lifetime for images | Использование максимального срока службы для образов |

## Culture and Organization

| ID | Activity (EN) | Translation (RU) |
|---:|---|---|
| 21 | Creation of simple abuse stories | Создание простых историй злоупотреблений |
| 22 | Conduction of simple threat modeling on technical level | Проведение простого моделирования угроз на техническом уровне |
| 23 | Creation of threat modeling processes and standards | Создание процессов и стандартов моделирования угроз |
| 24 | Conduction of advanced threat modeling | Проведение углубленного моделирования угроз |
| 25 | Creation of advanced abuse stories | Создание углубленных историй злоупотреблений |
| 26 | Regular security training of security champions | Регулярное обучение по безопасности для security champions |
| 27 | Each team has a security champion | В каждой команде есть security champion |
| 28 | Determining the protection requirement | Определение требований к защите |
| 83 | Office Hours | Часы консультаций по безопасности (office hours) |

## Implementation

| ID | Activity (EN) | Translation (RU) |
|---:|---|---|
| 7 | Version control | Управление версиями (контроль версий) |
| 29 | App. Hardening Level 1 | Жесткая настройка приложения: уровень 1 |
| 30 | App. Hardening Level 1 50% | Жесткая настройка приложения: уровень 1 (на 50%) |
| 31 | App. Hardening Level 2 75% | Жесткая настройка приложения: уровень 2 (на 75%) |
| 32 | App. Hardening Level 2 | Жесткая настройка приложения: уровень 2 |
| 33 | App. Hardening Level 3 | Жесткая настройка приложения: уровень 3 |
| 34 | Block force pushes | Блокировка force-push в репозитории |
| 35 | Require a PR before merging | Требовать PR перед объединением |
| 36 | Dismiss stale PR approvals | Снимать устаревшие одобрения PR |
| 37 | Require status checks to pass | Требовать прохождения статусных проверок |
| 38 | Backup | Резервное копирование |
| 39 | MFA | Многофакторная аутентификация (MFA) |
| 40 | MFA for admins | MFA для администраторов |
| 41 | Usage of test and production environments | Использование тестовых и production-сред |
| 42 | Virtual environments are limited | Виртуальные среды ограничены/лимитированы |
| 43 | Applications are running in virtualized environments | Приложения запущены в виртуализированных средах |
| 44 | Immutable infrastructure | Неизменяемая инфраструктура |
| 45 | Infrastructure as Code | Инфраструктура как код (IaC) |
| 46 | Limitation of system events | Ограничение системных событий |
| 48 | Usage of security by default for components | Безопасные настройки по умолчанию для компонентов |
| 49 | WAF baseline | Базовая конфигурация WAF |
| 50 | Context-aware output encoding | Контекстно-зависимое экранирование вывода |
| 51 | Production near environments are used by developers | Использование окружений, максимально приближенных к production |
| 52 | WAF medium | WAF: средний уровень |
| 53 | WAF Advanced | WAF: расширенный уровень |
| 69 | Filter outgoing traffic | Фильтрация исходящего трафика |
| 93 | Isolated networks for virtual environments | Изолированные сети для виртуальных сред |

## Information Gathering

| ID | Activity (EN) | Translation (RU) |
|---:|---|---|
| 47 | Audit of system events | Аудит системных событий |
| 54 | Centralized application logging | Централизованное логирование приложений |
| 55 | Alerting | Оповещения |
| 56 | Visualized logging | Визуализация логирования |
| 57 | Centralized system logging | Централизованное логирование систем |
| 58 | Correlation of security events | Корреляция событий безопасности |
| 59 | Visualized metrics | Визуализированные метрики |
| 60 | Monitoring of costs | Мониторинг затрат |
| 61 | Simple application metrics | Базовые метрики приложений |
| 62 | Simple system metrics | Базовые метрики систем |
| 63 | Advanced availability and stability metrics | Углубленные метрики доступности и стабильности |
| 64 | Deactivation of unused metrics | Отключение неиспользуемых метрик |
| 65 | Targeted alerting | Целевое оповещение |
| 66 | Advanced app. metrics | Углубленные метрики приложений |
| 67 | Coverage and control metrics | Метрики покрытия и контроля |
| 68 | Defense metrics | Метрики защитных мер |
| 70 | Screens with metric visualization | Дашборды с визуализацией метрик |
| 71 | Grouping of metrics | Группировка метрик |
| 72 | Metrics are combined with tests | Метрики объединены с тестами |
| 73 | Patching mean time to resolution via PR | Сокращение MTTR исправлений через PR |
| 74 | Generation of response statistics | Формирование статистики реагирования |
| 76 | Patching mean time to resolution via production | Сокращение MTTR исправлений через production-внедрение |

## Test and Verification

| ID | Activity (EN) | Translation (RU) |
|---:|---|---|
| 17 | Smoke Test | Smoke-тестирование |
| 75 | Usage of a vulnerability management system | Использование системы управления уязвимостями |
| 77 | Artifact-based false positive treatment | Обработка ложных срабатываний на основе артефактов |
| 78 | Simple false positive treatment | Простая обработка ложных срабатываний |
| 79 | Fix based on accessibility | Исправления на основе доступности/достижимости |
| 80 | Treatment of defects with high or critical severity | Устранение дефектов с высокой или критической серьезностью |
| 81 | Global false positive treatment | Глобальная обработка ложных срабатываний |
| 82 | Exploit likelihood estimation | Оценка вероятности эксплуатации |
| 84 | Coverage of client side dynamic components | Покрытие динамических компонентов на стороне клиента |
| 85 | Usage of different roles | Использование разных ролей при тестировании |
| 86 | Simple Scan | Простой скан |
| 87 | Coverage of hidden endpoints | Покрытие скрытых endpoint-ов |
| 88 | Coverage of more input vectors | Покрытие большего числа векторов ввода |
| 89 | Coverage of sequential operations | Покрытие последовательных операций |
| 90 | Usage of multiple scanners | Использование нескольких сканеров |
| 91 | Coverage of service to service communication | Покрытие взаимодействий сервис-сервис |
| 92 | Test for exposed services | Тестирование открытых сервисов |
| 94 | Test network segmentation | Тестирование сегментации сети |
| 95 | Test for unauthorized installation | Тестирование несанкционированных установок |
| 97 | Software Composition Analysis server side | SCA (Software Composition Analysis) на стороне сервера |
| 98 | Test for Time to Patch | Тестирование времени до исправления |
| 99 | Test libyear | Тестирование возраста библиотек (libyear) |
| 100 | API design validation | Валидация дизайна API |
| 101 | Software Composition Analysis client side | SCA на стороне клиента |
| 102 | Static analysis for important client side components | Статический анализ важных компонентов на стороне клиента |
| 103 | Static analysis for important server side components | Статический анализ важных компонентов на стороне сервера |
| 104 | Test for Patch Deployment Time | Тестирование времени внедрения исправлений |
| 105 | Static analysis for all self written components | Статический анализ всех собственных разработанных компонентов |
| 106 | Usage of multiple analyzers | Использование нескольких анализаторов |
| 107 | Dead code elimination | Удаление мертвого кода |
| 108 | Exclusion of source code duplicates | Исключение дубликатов исходного кода |
| 109 | Static analysis for all components/libraries | Статический анализ всех компонентов/библиотек |
| 110 | Correlate known vulnerabilities in infrastructure with new image versions | Корреляция известных уязвимостей инфраструктуры с новыми версиями образов |
| 112 | Test of infrastructure components for known vulnerabilities | Тестирование компонентов инфраструктуры на известные уязвимости |
