# GNA Finanças no iPhone, de graça

O app fica hospedado de graça no GitHub Pages e é instalado pela tela inicial do iPhone. Ele abre em tela cheia, com ícone próprio, e funciona sem internet. Não aparece na App Store e não tem nenhum custo.

**O que tem nesta pasta**

| Arquivo | Para que serve |
|---|---|
| `index.html` | O app |
| `manifest.webmanifest` | Nome, ícone e cores do app instalado |
| `sw.js` | Guarda o app no celular para abrir sem internet |
| `icons/` | Ícones do app |

---

## 1. Colocar o app na internet (uma vez, uns 10 minutos)

1. Crie uma conta gratuita em **github.com**.
2. Clique em **+ → New repository**. Nome: `gna-financas`. Marque **Public** e clique em **Create repository**.
3. Clique em **uploading an existing file**, arraste **todo o conteúdo desta pasta** (o `index.html`, o `manifest.webmanifest`, o `sw.js` e a pasta `icons`) e clique em **Commit changes**.
4. No repositório, vá em **Settings → Pages**. Em **Branch**, escolha `main` e `/ (root)` e clique em **Save**.
5. Espere 1 a 2 minutos e recarregue a página. O endereço do app aparece no topo, assim:
   `https://SEU-USUARIO.github.io/gna-financas/`

O código do app fica público, mas nenhum dado seu vai para o GitHub: os lançamentos ficam só no celular de quem usa.

## 2. Instalar no iPhone

1. Abra o endereço no **Safari** (precisa ser o Safari).
2. Toque no botão **Compartilhar** (o quadrado com a seta para cima).
3. Role e toque em **Adicionar à Tela de Início** → **Adicionar**.
4. A partir daí, abra sempre pelo ícone **GNA Finanças** na tela inicial.

Sua esposa pode instalar no celular dela do mesmo jeito, com o mesmo endereço. Cada celular guarda os próprios lançamentos.

No Android, abra o endereço no Chrome e toque em **Instalar app** (ou menu ⋮ → **Adicionar à tela inicial**).

## 3. Fazer backup (importante)

Os lançamentos ficam guardados dentro do app no celular. Se você apagar o ícone da tela inicial ou limpar os dados do Safari, eles se perdem.

- **Fazer backup:** no app, vá em **Família → Seus dados → Fazer backup** e escolha **Salvar em Arquivos** (pode ser no iCloud Drive).
- **Restaurar:** em **Família → Seus dados → Restaurar backup**, escolha o arquivo `gna-financas-backup-....json`.

Uma vez por semana é um bom ritmo. O app mostra a data do último backup.

O backup também serve para passar os dados para um celular novo: faça o backup no antigo e restaure no novo.

## 4. Atualizações

Quando quiser mudar algo no app, peça a mudança. Eu atualizo o `index.html`; você envia o arquivo novo para o repositório no GitHub (**Add file → Upload files**, por cima do antigo). O app pega a versão nova na próxima vez que for aberto com internet. Se não aparecer, feche e abra o app de novo.
