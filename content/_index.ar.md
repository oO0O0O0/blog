+++
archetype = "home"
title = "home"
+++

##### انشاء صفحة هبوط الرئيسية

```bash
hugo new --kind HOME _index.ar.md  # انشاء صفحة هبوط الرئيسية

hugo new --kind chapter Database/_index.ar.md # صفحة هبوط قواعد البيانات

hugo new Database/MariaDB/_index.ar.md # هبوط النوع 1 من فصل قواعد البيانات
### ***محتويات الفصل***
hugo new Database/MariaDB/Install.ar.md
hugo new Database/MariaDB/SSL-TLS.ar.md
hugo new Database/MariaDB/Backup.ar.md
hugo new Database/MariaDB/Replication.ar.md
hugo new Database/MariaDB/Galera-Cluster.ar.md
hugo new Database/MariaDB/phpMyAdmin.ar.md

hugo new Database/PostgreSQL/_index.ar.md # هبوط النوع 2 من فصل قواعد البيانات
### ***محتويات الفصل***
hugo new Database/PostgreSQL/Install.ar.md
hugo new Database/PostgreSQL/SSL-TLS.ar.md
hugo new Database/PostgreSQL/Backup.ar.md
hugo new Database/PostgreSQL/Replication.ar.md
hugo new Database/PostgreSQL/Galera-Cluster.ar.md
hugo new Database/PostgreSQL/phpMyAdmin.ar.md


hugo new --kind home _index.md
hugo new --kind chapter first-chapter/_index.md
hugo new first-chapter/first-page/_index.md
hugo new first-chapter/second-page/index.md
hugo new first-chapter/third-page.md

# in use

hugo new DRUPAL/Development/xxx.ar.md
```