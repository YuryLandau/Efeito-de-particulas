# Efeito-de-particulas
Pequeno teste em JS

![particles preview](https://j.gifs.com/xnQ8mJ.gif "teste preview")

Etapas:
- Garanta que a aplicação esteja rodando em um Live Server. No meu caso, utilizo a extensão criada por Ritwick Dey.
- Criar um index.html
- Criar uma div#particles-js
- Importar a biblioteca de particulas em uma tag script: "https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js".
- criar um arquivo de estilo para atribuir o background e dimensões de #particles-js
- Em um novo script, carregar a função particlesJS, atribuindo 3 parâmetros:
particlesJS.load('container_id', 'arquivo_de_config.json', callbackFunction(){
    console.log('particles.js config carregado');
});
- A partir deste momento, é necessário configurar o arquivo particles.json afim de exibir as particulas da forma desejada.
