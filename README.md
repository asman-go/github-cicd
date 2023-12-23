# github-cicd

CI/CD workflows

## PAC token

Чтобы workflow мог выставлять секреты на репозиторий/организацию, надо:

1. В настройках организации разрешить в разделе "Personal access tokens" выдать write permissions для fine-grained tokens
2. Перейти в раздел личных токенов https://github.com/settings/tokens?type=beta
3. Создать себе PAC-токен на выбранный репозиторий и проставить для него permissions на read/write секретов в репозитории/организации

И выполнять действия с этим токеном.
