# dub-videos-project
Estrutura e configuração para executar o projeto DubBideos
## Estrutura
Este projeto possui 4 componentes:  
* [Interface front-end](https://github.com/juliano-lopes/dub-videos-front-end?tab=readme-ov-file)  
* [Main Dub Videos API](https://github.com/juliano-lopes/main-dub-videos-api)  
* [Transcription API](https://github.com/juliano-lopes/transcription-api)  
* [Text To Speech API](https://github.com/juliano-lopes/text-to-speech-api)  
Assim clone este repositório e depois clone os 4 repositorios anteriores em sua raiz, onde se encontram 3 outros arquivos:
* Readme.md que contém estas  instruções;  
* .env que possui as variáveis de ambiente necessárias;  
* docker-compose.yml para subir os 4 componentes.

## Chaves do projeto
* Coloque o arquivo de crendenciais JSON em cada api no caminho api/config/
* no arquivo .env, coloque a chave Gemini como valor da chave GEMINI_API_KEY

## Como executar:

Após seguir as instruções apresentadas, na raiz do projeto execute via linha de comando:
**docker-compose up -d**  
Assim os 4 componentes serão executados e o acesso e e testes poderão ser realizados  de acordo com as respectivas orientações contidas no readme.md de cada repositório.