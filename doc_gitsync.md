## Инициализация гитсинха (один раз)

// Основной хран
//gitsync init -u DeployGit tcp://KyralesGun/Storage/storage.1ccr/StorageOtus f:\1C\Projects\otus_JenkinsExample\src\cf\
gitsync init -u DeployGit file://C:/Storage1C/StorageOtus C:\Git\Repoz_CICD\DemoUP_ci_cd\src\cf



// Хран Yaxunit
//gitsync init -u DeployGit -e YAXUNIT tcp://KyralesGun/Storage/storage.1ccr/StorageOtus_yaxunit 
//f:\1C\Projects\otus_JenkinsExample\src\cfe\yaxunit\

gitsync init -u DeployGit -e YAXUNIT file://C:/Storage1C/StorageOtus C:\Git\Repoz_CICD\DemoUP_ci_cd\src\cfe\yaxunit\


## Синхронизация с хранилищем

//gitsync sync -u DeployGit tcp://KyralesGun/Storage/storage.1ccr/StorageOtus f:\1C\Projects\otus_JenkinsExample\src\cf\
gitsync sync -u DeployGit -p "1234" file://C:/Storage1C/StorageOtus C:\Git\Repoz_CICD\DemoUP_ci_cd\src\cf\

