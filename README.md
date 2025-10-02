
# 🍲 Plataforma de Doação de Alimentos

## 1. Introdução

A insegurança alimentar é um desafio social que atinge milhões de pessoas em situação de vulnerabilidade. Muitas instituições e ONGs atuam no combate à fome, mas frequentemente enfrentam dificuldades em alcançar doadores de forma ágil.

Este projeto propõe o desenvolvimento de um **site responsivo** que conecta diretamente **doadores** (indivíduos, empresas e estabelecimentos) a **instituições** cadastradas, promovendo transparência, eficiência e impacto social.

---

## 2. Objetivo do Projeto

* Criar um  **front-end funcional, intuitivo e seguro** .
* Implementar páginas que permitam:
  * Cadastro e login de usuários (doadores e instituições).
  * Registro e acompanhamento de doações.
  * Solicitação e gerenciamento de alimentos.
  * Exibição de informações, estatísticas e conteúdos educativos.
* Priorizar **usabilidade, acessibilidade (WCAG)** e  **responsividade mobile-first** .

---

## 3. Estrutura do Site

### 🔹 Páginas Principais

* **Página Inicial**
  * Apresentação do propósito da plataforma.
  * Dados sobre insegurança alimentar.
  * Benefícios da doação.
* **Cadastro/Login**
  * Área para **doadores** e  **instituições** .
  * Autenticação segura.
* **Dashboard do Doador**
  * Cadastro de alimentos disponíveis para doação.
  * Histórico de doações realizadas.
* **Dashboard da Instituição**
  * Solicitação de alimentos.
  * Gerenciamento de recebimentos.
  * Histórico de doações recebidas.
* **Listagem de Doações Disponíveis**
  * Página pública ou restrita às instituições.
  * Exibição de doações cadastradas.
* **Transparência**
  * Estatísticas de alimentos doados.
  * Quantidade de instituições beneficiadas.
* **Blog/Artigos**
  * Conteúdos educativos sobre insegurança alimentar e solidariedade.
* **FAQ (Perguntas Frequentes)**
  * Como funciona a plataforma?
  * Como me cadastrar como voluntário/doador?
  * O site garante anonimato?
* **Contato e Suporte**
  * Formulário para envio de dúvidas e sugestões.
  * Links úteis para serviços de emergência.

---

## 4. Layout e Design

* **Paleta de cores sugerida:**
  * 🟢 Verde (solidariedade, esperança)
  * 🟠 Laranja (acolhimento, energia)
  * ⚪ Branco / tons neutros (clareza, simplicidade)
* **Tipografia:**
  * Fonte limpa e legível (ex:  *Roboto* ,  *Open Sans* ).
* **Componentes reutilizáveis:**
  * Header fixo com menu de navegação.
  * Cards para doações, artigos e estatísticas.
  * Botões com estilo consistente ( *Bootstrap* ).
  * Formulários responsivos com validação.
* **Responsividade:**
  * Design  **mobile-first** .
  * Breakpoints para tablets e desktops.

---

## 5. Tecnologias Sugeridas

* **Linguagens:** HTML5, CSS3, JavaScript ES6+
* **Framework CSS:** Bootstrap 5
* **Acessibilidade:** Padrões **WCAG 2.1**
* **Controle de versão:** Git/GitHub
* **Deploy:** Vercel / Netlify / GitHub Pages

---

## 6. Estrutura de Pastas

<pre class="overflow-visible!" data-start="3392" data-end="3936"><div class="contain-inline-size rounded-2xl relative bg-token-sidebar-surface-primary"><div class="sticky top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-bash"><span><span>📂 doacao-alimentos-frontend
├── 📁 public/          </span><span># Arquivos estáticos (favicon, index.html)</span><span>
├── 📁 src/
│   ├── 📁 assets/      </span><span># Imagens, ícones, estilos globais</span><span>
│   ├── 📁 components/  </span><span># Componentes reutilizáveis (Navbar, Footer, Cards)</span><span>
│   ├── 📁 pages/       </span><span># Páginas principais (Home, Login, Dashboard, etc.)</span><span>
│   ├── 📁 services/    </span><span># Conexão com APIs (ex: cadastro, login, listagem)</span><span>
│   ├── App.js          </span><span># Componente principal</span><span>
│   └── index.js        </span><span># Ponto de entrada</span><span>
└── package.json        </span><span># Dependências e scripts</span><span>
</span></span></code></div></div></pre>

---

## 7. Conclusão

O front-end da **Plataforma de Doação de Alimentos** deve unir **tecnologia e solidariedade** em prol de uma causa social. Com um design acessível, intuitivo e responsivo, a aplicação permitirá a conexão direta entre doadores e instituições, fortalecendo iniciativas contra a fome e a desigualdade.
