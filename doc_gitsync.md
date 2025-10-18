## Инициализация гитсинха (один раз)

// Основной хран
gitsync init -u DeployGit file://C:/Storage1C/StorageOtus C:\Git\Repoz_CICD\DemoUP_ci_cd\src\cf\

// Хран Yaxunit
gitsync init -u DeployGit -e YAXUNIT file://C:/Storage1C/StorageOtus C:\Git\Repoz_CICD\DemoUP_ci_cd\src\cfe\yaxunit\

## Синхронизация с хранилищем

gitsync sync -u DeployGit -p "1234" file://C:/Storage1C/StorageOtus C:\Git\Repoz_CICD\DemoUP_ci_cd\src\cf\
