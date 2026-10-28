# O Gui Resolve — site

Página única do **O Gui Resolve**: manutenção de notebook e serviços digitais em Fortaleza. É o link da bio do Instagram [@oguiresolve](https://instagram.com/oguiresolve) e dos envios no WhatsApp.

## Estrutura

- `index.html`: a página inteira (HTML e CSS, sem framework e sem build)
- `assets/`: as ilustrações do Gui em WebP

## Como editar

- **Número do WhatsApp:** constante `WHATSAPP` no `<script>` do fim do `index.html`.
- **Preços e serviços:** seção `#servicos` do `index.html`.
- **Projetos do Lado B:** lista `.projetos` na seção `#lado-b`.

Para ver localmente, abra o `index.html` no navegador.

## Publicação

Site estático. Qualquer push na `main` publica a nova versão quando o repositório está ligado à Vercel.
