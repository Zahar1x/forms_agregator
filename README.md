#Название: Forms cycle#
Функционал:
* Личный кабинет:
      *  история пройденных опросов
      + просмотр выложенных пользователем запросов
      + рейтинг(формируется из баллов за пройденные опросы и свои выложенные опросы) - чем больше баллов тем выше рейтинг
      + возможность редактировать атрибуты УЗ
      + за какое то кол-во баллов из рейтинга
      + средняя оценка за выложенные опросы 

3. Бизнес логика:
   +2.1 нужна категоризация опросов по тематике, возрастной группе, типу вопросов(открытые, закрытые)
   +2.2 Выкладывание опросов путем загрузки гугл формы по api гугла https://developers.google.com/forms/api/reference/rest?hl=ru
   +2.3 синхронизация изменений в гугл форме и на сайте
   +2.4 отслеживание прохождений опросов
   +2.5 анализ опросов на предмет размера(> 5 вопросов), тематики(без нарушений законов РФ)
   +2.6 поиск опросов по ключевым словам
   +2.7 фильтр опросов по тематике, возрастным ограничениям
   +2.8 давать оценку опросом после прохождения
