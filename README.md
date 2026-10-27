# Exercício LESS

Estilos escritos em LESS, divididos em arquivos (`src/less`) e compilados para `dist/css/main.css`.

Recursos usados:
- **Variáveis**: `src/less/variaveis.less`
- **Divisão de arquivos**: `main.less` importa os demais com `@import`
- **Escapings**: `~"(max-width: 768px)"` e `~"calc(100% - @{espaco-lateral})"`
- **Mapas**: `@cores`, `@botao-primario`, `@botao-secundario`, acessados com `@cores[fundo]`
- **Mixins**: `.centralizar()`, `.transicao()`, `.sombra()`

## Como compilar
```bash
npm install
npm run build
```
Abra o `index.html` no navegador. Use `npm run watch` para recompilar ao salvar.
