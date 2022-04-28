# PWA_Utilizando_React

<h1> Sejam bem-vindos ao meu Projeto Progressive Web Application com React.</h1> 

<h3> Desenvolvendo uma Progressive Web Application com React para mapear os dados do COVID19 pelo mundo. </h3>
Curso oferecido gratuitamente pela plataforma online <a href="https://dio.me/" rel="nofollow"><strong> Digital Innovation One</strong></a>


<h2 dir="auto"><a id="user-content--objetivo-do-projeto" class="anchor" aria-hidden="true" href="#-objetivo-do-projeto"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><g-emoji class="g-emoji" alias="dart" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3af.png">🎯</g-emoji> Objetivo do Projeto</h2>

<p dir="auto"> Criar uma aplicação <strong> Progressive Web Application (PWA) </strong> utilizando <strong>React</strong> para ser executada no browser e contendo algumas funcionalidades de um aplicativo nativo. Tudo rápido e fácil, sem precisar subir para a Play Store ou App Store. </p>


<h2 dir="auto"><a id="user-content--pré-requistos" class="anchor" aria-hidden="true" href="#-pré-requistos"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>
<g-emoji class="g-emoji" alias="stop_sign" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f6d1.png">🛑</g-emoji> Pré-requistos
</h2>

<ul class="contains-task-list">
  <li class="task-list-item">
    <p dir="auto"><input type="checkbox" id="" disabled="" class="task-list-item-checkbox" checked=""> Node 10</p>
  </li>
  <li class="task-list-item">
    <p dir="auto"><input type="checkbox" id="" disabled="" class="task-list-item-checkbox" checked=""> NPM e NPX</p>
  </li>
</ul>

<h2 dir="auto"><a id="user-content---guia-" class="anchor" aria-hidden="true" href="#--guia-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a> <g-emoji class="g-emoji" alias="vertical_traffic_light" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f6a6.png">🚦</g-emoji> Guia </h2>



<h2 dir="auto"><a id="user-content--tecnologias-utilizadas" class="anchor" aria-hidden="true" href="#-tecnologias-utilizadas"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><g-emoji class="g-emoji" alias="hammer_and_wrench" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f6e0.png">🛠</g-emoji> Tecnologias Utilizadas</h2>






<h2 dir="auto"><a id="user-content--links-úteis" class="anchor" aria-hidden="true" href="#-links-úteis"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><a id="user-content--links-úteis" href="#-links-úteis"></a><g-emoji class="g-emoji" alias="link" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f517.png">🔗</g-emoji>Scripts Disponíveis</h2>


<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Este projeto foi inicializado com </font></font><a href="https://github.com/facebook/create-react-app"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Create React App</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> .</font></font></p> 


<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">No diretório do projeto, você pode executar:</font></font></p>

<h3 dir="auto"><a id="user-content-yarn-start" class="anchor" aria-hidden="true" href="#yarn-start"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><code>yarn start</code></h3>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Executa o aplicativo no modo de desenvolvimento. </font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
Abra </font></font><a href="http://localhost:3000" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://localhost:3000</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> para visualizá-lo no navegador.</font></font></p>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">A página será recarregada se você fizer edições. </font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
Você também verá erros de lint no console.</font></font></p>

<h3 dir="auto"><a id="user-content-yarn-test" class="anchor" aria-hidden="true" href="#yarn-test"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><code>yarn test</code></h3>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Inicia o executor de teste no modo de relógio interativo. </font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
Consulte a seção sobre como </font></font><a href="https://facebook.github.io/create-react-app/docs/running-tests" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">executar testes</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> para obter mais informações.</font></font></p>

<h3 dir="auto"><a id="user-content-yarn-build" class="anchor" aria-hidden="true" href="#yarn-build"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><code>yarn build</code></h3>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Compila o aplicativo para produção na </font></font><code>build</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pasta. </font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
Ele agrupa corretamente o React no modo de produção e otimiza a compilação para o melhor desempenho.</font></font></p>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">A compilação é minificada e os nomes dos arquivos incluem os hashes. </font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
Seu aplicativo está pronto para ser implantado!</font></font></p>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Consulte a seção sobre </font></font><a href="https://facebook.github.io/create-react-app/docs/deployment" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">implantação</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> para obter mais informações.</font></font></p>

<h3 dir="auto"><a id="user-content-yarn-eject" class="anchor" aria-hidden="true" href="#yarn-eject"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><code>yarn eject</code></h3>

<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nota: esta é uma operação unidirecional. </font><font style="vertical-align: inherit;">Uma vez que você </font></font><code>eject</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, você não pode voltar!</font></font></strong></p>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Se você não estiver satisfeito com a ferramenta de compilação e as opções de configuração, poderá fazê-lo </font></font><code>eject</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">a qualquer momento. </font><font style="vertical-align: inherit;">Este comando removerá a dependência de compilação única do seu projeto.</font></font></p>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Em vez disso, ele copiará todos os arquivos de configuração e as dependências transitivas (webpack, Babel, ESLint, etc) diretamente em seu projeto para que você tenha controle total sobre eles. </font><font style="vertical-align: inherit;">Todos os comandos, exceto </font></font><code>eject</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, ainda funcionarão, mas eles apontarão para os scripts copiados para que você possa ajustá-los. </font><font style="vertical-align: inherit;">Neste ponto você está por conta própria.</font></font></p>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Você não precisa usar nunca </font></font><code>eject</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">. </font><font style="vertical-align: inherit;">O conjunto de recursos com curadoria é adequado para implantações pequenas e médias, e você não deve se sentir obrigado a usar esse recurso. </font><font style="vertical-align: inherit;">No entanto, entendemos que essa ferramenta não seria útil se você não pudesse personalizá-la quando estiver pronto para isso.</font></font></p>



<h2 dir="auto"><a id="user-content--links-úteis" class="anchor" aria-hidden="true" href="#-links-úteis"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><g-emoji class="g-emoji" alias="link" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f517.png">🔗</g-emoji> Links Úteis</h2>



<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Você pode aprender mais na </font></font><a href="https://facebook.github.io/create-react-app/docs/getting-started" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">documentação do Create React App</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> .</font></font></p>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Para aprender o React, confira a </font></font><a href="https://reactjs.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">documentação do React</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> .</font></font></p>

<h3 dir="auto"><a id="user-content-code-splitting" class="anchor" aria-hidden="true" href="#code-splitting"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Divisão de código</font></font></h3>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Esta seção foi movida para aqui: </font></font><a href="https://facebook.github.io/create-react-app/docs/code-splitting" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://facebook.github.io/create-react-app/docs/code-splitting</font></font></a></p>

<h3 dir="auto"><a id="user-content-analyzing-the-bundle-size" class="anchor" aria-hidden="true" href="#analyzing-the-bundle-size"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Analisando o tamanho do pacote</font></font></h3>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Esta seção foi movida para aqui: </font></font><a href="https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size</font></font></a></p>

<h3 dir="auto"><a id="user-content-making-a-progressive-web-app" class="anchor" aria-hidden="true" href="#making-a-progressive-web-app"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Fazendo um aplicativo da Web progressivo</font></font></h3>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Esta seção foi movida para aqui: </font></font><a href="https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app</font></font></a></p>

<h3 dir="auto"><a id="user-content-advanced-configuration" class="anchor" aria-hidden="true" href="#advanced-configuration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Configuração avançada</font></font></h3>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Esta seção foi movida para aqui: </font></font><a href="https://facebook.github.io/create-react-app/docs/advanced-configuration" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://facebook.github.io/create-react-app/docs/advanced-configuration</font></font></a></p>

<h3 dir="auto"><a id="user-content-deployment" class="anchor" aria-hidden="true" href="#deployment"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Desdobramento, desenvolvimento</font></font></h3>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Esta seção foi movida para aqui: </font></font><a href="https://facebook.github.io/create-react-app/docs/deployment" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://facebook.github.io/create-react-app/docs/deployment</font></font></a></p>

<h3 dir="auto"><a id="user-content-yarn-build-fails-to-minify" class="anchor" aria-hidden="true" href="#yarn-build-fails-to-minify"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><code>yarn build</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">não consegue minificar</font></font></h3>

<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Esta seção foi movida para aqui: </font></font><a href="https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify</font></font></a></p>


<div data-target="readme-toc.content" class="Box-body px-5 pb-5">
<article class="markdown-body entry-content container-lg" itemprop="text"><h2 dir="auto"><a id="user-content-pwa-do-showing-covid19-cases" class="anchor" aria-hidden="true" href="#pwa-do-showing-covid19-cases"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>PWA do Showing COVID19 Cases</h2>
<p dir="auto">Host: <a href="https://covid19pwa.netlify.app/" rel="nofollow">https://covid19pwa.netlify.app/</a></p>
</article>
</div>









<h2 dir="auto"><a id="user-content---contribuindo-" class="anchor" aria-hidden="true" href="#--contribuindo-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a> <g-emoji class="g-emoji" alias="handshake" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f91d.png">🤝</g-emoji> Contribuindo </h2>


<p dir="auto">Este repositório foi criado para fins de estudo, então contribua com ele. Se te ajudei de alguma forma, ficarei feliz em
saber. E caso você conheça alguém que se identidique com o conteúdo, não deixe de compatilhar.</p>



<p dir="auto"> Projeto desenvolvido utilizando a ajuda e os conhecimentos do Especialista: 
<a href="https://github.com/Tautorn" rel="nofollow">Bruno </a></p>















