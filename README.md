# Painel Participativo LUSIA + COMPUR

Este repositório foi preparado para publicação em GitHub Pages como formulário acessível por QR Code.

## Publicação no GitHub Pages

1. Acesse o repositório no GitHub.
2. Vá em `Settings` → `Pages`.
3. Em `Build and deployment`, selecione:
   - Source: `Deploy from a branch`
   - Branch: `gh-pages` / `root`
4. Salve.
5. Aguarde alguns minutos até a publicação da página.

URL pública esperada:

https://gustavomarinhosmu.github.io/Painel-Participativo-COMPUR/

## QR Code

Para abrir o formulário via QR Code, utilize a URL acima em qualquer gerador de QR Code. Exemplo:

https://api.qrserver.com/v1/create-qr-code/?size=400x400&data=https://gustavomarinhosmu.github.io/Painel-Participativo-COMPUR/

## Coleta e exportação das respostas

O formulário salva as respostas no navegador do usuário e também oferece o botão:

- `Encerrar coleta e exportar CSV`

Ao clicar, o navegador baixa automaticamente um arquivo `.csv` com todas as respostas coletadas até o momento.

## Observação importante

Como o GitHub Pages é estático, as respostas ficam armazenadas no navegador do usuário até que o arquivo seja exportado. Em ambientes com coleta em vários celulares, o ideal é conectar a coleta a uma ferramenta externa (Google Sheets, Supabase, Firebase, Airtable, etc.) para centralizar as respostas.

## Arquivo principal

- `index.html`
