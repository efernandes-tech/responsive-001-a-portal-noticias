# responsive-001-a-portal-noticias

##### Anotações:
- Não existe mobile, o que existe são dispositivos com características próprias.
- Não use as media queries padrão, crie as suas de acordo com o seu layaout.
- No surgimento dos dispositivos mobiles com tamanhos de telas em torno de 320px, para não quebrar os sites existentes, eles começaram a simular o tamanho de tela com geralmente 980px (ex.: iphone).
	- Então hj para forçar o uso do tamanho nativo a meta tag viewport deve ser utilizada.
		<meta name="*viewport*" content="width=device-width">
- Estratégia de desenvolvimento: desktop browser, emuladores, e debug remoto em dispositivos reais.
	- Monte o seu device lab (dica para ios: ipod touch é mais parato).
- Use o WEINRE para debug remoto em dispositivos genéricos (usa o nodejs).
    - Instalar com o NPM:
        npm install -g weinre
    - Iniciar pelo terminal:
        weinre
    - Acesse o localhost indicado.
    - Copie a tag <script> e cole no topo da pagina que vc deseja debugar.
    - Acesse a pagina pelo dispositivo.
    - No weinre acesse a pagina de debug.

- FAZER EXERCICIO 2 DA AULA 4