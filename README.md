# EmailApp
Email app vypracován dle zadání

Návod na instalaci email aplikace
1.	Extrahujte archiv EmailApp-Kompilovana.rar do složky, kde chcete mít aplikaci umístěnou
2.	Extrahujte soubor  AppDB.db z archivu SqliteDB.zip do složky C:\SqliteDB
(složku je třeba vytvořit)
3.	 Spusťe příkaz inetmgr v dialogu pro spuštění programu (kláv. zkratka - win + R)
(Případně je nutné aktivovat IIS server v Control Panel-> Programs -> Turn on features on or off ->  V seznamu zvolte Internet Information Services
4.	V IIS manageru zvolte v Connections oknu Sites->Add Website
5.	V dialogu Add Website zvolte Site name a jako Physical path zvolte složku, ve které se nacházi EmailApp aplikace
6.	zvolte port a případně připojení, a server s aplikací lze spustit
7.	Na aplikaci se lze připojit adresou localhost:port
