# ObraGest Landing Page

Landing page comercial do ObraGest, uma solução para gestão de obras e reformas. O site apresenta benefícios, diferenciais, processo de entrega, documentação legal e canais de contato usando HTML/CSS puro.

## Estrutura

```
/
├─ index.html                  # Página principal
├─ logos/                      # Logos, favicons e manifest
│  └─ favicon_io/             # Conjunto completo de favicons e manifest
└─ README.md
```

## Como rodar localmente

1. Clone o repositório:
   ```bash
   git clone <seu-repo>
   cd <seu-repo>
   ```
2. Abra `index.html` diretamente no navegador ou use um servidor estático simples:
   ```bash
   npx serve .
   ```

## Deploy na Vercel

1. Publique este diretório em um repositório GitHub.
2. Na Vercel, escolha **New Project** > **Import Git Repository** e selecione o repositório.
3. A Vercel detectará o projeto como “Static Site”. Basta confirmar:
   - Build Command: `N/A`
   - Output Directory: `.` (raiz)
4. Conclua o deploy. Cada push na branch configurada disparará novos deploys.

## Personalização

- Logos e favicons ficam em `logos/`.
- Para atualizar textos ou cores edite apenas `index.html`.
- O arquivo `logos/favicon_io/site.webmanifest` já está referenciado no `<head>` para suportar ícones em diferentes dispositivos.

## Licença

Uso interno do proprietário do projeto.
