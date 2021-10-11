### Legend:
@ - term to remember.<br>
? - question <br>
& - my understanding <br>

### Intro
@ Object-oriented modeling (OOM) - "is a way of thinking about problems using models organized around real-world concepts."<br>

& OOM использует объекты - объединение структуры и поведения в одну группу. <br>
& **Структура** - Кошка, мама, мотоцикл, виноград. Кажется это может быть любое существительное.<br>
& **Поведение** - То что вообще можно сделать над этой структурой: дернуть за хвост, покрасить, разобрать, посмотреть что внутри, скрутить.<br>

? Куда совать межструктурное поведение? <br>
? В отдельный объект "кошка-собака-взаимодействие"?<br>

@ **Object-oriented (OO)** - "means that we organize software as a collection of discrete objects that incorporate both data structure and behavior"<br>

& ОО наделяют 4-мя характеристиками: **Identity, classification, inheritance, polymorphism**<br>
@ **Identity** - "Identity means that data is quantized into discrete, distinguishable entities called objects."<br>
	* Похоже на определение инкапсуляции (не сокрытия).<br>
@ "Objects can be concrete, such as a file in a file system, or conceptual, such as a scheduling policy in a multiprocessing operating system."<br>
@ "Two objects are distinct even if all their attribute values (such as name and size) are identical"<br>

@ "**Classification** means that objects with the same data structure (attributes) and behavior (operations) are grouped into a class"<br>
@ "A class is an abstraction that describes properties important to an application and ignores the rest"<br>
@ "Each object is an instance of its class."<br>

& Класс - человек, объекты: Петя, Вася.<br>

## 1.2.1 Modeling Concepts, Not implementation
& **Object oriented development (OOD)** -  процесс создания софта посредством объектно-ориентированого моделирования. Т.е. сперва ты бахаешь диаграммы, понимаешь что и как должно работать, а потом только кодишь. 

& Идея простая - модели (классы и диаграммы) это упрощение кода. Ты откидываешь детали того как делегаты, события, модицикаторы доступа и прочая языковая фигня будет реализована, но концентрируешься только на бизнес процессах. А чем меньше деталей - тем эффективнее работа (меньше шансов ошибиться, легче найти подводные камни итд).

## 1.2.2 OO Methodology
**OO Methodology** - инструкция как писать софтину. Состоит из:
- **System conception** - БА или заказчик формирует пробные требования.
- **Analysis** - БА постоянно общается с заказчиком (потому что первые требования не всегда полные, а иногда и очень ошибочны) и формирует модели:
	- **Domain models** - описание реальных объектов бизнеса.
	- **Application model** - описание частей приложения которые видны юзеру. Полагаю это UI\UX дизайнер.
- **System design** - разрабы смотрят на требования и говорят о возможных идеях и проблемах с точки зрения кода (что-то будет тормозить, sql инъекции вдруг будет итд, или может кто-то знает какой-то сервис, который уже решает эту проблему).
- **Class design** - Берем Domain models и Applicaiton model и бахаем структуры данных, алгоритмы и то как это будет работать в теории. 
- **Implementation** - Пилим код.

## 1.2.3 Three Models
- **Class model** - class diagram - ноды это классы, а стрелочки отношения между ними.
- **State model** - state diagram - ноды это "состояния", а стрелочки - изменения между состояниями, которые произошли по какому-то событию
- **Interaction model** - use case diagram, sequence diagram. activity diagram

## 1.3 OO Themes
**abstraction** - штуки, которые позволяют тебе упрощать что-то сложное, чтобы концентрироваться только на важном.

