# Domínio e e-mail institucional — plano de implantação

Este arquivo deixa preparada a migração do site atual para um domínio próprio assim que houver um benefício de domínio elegível ou outra opção de registro adequada.

## Domínios prioritários para verificar

1. `pesquisajuridicaprofunda.tech`
2. `jurisprofunda.tech`
3. `pjprofunda.tech`

A disponibilidade deve ser conferida no momento do resgate. Não registrar alternativa paga sem revisão prévia de preço de renovação e política do provedor.

## Estrutura desejada

- site institucional: `https://DOMINIO/`
- e-mail profissional principal: `kelven@DOMINIO`
- alternativa pública: `contato@DOMINIO`
- hospedagem do site: GitHub Pages
- HTTPS: obrigatório
- DNS: Cloudflare, se compatível com o domínio escolhido
- recebimento de e-mails: Cloudflare Email Routing ou solução equivalente gratuita/adequada

## Sequência de implantação

1. Resgatar ou registrar o domínio.
2. Adicionar o domínio à conta Cloudflare.
3. Configurar os nameservers indicados pelo provedor.
4. Apontar o domínio para o GitHub Pages.
5. Configurar o domínio customizado nas configurações do repositório.
6. Validar HTTPS.
7. Criar o roteamento de `kelven@DOMINIO` e `contato@DOMINIO`.
8. Encaminhar o recebimento para a caixa escolhida.
9. Testar recebimento e eventuais respostas.
10. Atualizar site, GitHub e futuras candidaturas com o mesmo domínio/e-mail.

## Reaplicação institucional

Antes de uma nova candidatura a programas de startups:

- o site deve estar acessível no domínio definitivo;
- o e-mail informado deve usar o mesmo domínio;
- a página deve identificar claramente o projeto, o fundador, a proposta de valor e o contato;
- não usar e-mail acadêmico como principal e-mail de negócio;
- manter GitHub como prova complementar de desenvolvimento;
- revisar se todas as informações são verdadeiras e verificáveis.

## Segurança

Não registrar no repositório:

- senhas;
- tokens;
- chaves de API;
- códigos de autenticação;
- documentos de clientes;
- autos processuais;
- dados protegidos por sigilo profissional.

## Estado atual

O site provisório está publicado em:

https://kelvengps7-coder.github.io/

A migração para domínio próprio permanece pendente da definição/resgate do domínio.
