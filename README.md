
# SafeLogin

App de login fictício pra estudo de **IHC**. Totalmente local e offline.

## Tecnologias

* React + Vite
* CSS puro

## Como rodar

1. Instala:

```bash
npm install
```

2. Roda:

```bash
npm run dev
```

3. Abre no navegador o endereço que aparecer (geralmente `http://localhost:5173`)

### Outros comandos

* Build pra produção: `npm run build`
* Ver o build: `npm run preview`

## Metas de usabilidade

* **Fácil de lembrar**: layout de login normal, só usuário e senha.
* **Fácil de entender**: labels claros, placeholders e mensagens simples.
* **Útil**: autentica o usuário rápido.
* **Seguro (percepção)**: campo de senha escondido, dá pra mostrar, feedback de erro ou sucesso.
* **Eficiente**: poucos cliques, botão “Entrar como visitante” pra agilizar.

## Metas de experiência

* **Bonito**: tema escuro, contraste bom, tipografia legível, layout equilibrado.
* **Agradável**: animações leves, ícone de sucesso, mensagens legais quando erra.
* **Satisfatório**: confirma na hora se acertou, microinterações nos botões.
* **Motivador**: frases tipo “Tente novamente, você consegue!” quando erra.
* **Proveitoso**: resolve direto o que precisa, sem etapas desnecessárias.

## Etapas do projeto

### Segmento 1 ✓

* Tela de login pronta
* Campos de usuário e senha
* Botão com olho pra mostrar/ocultar senha

### Segmento 2 ✓

* Validação offline com React state
* Credenciais fixas:

  * `admin` / `1234`
  * `visitante` / `123visitante`
* Botão “Entrar como visitante” preenche tudo sozinho (valida ao clicar em “Vamos lá”)
* Feedback ao logar:

  * Campos vazios → mensagem de erro
  * Usuário ou senha errados → mensagem de erro
  * Certo → mensagem de sucesso
* Sem redirecionamento


