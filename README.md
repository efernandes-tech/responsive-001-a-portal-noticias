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
- Devise pixel ratio: é a razão entre o número de pixels físicos da tela e os pixels lógicos (ou pontos, ou device-independent pixels).
- Compressive images: é não bitolar pq muitas vezes uma imagem bastante otimizada é suficiente para várias resoluções e dispositivos.
- Content parity: é considerada uma boa prática que o usuário, na versáo mobile de uma página, consiga fazer tudo aquilo que ele faz no desktop.
- Não existe "contexto mobile"!
    - Ofereça todo o conteúdo e todos os cenários para que o usuário possa optar pelo aparelho que ele quiser.
- Priorização de conteúdo.
- Mobile-first.
    - Priorizamos a criação de sites próprios para smartphones e tablets e só depois pensamos em sua versão para desktop.
- Touch-first.
    - Os botões devem ter, em média, 50px (9mm).
    - Sem hover.
- Lições:
    - Não tente detectar em qual navegador o usuário está.
    - Pense em todas as possibilidades de uso. O usuário pode e deve ter a vontade de navegar como ele quiser.
    - Saiba o que o usuário quer visualizar primeiro em sua home page. Se ele quiser instalar algum aplicativo, deixe-o navegar, mas não impeça o acesso ao site.
        - Não obrigue seu usuário a fazer aquilo que muito provavelmente não quer. Ele deve ser livre para navegar.
    - Preste atenção naquilo que é mais importante ser mostrado na página. Uma página que à primeira vista só mostra o menu de opções confunde o usuário.
    - Mantenha o máximo de features em sua página. Não há razão para diminuir a quantidade de ferramentas para o usuário se elas não influenciam no resto do site.
        - Não desabilite o zoom com:
            <meta name="viewport" content="width=device-width, user-scalable=no">
- O Futuro é mobile.
