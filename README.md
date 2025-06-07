<!DOCTYPE html>
<html lang="pt-BR">
<body>

<h1>🚀 JavaScript Playwright Runner Framework</h1>

<p>
  <b>Framework de automação de testes end-to-end</b> para autenticação, construído com <a href="https://playwright.dev/">Playwright</a> em JavaScript.<br>
  Estrutura organizada e pronta para CI, ideal para acelerar seus testes de login!
</p>

<hr>

<h2>📦 Recursos</h2>
<ul>
  <li>🔗 Estrutura modular seguindo Page Object Model (POM)</li>
  <li>⚡ Testes paralelos com Playwright Test Runner</li>
  <li>📊 Relatórios automáticos em HTML</li>
  <li>🌐 Suporte a múltiplos navegadores</li>
  <li>🚦 Pronto para uso em integração contínua (CI)</li>
</ul>

<h2>🗂️ Estrutura do Projeto</h2>
<pre>
tests/
└── login/
    ├── interactions/
    │   └── LoginInteractions.js     # Métodos de interação para o login
    ├── login.spec.js                # Testes de login
    └── pages/
        └── LoginPage.js             # Page Object do login
playwright-report/                   # Relatórios HTML gerados
test-results/                        # Resultados das execuções
</pre>

<h2>🔧 Pré-requisitos</h2>
<ul>
  <li>⚙️ <a href="https://nodejs.org/">Node.js</a> (18+ recomendado)</li>
  <li>📦 <a href="https://www.npmjs.com/">npm</a> ou <a href="https://yarnpkg.com/">yarn</a></li>
</ul>

<h2>⚙️ Instalação</h2>
<pre>
git clone https://github.com/seu_usuario/javascript_playwright_runner_framework.git
cd javascript_playwright_runner_framework
npm install
</pre>

<h2>▶️ Executando os Testes</h2>
<pre>
npx playwright test
</pre>
<p>🔹 Isso executa todos os testes da pasta <code>tests</code> e gera o relatório HTML em <code>playwright-report</code>.</p>

<h3>📝 Executando testes de um arquivo específico</h3>
<pre>npx playwright test tests/login/login.spec.js</pre>

<h3>📈 Abrindo o relatório de testes</h3>
<pre>npx playwright show-report</pre>

<h2>🛠️ Estrutura dos Testes</h2>
<ul>
  <li><b>LoginPage.js</b> – Page Object com seletores e elementos da tela de login</li>
  <li><b>LoginInteractions.js</b> – Lógica para interações no login (herda o Page Object)</li>
  <li><b>login.spec.js</b> – Casos de teste para múltiplos usuários e senhas</li>
</ul>

<h2>⚙️ Configuração</h2>
<p>
O arquivo <b>playwright.config.js</b> contém configurações para testes paralelos, geração de trace, e escolha de navegadores. Personalize conforme necessário.
</p>

<h2>✨ Personalizando</h2>
<ul>
  <li>Adicione mais testes criando novos arquivos <code>.spec.js</code> em <code>tests/moduloEscolhido</code>.</li>
  <li>Explore a estrutura modular para testar outras áreas do sistema, seguindo o mesmo padrão de organização de pastas.</li>
</ul>

<h2>🪪 Licença</h2>
<p>
Distribuído sob a licença MIT. Veja o arquivo <code>LICENSE</code> para mais informações.
</p>

<hr>
<p>
  🤝 Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.<br>
  <br>
</p>

</body>
</html>
