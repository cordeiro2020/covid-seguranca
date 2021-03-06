> Este repositório faz parte de uma aplicação voltada para a prevenção do COVID-19 através do diagnóstico e rastreamento de possíveis casos positivos.

# COVID - Segurança

Essa aplicação web possibilita a um segurança verificar a situação de um usuário no sistema (Quanto a possível presença ou não de COVID-19), o encaminhando para que as devidas providências sejam tomadas.

Os micro e nano-serviços  podem ser encontrados no [back-end](https://github.com/cordeiro2020/covid-back).

## Pré-requisitos :heavy_check_mark:

* [node](https://nodejs.org/en/) - v8.0.0 ou superior
* [yarn](https://yarnpkg.com/pt-BR/) - v1.15 ou superior


## Iniciando :zap:

    git clone https://github.com/cordeiro2020/covid-seguranca.git
    cd covid-seguranca
    yarn install
   
   Edite suas credências do firebase em `.env.local` :ok_hand:
   Não esqueça de inicializar o método de login "Email\Senha" no firebase, e também o firestore
    
    yarn start

## Build :hammer:

    yarn build

## Deployment :rocket:

    Usamos o deploy com CI/CD  configurado no arquivo `.gitlab-ci.yml` mas você pode usar qualquer CI/CD que quiser, ou fazer deploy usando o firebase-CLI.

## Feito com :package:

* [create-react-app](https://github.com/facebook/create-react-app) - Components
* [firebase](https://www.npmjs.com/package/firebase) - Realtime Database / Notifications

## Quem participou? :busts_in_silhouette:

:construction: