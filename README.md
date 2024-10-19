# Script de Varredura de Domínios e Subdomínios

Este script em Bash foi criado para varrer páginas HTML e identificar domínios e subdomínios que estão linkados na página. É uma ferramenta útil para quem precisa analisar links contidos em páginas web.

## Funcionalidade

- Baixa a página HTML especificada.
- Extrai e lista domínios e subdomínios presentes nos links.
- Permite reiniciar a varredura caso existam resultados anteriores.

## Requisitos

- **Bash**: Certifique-se de que você tem um terminal Bash disponível.
- **Ferramentas necessárias**:
  - `wget`: para baixar páginas web.
  - `grep`: para filtrar resultados.
  - `cut`: para manipulação de strings.
  - `sort`: para ordenar resultados.

## Instalação

1. **Clone este repositório**:

   ```bash
   git clone https://github.com/NathanHackSec/domainpage_sh.git
