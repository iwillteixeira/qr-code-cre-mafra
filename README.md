<p align="center">
  <img src="assets/logo-cre-mafra.png" alt="CRE Mafra" width="150" />
</p>

<h1 align="center">QR Code Generator — CRE Mafra</h1>

<p align="center">
  <strong>Coordenadoria Regional de Educação de Mafra</strong><br/>
  Secretaria de Estado da Educação — Santa Catarina
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-ativo-336633?style=flat-square" alt="Status" />
  <img src="https://img.shields.io/badge/licen%C3%A7a-uso%20institucional-C4000B?style=flat-square" alt="Licença" />
  <img src="https://img.shields.io/badge/plataforma-web-333333?style=flat-square" alt="Plataforma" />
</p>

---

## Sobre

Gerador de QR Codes gratuito desenvolvido para a **CRE de Mafra** (Coordenadoria Regional de Educação), vinculada à Secretaria de Estado da Educação de Santa Catarina.

Os QR Codes são **gerados localmente no navegador**, sem envio de dados para servidores externos. Não expiram e não possuem limite de leituras.

## Funcionalidades

| Tipo | Descrição |
|------|-----------|
| **URL** | Links para sites e páginas |
| **Texto** | Texto livre |
| **E-mail** | Endereço, assunto e corpo |
| **Telefone** | Ligação direta |
| **SMS** | Mensagem de texto |
| **WhatsApp** | Mensagem via WhatsApp |
| **Wi-Fi** | Conexão automática à rede |
| **vCard** | Cartão de contato digital |

## Personalização

- Cor do QR Code e cor de fundo
- Logo centralizada: **CRE Mafra**, **SED/SC**, **Bandeira de SC** ou imagem personalizada
- Estilo dos pontos (quadrado, círculos, arredondado, classy)
- Estilo dos cantos (borda e centro)
- Resolução de 200px a 1000px
- Download em **PNG** ou **SVG**

## Como usar

1. Acesse o gerador pelo navegador
2. Escolha o tipo de conteúdo na barra lateral
3. Preencha os campos
4. Personalize cores, logo e estilo
5. Clique em **Criar QR Code**
6. Baixe em PNG ou SVG

## Executando localmente

```bash
# Clone o repositório
git clone https://github.com/iwillteixeira/qr-code-cre-mafra.git
cd qr-code-cre-mafra

# Sirva com qualquer servidor HTTP
python3 -m http.server 8765

# Acesse no navegador
# http://localhost:8765
```

> Não requer instalação de dependências — é 100% client-side (HTML + CSS + JS).

## Identidade Visual

| Elemento | Valor |
|----------|-------|
| Verde principal | `#336633` |
| Verde hover | `#3d7a3d` |
| Vermelho destaque | `#C4000B` |
| Fonte headings | Montserrat |
| Fonte body | Open Sans |

Paleta e tipografia seguem a identidade visual da **Secretaria de Estado da Educação de Santa Catarina** (SED/SC).

## Estrutura do Projeto

```
qr-code-cre-mafra/
├── index.html          # Página principal
├── style.css           # Estilos (identidade SED/SC)
├── app.js              # Lógica do gerador
├── assets/
│   ├── logo-cre-mafra.png   # Logo CRE Mafra
│   ├── logo-cre-mafra.svg   # Logo CRE Mafra (vetor)
│   ├── logo-sed.png          # Logo SED/SC
│   └── bandeira-sc.png       # Bandeira de Santa Catarina
└── lib/
    └── qr-code-styling.js    # Biblioteca QR Code Styling
```

## Municípios atendidos

Itaiópolis · **Mafra** · Monte Castelo · Papanduva

---

<p align="center">
  <sub>Desenvolvido para a CRE de Mafra — SED/SC</sub>
</p>
