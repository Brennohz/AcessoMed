# AcessoMed

**Informação para encontrar caminhos de acesso ao seu medicamento.**

**Situação:** proposta inicial em avaliação. Nome provisório. Aplicação ainda não implementada; integrações comerciais e relações de equivalência ainda serão validadas.

## 1. Problema

Uma pessoa que recebeu uma prescrição pode precisar consultar diferentes fontes para descobrir se a apresentação consta no Farmácia Popular e localizar onde poderia retirar.

O problema delimitado pelo projeto é o esforço necessário para reunir essas informações e comparar caminhos de acesso ao medicamento prescrito. O sistema pretende reduzir esse esforço com uma consulta organizada e fontes identificadas.

## 2. Público e contexto

Pessoas adultas e idosas que precisam adquirir medicamentos prescritos e familiares que auxiliam nessa aquisição, especialmente quem precisa comparar custos. A consulta será por navegador de celular ou computador.

## 3. Solução proposta

O usuário pesquisa um medicamento e confirma concentração e apresentação. O resultado reúne:

**Acesso gratuito:** correspondência com o elenco do Farmácia Popular, orientações de acesso e estabelecimentos credenciados no recorte escolhido.

**Compra online:** ofertas do produto exato, com loja, quantidade, preço, condições, link e data da coleta.

### Funcionalidades do protótipo

- Busca por nome ou princípio ativo dentro do catálogo validado.
- Seleção explícita de concentração, forma farmacêutica e apresentação.
- Resultado de correspondência com o Farmácia Popular.
- Consulta de estabelecimentos credenciados por município.
- Comparação de ofertas

## 4. Dados públicos, fontes e dependências

| Fonte | Uso previsto | Situação |
|---|---|---|
| Elenco oficial do Farmácia Popular | Identificar substâncias e apresentações contempladas | Fonte localizada; extração e conferência pendentes |
| Lista oficial de estabelecimentos participantes | Localizar farmácias credenciadas | Planilha pública localizada; importação pendente |
| Consulta de medicamentos da Anvisa | Conferir identidade, registro e relações de equivalência aplicáveis | Consulta pública localizada; forma de obtenção dos registros a validar |
| Orientações oficiais do Farmácia Popular | Apresentar requisitos e links de acesso | Fonte localizada; regras do recorte serão revisadas |
| Ofertas de farmácias ou fornecedor de preços | Exibir preços reais e links de compra | Integração ainda não confirmada |

Fontes oficiais:

- [Elenco de medicamentos e insumos do Farmácia Popular](https://www.gov.br/saude/pt-br/composicao/sectics/farmacia-popular/arquivos/elenco-de-medicamentos-e-insumos-pfpb.pdf)
- [Lista de estabelecimentos participantes](https://www.gov.br/saude/pt-br/composicao/sectics/farmacia-popular/publicacoes/farmacias-participante-do-programa-farmacia-popular/view).
- [Orientações de acesso ao programa](https://www.gov.br/saude/pt-br/composicao/sectics/farmacia-popular).
- [Consulta de medicamentos da Anvisa](https://consultas.anvisa.gov.br/#/medicamentos/).

## 5. Tecnologias propostas e justificativas

| Tecnologia | Aplicação e justificativa |
|---|---|
| Figma | Identidade Visual |
| HTML e CSS | Interface responsiva, legível e acessível por celular e computador |
| JavaScript | Filtros, seleção de apresentações e comparação interativa |
| Python | Preparação dos dados, normalização de registros e lógica de consulta |
| pandas e openpyxl | Leitura e preparação das planilhas oficiais |
| Git e GitHub | Versionamento, documentação e registro das contribuições do grupo |

## 6. Pitch inicial

O AcessoMed é uma plataforma que ajuda pessoas a consultar possibilidades de acesso ao medicamento prescrito, reunindo informações do Farmácia Popular, ofertas de compra online. A proposta organiza dados que normalmente precisam ser consultados separadamente e permite comparar apresentações, quantidades e condições de preço com mais clareza. Com um protótipo de escopo reduzido e fontes identificadas, o projeto pretende facilitar decisões de aquisição e contribuir para a meta 3.8 da ODS 3, voltada ao acesso a medicamentos a preços acessíveis.

## 7. Equipe

Brenno Oliveira Souza - 2026108788 - BCC 2º Semestre

Murillo Manoel Silva Mendes - 2026104915 - BCC 2º Semestre

Rayssa Morais de Aquino - 2026112326 - BCC 2º Semestre

Ahmad Fayaz Kohistani - 2026114693 - BCC 2º Semestre


