## ⚠️ Atenção, Colaboradores!!

Para conectar o **VS Code** (ou outra IDE) ao repositório no **GitHub** e realizar ações como **clone**, **init**, **add**, **commit**, **push**, **pull**, **branches** e **PRs** (Pull Requests), é **obrigatório ter o Git instalado** em sua máquina.

O **Git** é o sistema responsável pelo **controle de versionamento distribuído**, permitindo que todos trabalhem em paralelo com segurança e rastreabilidade.

---

### 🧩 Extensões Recomendadas

Para facilitar o fluxo de versionamento e manter uma colaboração organizada, instale as seguintes extensões no **VS Code**:

- 🧠 **[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)** – fornece insights avançados sobre commits, histórico e autores de cada linha de código.  
- 🔁 **[GitHub Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)** – permite criar, revisar e gerenciar PRs diretamente pelo VS Code.

Nosso fluxo **exige o uso de PRs** para garantir **segurança**, **organização** e **validação colaborativa** do código.

---

### 🌿 Boas Práticas de Branches e Commits

- Sempre que for desenvolver uma **nova feature**, **crie uma nova branch** específica para ela.  
- Após concluir o desenvolvimento, **publique a branch** e **abra uma Pull Request (PR)**.
- **Nunca tente commitar algo sem criar uma branch separada pra trabalhar na feature ou fix**.
- **Mantenha commits semânticos**, claros e objetivos.

#### 🎥 Aprendizado
Se você ainda não conhece esses conceitos, veja os vídeos abaixo (são breves):

- [📘 Commits Semânticos](https://youtu.be/P_DeVtGP3VE?si=1RhTkEvAnrLkGMz0)  
- [🔍 GitLens](https://youtu.be/yNhFgdGqDDE?si=NxFAdlIXp-zVduXe)  
- [🔄 GitHub Pull Requests](https://youtube.com/shorts/2CxHfU1tO-E?si=qS4_9tTiyXhj6Bt5)

---

## 🧱 Convenções do Projeto

   - O código e os commits devem ser escritos em **inglês**. Apenas labels e textos exibidos ao usuário no **Frontend** devem estar em **português**.
   - Constantes devem ser declaradas em **letras maiúsculas** e separadas por **underline**. Exemplo:  
     ```javascript
     const DEFAULT_SELECT_VALUE = 'Todos';
     ```
   - Variáveis e Funções devem seguir o padrão **camelCase**, iniciando com letra minúscula e separando as palavras por letras maiúsculas. Exemplo:
     ```javascript
     let selectedUserId
     function isFirstAttempt() {}
     ```
   - Componentizar é **organizar e otimizar o código**, separando responsabilidades em partes menores e reutilizáveis.

  ---
  
  ### 🚀 Por que seguir esses padrões?
  
  Seguir essas convenções e aprender essas ferramentas vai enriquecer sua experiência e maturidade profissional, pois são práticas amplamente utilizadas no mercado há anos.
  Colabore com atenção, organização e propósito — cada commit é um passo para um código mais limpo e um time mais forte.
