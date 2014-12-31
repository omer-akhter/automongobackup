* VER 0.9.3 - (2014-12-24) (author: Omer Akhter)
  * Added xz compression option
  * Added option to log to single file
  * Added option to keep logs
* VER 0.9.2 - (2014-xx-xx) (author: Alex Bevilacqua)
  * Added 7zip compression option
* VER 0.9.1 - (2014-xx-xx) (author: Xisco Guaita)
  * Added individual database backup
  * Added individual collection backup
* VER 0.9 - (2011-10-28) (author: Joshua Keroes)
  * Fixed bugs and improved logic in select_secondary_member()
  * Fixed minor grammar issues and formatting in docs
* VER 0.8 - (2011-10-02) (author: Krzysztof Wilczynski)
  * Added better support for selecting Secondary member in the Replica Sets that can be used to take backups without bothering busy Primary member too much.
* VER 0.7 - (2011-09-23) (author: Krzysztof Wilczynski)
  * Added support for --journal dring taking backup to enable journaling.
* VER 0.6 - (2011-09-15) (author: Krzysztof Wilczynski)
  * Added support for --oplog during taking backup for point-in-time snapshotting.
  * Added filter for "mongodump" writing "connected to:" on the standard error, which is not desirable.
* VER 0.5 - (2011-02-04) (author: Jan Doberstein)
  * Added replicaset support (don't Backup on Master)
  * Added Hard Support for 'latest' Copy
* VER 0.4 - (2010-10-26)
      * Cleaned up warning message to make it clear that it can usually be safely ignored
* VER 0.3 - (2010-06-11)
  * Added the DBPORT parameter
  * Changed USERNAME and PASSWORD to DBUSERNAME and DBPASSWORD
  * Fixed some bugs with compression
* VER 0.2 - (2010-05-27) (author: Gregory Barchard)
  * Added back the compression option for automatically creating tgz or bz2 archives
  * Added a cleanup option to optionally remove the database dump after creating the archives
  * Removed unnecessary path additions
* VER 0.1 - (2010-05-11)
  * Initial Release
