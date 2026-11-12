# Portal de Voluntariado UCSAL

Protótipo do Portal de Voluntariado da Universidade Católica do Salvador, desenvolvido para a Coordenação de Ações Comunitárias e de Extensão (CAEX), da Pró-Reitoria de Graduação, Extensão e Ação Comunitária.

## O que o portal reúne

- Oportunidades de voluntariado, com filtros por frente de atuação, modalidade e ODS
- Formação gratuita: trilha do voluntário, formações específicas e o ciclo Voluntalks
- Programa de Monitoria Voluntária, com agendamento de conversa com o CAEX
- Explorar o mundo: programas na Bahia, no Brasil e no exterior
- Relatos de experiências, com revisão da equipe antes da publicação
- Indicação de locais e instituições para receber ações
- Cadastro no banco de voluntários (contato, disponibilidade, liga acadêmica, habilidades)
- Painel CAEX: banco de voluntários, convocação por perfil, horas e selos, declarações, formações, reuniões, relatos e indicações

## Estrutura

Página única (`index.html`), sem dependências de build. Fontes carregadas do Google Fonts.

## Publicar no GitHub Pages

1. Acesse **Settings → Pages** no repositório.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione a branch `main` e a pasta `/ (root)` e salve.
4. Em alguns minutos o portal fica disponível em `https://<usuario>.github.io/<repositorio>/`.

## Limitação desta versão

O banco de dados do protótipo funciona apenas quando a página é aberta como artefato no Claude. Fora dele, como no GitHub Pages, o portal abre em **modo de apresentação**: todo o conteúdo e a navegação funcionam, os formulários validam os campos, mas os envios não são gravados.

Para receber cadastros reais, o próximo passo é ligar os formulários a um banco externo (por exemplo, Google Planilhas com Apps Script, ou o sistema institucional da UCSAL).

## Contato

CAEX/UCSAL · extensao@ucsal.br · WhatsApp (71) 9959-0535
