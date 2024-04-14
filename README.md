# otus_postgres
Запускаем Vagrant
<pre>Vagrant up</pre>
Поднимается три ВМ:
- мастер postgres;
- реплика postgres;
- barman.

Проверяем работу репликации 
<pre>select * from pg_stat_replication;</pre>
![image](https://github.com/ViktorKonovalenko/otus_pg/assets/32430041/99398095-588a-4edb-9285-34f068a59341)

Проверяем работу barman
![image](https://github.com/ViktorKonovalenko/otus_pg/assets/32430041/6e2d45d1-788f-4bc6-b5ad-dbc10fd7b41f)
