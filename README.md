# FairFax Seguro Auto

![example of app running](https://media.giphy.com/media/c0N66cY9ESIy9oT0yx/giphy.gif)


Essa é uma aplicação, desenvolvida em flutter, que se integra com um serviço de Deep Learning para verificar o estado de conservação (ou até mesmo acompanhar a existência) do bem assegurado para aquisição e acionamento de seguros.

Por meio do app desenvolvido em flutter, conseguimos capturar uma foto do veículo, e assim fazer a triagem a fim de avaliar se o mesmo está com um estado de conservação aceitável.

## como foi feito?

Nossa triagem foi feita, utilizando um serviço em cloud, de alta disponibilidade, da microsoft, chamado [Custon Vision AI](https://www.customvision.ai/), onde lá na plataforma, temos um projeto nosso com um banco de imagens de carros batidos ou carros integros. e assim treinamos um modelo de Deep Learning,  que identifica os padrões e assim determina se um carro está batido ou não.

<a title="plataforma" href="https://flutter.dev/" target="_blank" rel="noreferrer"> 
    <img src="https://user-images.githubusercontent.com/35856303/172084043-2de788d7-ac38-45b5-b4fb-db9c62cfcd4b.png" alt="plataforma" width="600" height="300"/> 
</a>


O próximo passo foi capturar as imagens via aplicativo flutter, e envia-las para o backend, assim recebemos uma resposta, do valor em cima do modelo treinado, quanta similaridade ela possui em relação ao modelo de carro batido, ou de carro integro.

## Roadmap futuro
- [X] Avaliar as condições de estado(Integro ou batido)
- [ ] identificar numeração da placa, para já fazer a consulta automática do veículo
- [ ] identificar o número de chassi, para assim verificar se os dados da placa batem com o chassi.
- [ ] aperfeiçoar o modelo, para assim identificar possiveis avarias visualmente no motor, e assim classificar como grupo de risco o carro.
- [ ] Contratar o seguro para a etapa final.
- [ ] Identificar carteira de motorista do proprietário/condutor principal.
- [ ] Avaliar dados futuros do condutor.


## Funcionalidades

- Fluxo de cadastro do carro

- Tirar foto do veículo

- Avaliar as condições de estado(Integro ou batido)

- Planos de integrar com o [backend](https://github.com/FairFaxSeguros/fairfax-auto-seguro-API)

## Tecnologias

As ferramentas e frameworks utilizados no desenvolvimento

<a title="Flutter" href="https://flutter.dev/" target="_blank" rel="noreferrer"> 
    <img src="https://storage.googleapis.com/cms-storage-bucket/4fd0db61df0567c0f352.png" alt="flutter" width="60" height="60"/> 
</a>
<a title="dart" href="https://dart.dev/" target="_blank" rel="noreferrer"> 
    <img src="https://dart.dev/assets/shared/dart/icon/64.png" alt="dart" width="60" height="60"/> 
</a>
<a title="custom vison" href="https://www.customvision.ai/" target="_blank" rel="noreferrer"> 
    <img src="https://connectoricons-prod.azureedge.net/releases/v1.0.1481/1.0.1481.2460/cognitiveservicescustomvision/icon.png" alt="custom vision" width="60" height="60"/> 
</a>

## Profissionais responsáveis pelo projeto:

- Marina Bittencourt - **Produto**

<a href="https://www.linkedin.com/in/marinarosabittencourt/" target="_blank">
<img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">
</a>

- Gabriella Feliciano - **Agilista**

- Leonardo Bittencourt - **Desenvolvedor Backend**

<a href="https://github.com/leonardo-otero390" target="_blank">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"> 
<a href="www.linkedin.com/in/leonardo-otero390" target="_blank">
<img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">
</a>

- Enzo Danjour - **Desenvolvedor Mobile**

<a href="https://github.com/enzodanjour" target="_blank">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"> 
<a href="https://www.linkedin.com/in/enzo-danjour/" target="_blank">
<img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">
</a>
