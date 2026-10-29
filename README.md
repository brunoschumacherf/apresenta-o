# Site de apresentação — Cacautrip

Site estático independente, pensado para compartilhar a explicação do projeto por QR code em slides. Contém apresentação do problema, públicos, funcionalidades, jornadas, trilhas, negociação de transporte, sustentabilidade, suporte, administração, arquitetura e estágio do MVP. Não contém senhas, códigos de coleta, URLs privadas do banco ou dados de usuários.

## Arquivos

- index.html: todo o conteúdo, com seções navegáveis e tópicos expansíveis.
- style.css: identidade visual, adaptação para celular, menu e impressão.
- script.js: menu móvel acessível. O conteúdo continua legível sem JavaScript.
- assets/: logo e foto local do projeto.
- favicon.ico: ícone do site.

Não exige npm, Rails, banco, build ou bibliotecas externas. Abra index.html para consultar localmente. Publique **a pasta inteira**, preservando a estrutura, em qualquer hospedagem estática HTTPS. Este site não chama a API e não cria reservas.

## Publicar e colocar no slide

1. Publique o conteúdo desta pasta em uma hospedagem estática de sua preferência, como a mesma plataforma usada para hospedar seu frontend.
2. Abra a URL pública definitiva em um celular para conferir se os assets foram publicados junto do HTML.
3. Gere o QR code com **essa URL HTTPS** no editor dos slides ou na ferramenta de sua preferência.
4. Coloque o QR code no slide com uma legenda, por exemplo: “Conheça o projeto Cacautrip”, e o endereço escrito ao lado como alternativa.
5. Confira a leitura do QR code depois de exportar os slides.

O QR code não foi gerado porque ainda não existe uma URL pública definida para esta apresentação. Não use endereço local, caminho de arquivo ou URL temporária no QR do slide. O site também não foi publicado nesta solicitação.

## Conteúdo e manutenção

O texto descreve os fluxos implementados no repositório e mantém uma seção de transparência: Gov.br, pagamentos e saques são de demonstração; Google e IA dependem de configuração. Não afirma que a plataforma já possui parceiros comerciais ou indicadores de impacto ambiental reais. A apresentação inclui orientações de privacidade sem afirmar certificação de conformidade legal.

Atualize os textos do HTML quando o produto evoluir. Para adicionar o link do app publicado, inclua um botão com a URL final; nenhum endereço do app foi inventado. Após publicar, pode adicionar og:url e og:image com URLs absolutas da hospedagem para melhorar a prévia ao compartilhar.

Não foram executados testes, servidor ou build, seguindo a preferência por validação manual.
# apresenta-o
