# renanloureiro-dev · marca

Xícara rubro-negra em pixel art 16 × 16: café, as cores do time e o video game retrô.

## O que tem aqui

| Pasta | Arquivo | Para quê |
|---|---|---|
| `avatar/` | `avatar-escuro-512.png` | **Foto da organização no GitHub** (a principal) |
| | `avatar-escuro-1024.png`, `avatar-escuro.svg` | Mesma coisa em tamanho maior e em vetor |
| | `avatar-vermelho-*` | Variação com fundo vermelho (redes, perfis secundários) |
| `simbolo/` | `simbolo-para-fundo-escuro.*` | Só a xícara, sem fundo, para fundos escuros |
| | `simbolo-para-fundo-claro.*` | Só a xícara com contorno preto, para fundos claros |
| `lockup/` | `lockup-para-fundo-escuro.*`, `lockup-para-fundo-claro.*` | Xícara + nome. O SVG tem o texto em curvas (não precisa da fonte instalada) |
| `favicon/` | `favicon.ico` (16, 32, 48), `favicon.svg`, `favicon-32.png` | Sites dos projetos |
| | `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | Ícone de app / PWA / atalho no iPhone |
| `github/` | `social-preview-1280x640.png` | Prévia social dos repositórios |
| | `readme-banner-1280x320.png` | Banner do README da organização |
| | `xicara-animada.gif` | Xícara com o vapor mexendo, para usar em README |
| | `profile-README.md` | Modelo do README da organização |

## Como aplicar no GitHub

1. **Foto da organização:** github.com/organizations/renanloureiro-dev/settings/profile → *Profile picture* → envie `avatar/avatar-escuro-512.png`. Envie o quadrado como está; o GitHub arredonda os cantos sozinho.
2. **README da organização:** crie o repositório público `.github` na organização, com o arquivo `profile/README.md`. Use `github/profile-README.md` como modelo e coloque o banner e o GIF na pasta `profile/`.
3. **Prévia social de cada repositório:** Settings do repositório → *Social preview* → envie `github/social-preview-1280x640.png` (ou uma cópia com o nome do projeto).

## Paleta

| Nome | Hex | Uso |
|---|---|---|
| Preto | `#14121C` | Fundo do avatar, texto em fundo claro |
| Carvão | `#3B3445` | Faixa preta da xícara |
| Vinho | `#8E1B2A` | Sombra do vermelho |
| Vermelho | `#D1202F` | Faixas da xícara, "-dev" em fundo claro |
| Vermelho luz | `#F25A4A` | Brilho do vermelho, "-dev" em fundo escuro |
| Creme | `#FFF1E8` | Porcelana, nome em fundo escuro |
| Creme sombra | `#D9C7BA` | Sombra da porcelana |
| Café | `#4A2416` | Café na xícara |
| Crema | `#8A4A28` | Brilho do café |
| Vapor | `#C2C3C7` | Vapor |

## Tipografia

**Jersey 10** (Google Fonts, licença SIL Open Font License), em minúsculas: `renanloureiro` na cor do texto e `-dev` em vermelho.

## Regras

- **Escala inteira:** a grade é de 16 × 16. Amplie só em múltiplos de 16 (32, 48, 64, 128, 256, 512…) e sempre com "vizinho mais próximo" (nearest neighbor), nunca suavizado, senão os pixels borram.
- **Sem distorcer**, girar, trocar cores fora da paleta ou adicionar sombra/brilho.
- **Respiro:** deixe em volta pelo menos 2 "pixels" da grade (1/8 do lado).
- Em fundo claro use o símbolo com contorno ou o avatar com fundo; a porcelana creme some no branco.
- As cores e listras lembram o rubro-negro, mas a marca não usa escudo, mascote ou nome de clube. Mantenha assim.
