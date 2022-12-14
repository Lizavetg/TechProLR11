 # Отчет по 1-й лабораторной работе
 ### ЛР выполнили: Прокопенко Дарья и Герасимова Елизавета, гр.М30-406с-19.
  
  В профиле был создан репозиторий TechProLR1  с файлом LR1.txt, далее необходимо было вписать в файл строку “Morning”  и отправить изменения на удаленный сервер. 
Для этого необходимо было прописать ряд команд:

  1.	$ git add LR1.txt;
  2.	$ git commit –am “All my changes”;
  3.	$ git push origin main;

  Далее на github.com были созданы ветки на каждого члена бригады. В каждой ветке в файле необходимо было заменить строку “Morning” на строку “Morning” *имя участника*
С помощью команды git fetch произошла загрузка из репозитория:

$ git checkout <ветвь>    -  переход на другую ветку.

  Загрузили  файл. И далее с помощью команды git merge смержили 2 ветки.
  
  При слиянии еще одной ветки возникло несоответствие , чтобы его убрать, необходимо стереть в файле все , кроме 2х текстов (взятых из веток).
В конечном итоге выгружаем полученный результат в репозиторий.

  В папке клонированного репозитория создали файлы с расширениями .docx, .txt и .md. Далее данные файлы отправляем в репозиторий с помощью следующих команд: 

  1.	$ git add <file>;
  2.	$ git commit –am “All my changes”;
  3.	$ git push origin main;

  Изменив содержимое каждого файла, проделали те же самые действия, чтобы  внесенные данные отобразились в репозитории. В репозитории изменения в файлах отображаются по-разному: .docx возможно только скачать, чтобы увидеть содержимое файлов; .txt заполненные строки нумеруются; формат .md выглядит как обычный текстовый файл. Размер файлов также отличается: .docx занимает 12,4 КБ, .txt 9 байт и .md 38 байт.
  
  Чтобы проверить историю работы бригады, для начала следует вернуться к более старому коммиту, используя команду “git checkout main”. С ее помощью мы сменили текущую ветку на ветку main. Команда “git log --graph --pretty=oneline --abbrev-commit” позволяет посмотреть на историю работы.
  
  Вывод: После выполнения данной лабораторной работы, мы научились выполнять базовые локальные операции с Git'ом: создавать или клонировать файлы, определеть их состояние, научились отслеживать и записывать измененные файлы в репозиторий;  фиксировать все проделанные изменения, а также просматривать историю всех изменений в репозитории. Также научились созданию новых веток и их слиянию в мастер-ветку. Рассмотрели расширения файлов .docx, .txt и .md, выяснили, что при разном расширении содержимое файлов также отображается по-разному; их размер также отличается.

