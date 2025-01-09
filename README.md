# LawMatic-B2-Windows
Описание проекта LawMatic B2 для Windows и условий получения доступа к исходным кодам проекта. Этот репозиторий также содержит общую информацию о проекте и примеры использования, доступные для всех.

![Scr_moek_lawmaticb2win](https://github.com/user-attachments/assets/8f043a19-c40d-45e4-a96c-72e99a15e44f)


## Исходный код проекта LawMatic B2 для Windows  

Мы можем предоставить пользователям доступ к исходным кодам проекта LawMatic B2 для Windows (а также LawMatic B2 для iOS, [LawMatic B2 для macOS](https://github.com/lawlabs/LawMatic-B2-macOS), LawMatic B2 для Android - эти проекты размещены в других репозитариях). Мы считаем, что наши пользователя должны быть на 100% уверены в чистоте, отсутствии закладок и т.п. продукта, который планируют использовать. Специалисты со стороны пользователя могут проверить весь код, сделать форк, самостоятельно скомпилировать в соответствующей среде разработки и использовать, в правом предоставления приложения другим пользователям самостоятельно скомпилированный проект. 

Исходный код этого проекта доступен только зарегистрированным пользователям при подписании NDA и при оплате подписки на использование продукта. Для уточнения условий и получения доступа, свяжитесь с нами info@lawlabs.ru.  

# Описание проекта LawMatic B2 для Windows

## Что делает LawMatic B2 уникальным?

Систем учета дел, как специализированных для юристов, так и универсальных (например, Яндекс.Трекер, Битрикс24), достаточно много. Однако у **LawMatic B2** есть уникальные возможности, которых нет у других (поправьте нас, если с момента размещения данного текста что-то изменилось на рынке LegalTech в России), попробуем придумать слоган: "Скучали по оффлайн-продуктам? У нас есть. Но потом стала нужна синхронизация? Тоже можно. Гм, только часть данных нужно синхронизировать? А вот есть и это".

### 1. Полная автономность работы
- **Офлайн-режим**: Все данные хранятся исключительно на устройстве пользователя (поддерживаются Windows, macOS, iPhone, Android).
- **Безопасность данных**: Никакие данные не передаются по сетям или не сохраняются на серверах хостеров.

### 2. Контролируемая и безопасная синхронизация
- **Файловая синхронизация**: Пользователь может вручную выгружать данные в файл и загружать их на другое устройство для синхронизации. Это менее удобно, чем автоматическая синхронизация, но предоставляет полный контроль над "чувствительной" информацией.
- **Частичная синхронизация через сервер**: Можно выбрать, какие данные передавать через интернет. Например:
  - Публичная информация (наличие дел, заседания) может быть синхронизирована.
  - Приватная информация (например, финансовые данные) исключается из синхронизации.
- Пользователь может разделять данные на:
  - Безопасные данные, которые могут быть синхронизированы.
  - Данные, которые останутся только на локальном устройстве.
  - 
### 3. SAAS и обычная синхронизации с локальными клиентами
- **Обычная синхронизация через сервер**: Доступна возможность синхронизации данных с сервером, используя ключи API. Также поддерживается онлайн-доступ через браузер (вариант работы SAAS).

### 4. Интеграция искусственного интеллекта
Мы внедряем в систему учета юридической работы **интеллектуальные инструменты**, которые выходят за рамки стандартных функций (анализ текста, поиск условий в договорах). LawMatic B2 предлагает:

- **Автоматизация на основе ИИ**:
  - Например, загрузка файла с текстом решения суда с сайта суда.
  - Система может:
    - Найти дело, к которому относится это решение.
    - Создать запись о вынесенном решении.
    - Сохранить файл в соответствующей папке дела и клиента.
  
- **Настраиваемые сценарии работы с ИИ**:
  - Пользователи могут настраивать собственные сценарии обработки данных, экспериментировать с промтами и моделями.

- **Поддержка API**:
  - Встроенная работа с YandexGPT, OpenAI, GigaChat - в планах.
