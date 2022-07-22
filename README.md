# VSCode Setup

Setup para deixar o VSCode pronto para trabalhar com Laravel e PHP.

## 1. Github

Vamos ter mais informações rápidas do histórico de git dos arquivos, além de `git log` direto pelo vscode.

<img width="2032" alt="CleanShot 2022-07-22 at 12 21 42@2x" src="https://user-images.githubusercontent.com/23129218/180500511-044092f1-ae97-4cfb-93b1-7c0f4cf26360.png">

![CleanShot 2022-07-22 at 12 19 51@2x](https://user-images.githubusercontent.com/23129218/180500256-04d83ca5-7ba0-44ba-9db7-2ec50c153efe.png)

```
code --install-extension GitHub.copilot
code --install-extension donjayamanne.githistory
code --install-extension eamodio.gitlens
```

## 2. PHP

Habilitaremos uma melhor análise do código php, melhores sugestões de código, uma leitura melhor das classes, métodos e propriedades. Além de uma ajuda em erros de código. 

![CleanShot 2022-07-22 at 12 20 31@2x](https://user-images.githubusercontent.com/23129218/180500348-8cec21a9-6fc9-408e-9a09-8049000118c1.png)

<img width="2032" alt="CleanShot 2022-07-22 at 12 24 46@2x" src="https://user-images.githubusercontent.com/23129218/180500921-06070448-9244-4688-b816-359120845183.png">

```
code --install-extension bmewburn.vscode-intelephense-client
code --install-extension junstyle.php-cs-fixer
code --install-extension MehediDracula.php-namespace-resolver
code --install-extension neilbrayfield.php-docblocker
code --install-extension liamhammett.inline-parameters
```

## 3. PHPUnit

Ajuda visual na execução e resultado dos testes unitários. E teclas de atalho para acelerar a execução de testes usando PEST.

<img width="2032" alt="CleanShot 2022-07-22 at 12 30 11@2x" src="https://user-images.githubusercontent.com/23129218/180501682-a1d03194-3676-4b49-84e3-fad5926f689c.png">

```
code --install-extension m1guelpf.better-pest
code --install-extension hbenl.vscode-test-explorer
code --install-extension recca0120.vscode-phpunit
```

## 4. Laravel

Com essas extensões vamos conseguir navegar melhor pelo Laravel, formatação de blade, análise melhor do código, atalhos para criação de novos componentes e classes do laravel.

<img width="2032" alt="CleanShot 2022-07-22 at 12 34 58@2x" src="https://user-images.githubusercontent.com/23129218/180502353-30405b1b-fc00-4787-b8a3-ff5f6d5b8bd5.png">

```
code --install-extension amiralizadeh9480.laravel-extra-intellisense
code --install-extension austenc.laravel-blade-spacer
code --install-extension cjhowe7.laravel-blade
code --install-extension codingyu.laravel-goto-view
code --install-extension ryannaddy.laravel-artisan
code --install-extension shufo.vscode-blade-formatter
code --install-extension mikestead.dotenv
code --install-extension bradlc.vscode-tailwindcss
```

## 5. Docker

<img width="2032" alt="CleanShot 2022-07-22 at 12 37 20@2x" src="https://user-images.githubusercontent.com/23129218/180502709-b6219079-c3b8-4c82-9caa-2a4701776684.png">


```bash
code --install-extension ms-azuretools.vscode-docker
```

## 6. File Management

Criar, deletar, renomear, mover, duplicar tudo pelo teclado. Muito mais rápido.

<img width="2032" alt="CleanShot 2022-07-22 at 12 37 20@2x" src="https://user-images.githubusercontent.com/23129218/180502806-9e7cf3f4-6132-467c-8559-9f4386e83695.png">

```
code --install-extension patbenatar.advanced-new-file
code --install-extension **sleistner.vscode-fileutils
```

## 7. Project Management

Você trabalha com diversos projetos e precisa navegar por eles de forma rápida. 

<img width="2032" alt="CleanShot 2022-07-22 at 12 39 45@2x" src="https://user-images.githubusercontent.com/23129218/180503068-66cb53bd-38be-48ce-98f2-46b06bdc95b3.png">

```
code --install-extension alefragnani.project-manager
```

## 8. Rest Client

Precisa testar endpoints rapidamente. Não precisa de Insomnia, Postman, ou HTTPie.

<img width="2032" alt="CleanShot 2022-07-22 at 12 42 03@2x" src="https://user-images.githubusercontent.com/23129218/180503384-ca2df20c-eba9-4f2a-aad7-162519b97c4e.png">

```
code --install-extension rangav.vscode-thunder-client
```

## 9. Mudando o Visual

<img width="2032" alt="CleanShot 2022-07-22 at 12 42 50@2x" src="https://user-images.githubusercontent.com/23129218/180503507-efcdc026-912a-465a-b12e-6907a23c373b.png">

```
code --install-extension iocave.customize-ui
code --install-extension miguelsolorio.fluent-icons
code --install-extension o4x.base16-tomorrow
code --install-extension atomiks.moonlight
code --install-extension dhedgecock.radical-vscode
code --install-extension dline.CobaltNext
code --install-extension arcticicestudio.nord-visual-studio-code
```

## 10. Extras

Wakatime: você que gosta de dados. Esse plugin te dá análises de tudo que você tem trabalhado

<img width="1964" alt="CleanShot 2022-07-22 at 12 45 25@2x" src="https://user-images.githubusercontent.com/23129218/180503960-a0b91e77-e432-4c6c-b88c-18943eeeba37.png">

```
code --install-extension WakaTime.vscode-wakatime
```

Spell checker: pra não errar na hora de escrever em inglês

<img width="2032" alt="CleanShot 2022-07-22 at 12 51 16@2x" src="https://user-images.githubusercontent.com/23129218/180504719-32b4354e-37e0-4643-acfc-c955c682f092.png">

```
code --install-extension streetsidesoftware.code-spell-checker
```
