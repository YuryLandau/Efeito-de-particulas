# Efeito-de-particulas
Pequeno teste em JS

![particles preview](https://github.com/YuryLandau/Efeito-de-particulas/blob/main/src/img/preview.gif)

Etapas:
- Garanta que a aplicação esteja rodando em um Live Server. No meu caso, utilizo a extensão criada por Ritwick Dey.
- Criar um index.html
- Incluir uma div com o id que será chamado posteriormente:
```html
<div id="particles-js"></div>
```
- Importar a biblioteca de particulas em uma tag script: "https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js".
```html
<script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>
```
- criar um arquivo de estilo para atribuir o background e dimensões de #particles-js
```css
#particles {
    background-color: #770099;
    height: 100vh;
    width: 100vw;
}
```
- Em um novo script, carregar a função particlesJS, atribuindo 3 parâmetros:
```javascript
particlesJS.load('container_id', 'arquivo_de_config.json', callbackFunction(){
    console.log('particles.js config carregado');
});
```
- A partir deste momento, é necessário configurar o arquivo particles.json, afim de exibir as particulas da forma desejada.
