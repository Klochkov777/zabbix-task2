# admin-zabbix
<<<<<<< HEAD
=======
# Домашнее задание к занятию "`Zabbix 2`" - `Klochkov Vladimir`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

`Приведите ответ в свободной форме........`

1. 
2. [create new template](https://github.com/Klochkov777/zabbix-task2/blob/feature/screen/task1.2-create%20new%20template.png)
3. создал элемент. В последующих заданиях к нашем хостам необходимо будет присоединить шаблон "Linux by Zabbix agent",
 там элемент для считывания этой информации есть с ключом system.cpu.util ,idle, в качестве выполнения учебного задания,
  но чтобы не было конфликта в будущем при выполнении моего шаблона и "Linux by Zabbix agent", я создал свой параметр в 
  и получил это значение выполняя команду на хосте [create user parameter](https://github.com/Klochkov777/zabbix-task2/blob/feature/screen/task1.3%20create%20user%20parameter.png), а затем создал новый элемент данных
  [create new item for getting free cpu %](https://github.com/Klochkov777/zabbix-task2/blob/feature/screen/task1.3%20create%20item.png) 
4. создавать в процентах не имеет смысла по той же причине что и в предидущем задании, тк шаблон "Linux by Zabbix agent" 
который мы
будем закреплять за хостами имеет уже элемент данных с этим ключом vm.memory.size[pavalable], поэтому я не стал свой 
собственный параметер устанавливать, а просто с ключом vm.memory.size[free] создал элемент. Задание легко сделать, я просто видоизменил его потому что потом возникнет конфликт и один иhttps://github.com/Klochkov777/zabbix-task2/blob/feature/screen/task3.pngз элементов просто не будет работать. Просто чтобы этого не произошло
чуть чуть сделал по другому. [create new item for getting free ram](https://github.com/Klochkov777/zabbix-task2/blob/feature/screen/task1.4%20create%20item%20ram.png)

### Задание 2

это задание находится в задание 3

### Задание 3

* [two templates for two hosts](https://github.com/Klochkov777/zabbix-task2/blob/feature/screen/task3.png)
* [latest data cpu and other](https://github.com/Klochkov777/zabbix-task2/blob/feature/screen/task3%20latest%20data%20cpu.png)
* [latest data ram](https://github.com/Klochkov777/zabbix-task2/blob/feature/screen/task3%20latest%20data%20ram.png)


### Задание 4

[dashboard with grathics](https://github.com/Klochkov777/zabbix-task2/blob/feature/screen/dashboard%20with%20grathics.png)


>>>>>>> bae5bb3 (finished task1.2)
