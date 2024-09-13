# notes-java
мои заметки по JAVA

# Многопоточность

*Thread dump*
Для снятия тред дампа: jstack, jmap, jconsole
Пример: jstack -l 3480 (ps aux)
Полученный thread dump можно вставить в fastthread.io и поразглядывать

Потоки ОС - Threads class SMR info
Потоков JVM - VM Thread
Количество JNI-ссылок - JNI global references
Найденные дедлоки - Found one Java-level deadlock
