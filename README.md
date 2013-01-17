liquibase
=========

Fork for adding support for NuoDB. A quick grep search indicates the need to update
* liquibase / liquibase-core / src / main / java / liquibase / database / core / NuoDbDatabase.java
* liquibase / liquibase-core / src / main / java / liquibase / snapshot / jvm / NuoDbDatabaseSnapshotGenerator.java
* liquibase / liquibase-core / src / main / resources / dist / liquibase.spec
* Add unit tests

Looking to move Lauf Labs properties over to NuoDB over the next few months and will need Liquibase support for this.
Now to find the free time. ;)
