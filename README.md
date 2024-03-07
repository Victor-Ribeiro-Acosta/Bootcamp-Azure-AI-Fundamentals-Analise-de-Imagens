# Projeto de Visão Computacional no Azure

## Etapa 1: Criar recurso de Visão computacional no Azure

- Na pagina inicial, iniciaremos com criar um novo recurso
  
![Tela inicial do Azure](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Analise-de-Imagens/blob/main/Passos/1.png)
  
- Buscaremos nas opçoes de recurso por serviço de IA do Azure

![Recurso de serviços cognitivos do Azure](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Analise-de-Imagens/blob/main/Passos/2.png)

- Selecionamos nossa subscrição, depois definiremos nosso grupo de recursos
- Nomearemos nosso recurso e definiremos o tipo de conta

![Criando um grupo de recursos](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Analise-de-Imagens/blob/main/Passos/3.png)
  
- Ativar a criação do recurso

![Finalizar recurso](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Analise-de-Imagens/blob/main/Passos/4.png)

- Após a conclusão, essa será a tela apresentada

![Reconhecimento facial em imagens](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Analise-de-Imagens/blob/main/Passos/5.png)

## Etapa 2: Acessar o Azure Visual Studio

- Acessar a plataforma https://portal.vision.cognitive.azure.com
- Logar com conta do Azure

## Etapa 3: Acessar serviços de visão computacional

### Detecção de Faces

- No Visual Studio, acessar a guia faces

![Reconhecimento facial em imagens](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Analise-de-Imagens/blob/main/Passos/6.png)

- Selecionar serviço de detectar faces na imagem

![Reconhecimento facial em imagens](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Analise-de-Imagens/blob/main/Passos/7.png)

- Podemos carregar imagens próprias ou usar as imagens de exemplo

![Reconhecimento facial em imagens](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Analise-de-Imagens/blob/main/Passos/8.png)

- Podemos perceber que o serviço consegue identificar rostos na imagem, além de descrever se esse está ou não usando máscara

- O algoritmo parece apresentar um pouco de dificuldade de diferenciar o que é uma mascara cobrindo o rosto da pessoa

### Descrição de uma Imagem

- Esse serviço permite inserir uma imagem e o algoritmo de visão computacional retornará uma descrição dos itens na mesma
- No Visual Studio do Azure, vamos acessar a guia de Análise de Imagens

![Reconhecimento facial em imagens](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Analise-de-Imagens/blob/main/Passos/10.png)

- Vamos escolher o serviço de Add Captions Image.

![Reconhecimento facial em imagens](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Analise-de-Imagens/blob/main/Passos/11.png)

- Na ferramenta de detecçao, inserimos a imagem desejada, a direita dela é possível observar a descrição que o serviço ofereceu

![Reconhecimento facial em imagens](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Analise-de-Imagens/blob/main/Passos/12.png)


### Detecção de Textos em Imagens

- No Visual Studio, vamos buscar a guia de reconhecimento optico de caracteres

![Reconhecimento facial em imagens](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Analise-de-Imagens/blob/main/Passos/13.png)

- Escolheremos o serviço de extração de textos em imagens

![Reconhecimento facial em imagens](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Analise-de-Imagens/blob/main/Passos/14.png)
