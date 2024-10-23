# Week 2

## Topics

<li> Software process models
<li> Process Activities
<li> Coping with change
<li> Process Improvement

## Software process models
A software process is a set of related activities that leads to the production of a software system.

**Four Funtamemtal Software Engineering Activity**
- Software Specification 
- Software Development
- Software Validation
- Software Evaluation (*Softfare must evolve to meet changing customer needs*)

**Software Process Models**  
Generic models are high-level, abstract descriptions of software processes that can be used to explain different approaches to software development

### Waterfall model
![alt text](image.png)
### Incremental Model
![alt text](image-1.png)
### Integration and Configuration Model
The integration and configuration process model is based on reuse. In this software process model, systems are adapted from existing components as much as possible. The reused components may be configured to adapt their behavior and functionality to the requirements of the new software or system.

![alt text](image-2.png)

## Process Activities
- **Software Design and Implementation:** Software design is a creative activity in which you identify software components and their relationships, based on a customer's requirements. Implementation is the process of realizing the design as a program.
- **Software Validation:** checks that the software product satisfies or fits the intended use.
- **Software Evaluation:** The process of measuring the performance and utility of software assets in businesses' inventories. The purpose of software evaluation is to detect dysfunctional and unused software.

## Coping with change
It is a process of adapting to changes that occur during software development. These changes may relate to project requirements, technologies, architecture, business goals, and other factors that affect the software creation process.
## Process Improvement
Process Improvement means understanding existing processes and changing these processes to increase product quality and/or reduce costs and development time.

## Agile Software development
Это гибкий подход к разработке программного обеспечения, который фокусируется на быстрой адаптации к изменениям, взаимодействии с клиентами и регулярной доставке небольших, работающих частей продукта. Основные принципы Agile изложены в Манифесте гибкой разработки ПО (Agile Manifesto), опубликованном в 2001 году
### Основные характеристики Agile
- **Итеративная разработка:** Проект разбивается на короткие циклы (итерации или спринты), обычно продолжительностью от 1 до 4 недель. В конце каждой итерации команда представляет работающий продукт.
- **Постоянная обратная связь:** Постоянное взаимодействие с клиентом или пользователем для получения обратной связи и корректировки требований по ходу разработки.
- **Адаптивность к изменениям:** Agile приветствует изменения требований даже на поздних этапах проекта. Команда всегда готова пересматривать и корректировать план работы
- **Командная работа:** Agile основывается на тесном взаимодействии всех участников команды (разработчики, тестировщики, менеджеры и клиенты) и прозрачности процесса разработки.
- **Работающий продукт — главный показатель успеха:** В Agile основное внимание уделяется регулярной поставке работающего программного обеспечения, которое приносит реальную пользу клиенту.
### Основные методологии Agile
- **Scrum:** Одна из наиболее популярных методологий. Она организует процесс работы в короткие спринты, назначает роли (например, Product Owner, Scrum Master) и включает регулярные встречи (ежедневные стендапы, планирование спринтов, ретроспективы).
- **Kanban:** Методология, которая визуализирует задачи с помощью доски и карточек, помогая отслеживать рабочий процесс и улучшать его гибкость. Основной фокус на визуализации потока задач и устранении узких мест.
- **XP (Extreme Programming):** Методология, направленная на повышение качества разработки через тесное сотрудничество с клиентами, частые релизы, тестирование и парное программирование.
## Принципы Agile (Манифест Agile):
1. Люди и взаимодействие важнее процессов и инструментов.
2. Рабочий продукт важнее исчерпывающей документации.
1. Сотрудничество с клиентом важнее контрактных переговоров.
1. Готовность к изменениям важнее следования первоначальному плану.

Agile помогает командам быстро реагировать на изменения, предоставлять клиентам актуальные решения и работать более продуктивно в условиях изменяющихся требований.

# Week 3

## Topics

<li> Functional and non-functional requirements
<li> Requirements engineering processes
<li> Requirements elication, specification and validation
<li> Requirements change  

### Functional and non-functional requirements
![alt text](image-6.png)

![alt text](image-7.png)

**Functional requirements** - what system should do  
**Non-Functional requirements** - how system should work

### Requirements engineering processes
Это процесс систематического определения, документирования и управления требованиями к программному обеспечению или системе. Процесс помогает разработчикам и заказчикам лучше понять цели системы, гарантировать их достижение и управлять изменениями требований на протяжении жизненного цикла проекта.

### Requirements elication, specification and validation
- **Elication (Сбор требований)** - это процесс выявления потребностей и ожиданий всех заинтересованных сторон, включая клиентов, пользователей, и команды разработки.
- **Specifation** - это процесс документирования требований, выявленных на этапе их сбора и анализа. Этот документ становится основой для разработки, тестирования и дальнейшей валидации требований.
- **Validation** - это процесс проверки и подтверждения того, что задокументированные требования правильно отражают потребности всех заинтересованных сторон и являются реализуемыми.
### Requirements change 
 это процесс внесения изменений в требования к системе в течение всего жизненного цикла разработки программного обеспечения. Поскольку требования могут изменяться из-за различных факторов, правильное управление изменениями является критически важным для успеха проекта.

 # Week 4

## Topics
- Context Models
- Interactional and Structural Models
- Behavioral Models
- Model-driven engineering

System modeling is the process of developing abstract models of a system, with each model presenting a different view or perspective of that system. Models are used during the requirements engineering process to help derive the detailed requirements for a system, during the design process to describe the system to engineers implementing the system, and after implementation to document the system`s structure and operation.
***UML (Unified Modelling language)* -> 14 diagram types
### Context Models
это графические или текстовые представления, которые описывают окружающую среду системы, ее взаимодействия с пользователями и другими системами, а также основные компоненты, которые влияют на ее функционирование. Контекстные модели помогают командам разработки понять, как система будет использоваться, кто ее будет использовать и какие факторы могут повлиять на ее поведение.

### Interactional Models
это представления, которые описывают, как пользователи взаимодействуют с системой, а также как различные компоненты системы взаимодействуют друг с другом. Эти модели помогают визуализировать, анализировать и проектировать взаимодействия, что важно для обеспечения удобства и эффективности пользовательского опыта.
![alt text](image-8.png)
### Structural Models
 это представления, которые описывают организацию системы, ее компонентов и их взаимосвязи. Эти модели помогают визуализировать архитектуру системы, показывая, как различные элементы взаимодействуют и как они структурированы внутри системы. Структурные модели являются важным инструментом в инженерии требований и системном проектировании.
 
 ### Behavioral Models
 это представления, которые описывают динамическое поведение системы, ее компонентов и их взаимодействий с пользователями и другими системами. Эти модели помогают понять, как система будет реагировать на события, как она будет изменяться во времени и как различные компоненты будут взаимодействовать для выполнения функций.
 
 ### Model-driven engineering
  это подход в разработке программного обеспечения, который фокусируется на использовании моделей как основного артефакта на всех этапах процесса разработки. MDE позволяет создавать, анализировать и трансформировать модели для генерации кода и другой документации, что может значительно упростить и ускорить процесс разработки.

# Week 5

## Topics
- Architectural design decisions
- Architectural views
- Architectural patterns
- Application architectures

### Architectural design
Give answer to questions like, how a software system should be organized
and also designing the overall structure of that system.
### Architectural design decisions
это ключевые выборы и определения, принимаемые во время разработки архитектуры системы. Эти решения формируют основную структуру системы, определяют, как различные компоненты будут взаимодействовать, и задают параметры, влияющие на производительность, надежность и удобство использования.

## Architectural views
 это различные способы представления архитектуры системы, которые помогают различным заинтересованным сторонам (разработчикам, архитекторам, менеджерам, заказчикам) понять ее структуру и поведение. Каждый вид акцентирует внимание на определенных аспектах системы, обеспечивая более глубокое понимание и облегчая коммуникацию.

![alt text](image-9.png)
 ## Architectural patterns
 это общепринятые решения для часто возникающих проблем в архитектуре программных систем. Они предоставляют структурированные подходы к проектированию системы, описывая, как различные компоненты и их взаимодействия должны быть организованы. Архитектурные шаблоны помогают обеспечить лучшие практики, улучшить качество разработки и упростить поддержку системы.
 - **Архитектура на основе представления-управления (Model-View-Controller - MVC):** В этом шаблоне система разделена на три основные компоненты: модель (данные), представление (интерфейс пользователя) и контроллер (логика управления). Это разделение упрощает поддержку и тестирование.
 ![alt text](image-10.png)
 - **Многослойная архитектура (Layered Architecture):** В этом шаблоне система организована в несколько слоев (например, презентационный, бизнес-логики и доступа к данным). Каждый слой имеет четко определенные обязанности и взаимодействует только с соседними слоями, что упрощает тестирование и поддержку.
 ![alt text](image-11.png)

 - **Repository Architecture (Архитектура репозитория):** Это архитектурный шаблон, который используется для организации и управления данными в программных системах. Он разделяет бизнес-логика и доступ к данным, позволяя более удобное управление и манипуляцию с данными, а также упрощая тестирование и поддержку кода. 
 ![alt text](image-12.png)

 - **Клиент-сервер (Client-Server):** Этот шаблон разделяет клиентские и серверные компоненты, позволяя клиентам запрашивать услуги у серверов. Он широко используется в веб-приложениях, где клиент (браузер) взаимодействует с сервером через API.
 ![alt text](image-13.png)

 ## Application Architectures (Архитектурные решения приложений)
 это структурные схемы, которые описывают, как различные компоненты приложения взаимодействуют друг с другом и с окружающей средой. Правильная архитектура приложения обеспечивает масштабируемость, гибкость и устойчивость системы, а также упрощает ее разработку, тестирование и поддержку.

 - **Transaction Processing Systems, Системы обработки транзакций** -  это информационные системы, которые управляют и обрабатывают данные о транзакциях. Они предназначены для эффективного и точного выполнения большого объема рутинных транзакций, обеспечивая, чтобы данные были захвачены и обработаны в реальном времени или вблизи реального времени.
 ![alt text](image-14.png)
 - **Information Systems, Информационные системы** - представляют собой интегрированный набор компонентов для сбора, хранения, обработки и передачи данных и информации. Они используются для поддержки принятия решений, координации, контроля, анализа и визуализации в организации.
 ![alt text](image-15.png)
 - **Language Processing Systems, Системы обработки языка** - это программные приложения, которые анализируют, понимают и генерируют человеческий язык. Они часто являются частью области, известной как Обработка естественного языка (NLP), которая сочетает вычислительную лингвистику, машинное обучение и искусственный интеллект для упрощения взаимодействия между компьютерами и людьми с помощью естественного языка.
 ![alt text](image-16.png)