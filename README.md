# devops-neotology_3.2v1

1. cd — это встроенная команда (программа) bash.
2. grep <some_string> <some_file> -c (кол-во совпадающих строк)  
3. systemd  
4. ls /df >/dev/pts/1 2>&1  
5. cat <test.txt > test2.txt  
6. ?
7. bash 5>$1 (создание нового дескриптора 5)  
   echo netology > /proc/$$/fd/5 (перенаправление вывода в новый дескриптор 5)
8. 
9. Переменные среды для текущего процесса  
    printenv  
10. Файл cmdline, доступный только для чтения, содержит полную командную строку для
процесса (cat /proc/$$/cmdline). Файл exe представляет собой символическую ссылку, содержащую путь к выполняемой команде (cat /proc/$$/exe).  
11. sse4_2  
12. Нет свободного терминала TTY. Запуск ssh с ключом -t для принудительного выделения терминала TTY   
13. sudo apt install reptyr  
root@LSergeyO:~# ping 8.8.8.8  
PING 8.8.8.8 (8.8.8.8) 56(84) bytes of data.  
64 bytes from 8.8.8.8: icmp_seq=1 ttl=59 time=85.1 ms  
root@LSergeyO:/# ps -a  
PID TTY          TIME CMD  
1004 tty2     00:01:59 Xorg  
1153 tty2     00:00:00 gnome-session-b  
5792 pts/1    00:00:00 sudo  
5796 pts/1    00:00:00 bash  
21540 pts/0    00:00:00 sudo  
21541 pts/0    00:00:00 bash  
21571 pts/0    00:00:00 ping  
21572 pts/1    00:00:00 ps  
root@LSergeyO:/# reptyr 21571  
64 bytes from 8.8.8.8: icmp_seq=29 ttl=59 time=89.8 ms  
14. Команда tee вместе с sudo используется для записи в файлы, принадлежащие другим пользователям.






