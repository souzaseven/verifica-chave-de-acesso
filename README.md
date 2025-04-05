# 🔍 Validador de Chave de Acesso NF-e/NFC-e/CT-e

![Preview](https://www.sefaz.mt.gov.br/imagens/cabecalho.PNG)

Ferramenta web para validação e decomposição de chaves de acesso de documentos fiscais eletrônicos brasileiros.

## ✨ Funcionalidades

- **Validação instantânea** de chaves de 44 dígitos
- **Decomposição detalhada** em todos os campos:
  - UF emitente (cUF)
  - Ano/mês de emissão (AAMM)
  - CNPJ do emitente
  - Modelo do documento (NF-e, NFC-e, CT-e)
  - Série, número e tipo de emissão
- **Links diretos** para consulta oficial:
  - SEFAZ MT
  - Portal Nacional NF-e
  - Portal CT-e
- **Visualização ampliada** das imagens explicativas

## 🛠 Tecnologias

- **Frontend**
  - HTML5 semântico
  - CSS3 Flexbox
  - JavaScript (ES6)
- **Integrações**
  - Google Analytics (GTAG)
  - Google AdSense

## 🚀 Como Usar

1. Cole a chave de acesso no campo indicado
2. Visualize automaticamente:
   - A validação da chave
   - A decomposição completa
   - O tipo de documento fiscal
3. Utilize os botões para:
   - Consultar no portal oficial
   - Visualizar detalhes ampliados

## 🏛 Estrutura da Chave

| Campo   | Dígitos | Descrição                     | Exemplo  |
|---------|---------|-------------------------------|----------|
| cUF     | 2       | Código da UF do emitente      | 51 (MT)  |
| AAMM    | 4       | Ano/mês da emissão            | 2203     |
| CNPJ    | 14      | CNPJ do emitente              | 00000000000191 |
| mod     | 2       | Modelo (55=NF-e, 65=NFC-e)    | 55       |
| série   | 3       | Série do documento            | 001      |
| nNF     | 9       | Número do documento           | 000012345 |
| tpEmis  | 1       | Tipo de emissão               | 1        |
| cNF     | 8       | Código numérico               | 12345678 |
| cDV     | 1       | Dígito verificador            | 7        |

