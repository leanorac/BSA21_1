# Домашнее задание 1

Учимся писать пользовательские истории (user story).

School 21: mhorton

## Учение

Пользовательская история (ПИ) имеет устоявшееся строение:

1. пользователь -> это не обязательно физическое лицо (ФЛ), но, возможно, и внешняя система и вообще сущность, которая может использовать целевую систему
2. требование -> пожелание\потребность\функциональность и т.п. - нечто (свойство\поведение\связь), что хотелось бы иметь в целевой системе
3. цель -> конечный выдаток (результат), который будет (может быть) достигнут пользователем системы при воплощении указанного требования

Это обычно подаётся как следующее лекало:

**Кто-то** (сущность) как **Пользователь или Роль + возможное указание системы\подсистемы**
**Желает\Требует\Хочет\...** (глагол изъявления требования) функциональность\хотелка\...
**Чтобы\Для\...** (описание достигаемой цели\потребности\...)

Пример:

**Федеральная налоговая служба** (пользователь) как (уточнение пользователя) "внешний надзорный орган" (пусть будет такая бизнес сущность в наших понятиях)
**Изволит** (далее предметная хотелка) "выбирать разные форматы выгрузки отчётов ХХХ"
**Дабы.** получать данные в нужных форматах без дополнительных усилий по преобразованию данных из одного формата в другие

Как-то так, пусть и подкривовато...

Желательно не смешивать несколько требований в одно, но это сильное пожелание, а не требование.
Т.е., "хочу А и Б, но если не Б, то В" - с этим может быть управляться сложнее.

## Предварение

Я пользуюсь Озон, в основном мобильным приложением.
Но далее, когда буду писать "Озон", буду подразумевать систему в целом: и страницу (сайт), и мобильное приложение и другие доступные способы. В других случах будет уточнятся конечная точка использования (приложение или страница или общедоступное API и т.д.).

В следующем разделе (Упражнение) дело пойдёт о мобильном приложении Озон, точнее Озон банк, поэтому код требований будет следующим:

US_OBS_XX1 = User Story Ozon Bank Категория XX номер. Далее будет категория CB (Cash Back - кэшбек).

## Упражнение

Требование US_OBS_CB1:
**Я** как пользователь Озон банка
**Хочу** выбирать категории кэшбека на следующий месяц начиная с двадцатого числа текущего
**Чтобы** заранее выбирать нужные мне категории на следующий месяц

Требование US_OBS_CB2:
Я как пользователь Озон банка
Хочу получать уведомления по непроставленным категория кэшбека
Чтобы не забыть их выбрать и утвердить с двадцатого числа текущего месяца (см. UB_OBS_CB1) и весь следующий (целевой) месяц

## Источники

- [Гайд по написанию пользовательских историй и критериев приёмки - Habr.ru](https://habr.com/ru/companies/X5Tech/articles/723742/)
- [Что такое User Story и как её создать - Practicum.Yandex](https://practicum.yandex.ru/blog/chto-takoe-user-story-i-kak-napisat/)