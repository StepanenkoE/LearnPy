# LearnPy

#Задание по корпусу:
 Мной был скачан Толковый словарь Дмитриева с сайта academic.ru: http://dic.academic.ru/contents.nsf/dmitriev/ для нужд НИСа, задание было модифицировано под особенности словаря, но основные требования я старалась соблюсти.
 1. academic.py - скачивает корпус в том виде, в котором это удобно для НИСа. Названия файлов и папок содержат кириллические символы. Сама статья представляет собой часть кода html вместе с тэгами. В поздней версии программы для каждой статьи сохраняется не только файл с html, но и чистый текст. Есть csv файл с некоторыми данными по корпусу. Корпус скачан только в ранней версии, т.е. только с файлами html. Доступен по ссылке: https://drive.google.com/open?id=0BwSVXuCXDtRRMGRSQmF6b01ncU0
 2. academic_plain_text.py - скачивает корпус, учитывая требования домашнего задания. Представляет собой частично изменённый код предыдущей программы. Названия статей и категорий заменены на порядковые номера. В файлах txt хранится не html, а тексты статей. Корпус в данном виде скачан, имеет свой csv файл.
 3. dmitriev_mystem.py - Обрабатывает с помощью mystem файлы корпуса, полученного в результате работы программы academic_plain_text.py; Сохраняет в отдельные папки результат в txt и xml. 
UPD: второй корпус, полученный в результате работы программ academic_plain_text.py и dmitriev_mystem.py доступен по ссылке: https://drive.google.com/open?id=0BwSVXuCXDtRRcVQ1TUtoeTBOZG8