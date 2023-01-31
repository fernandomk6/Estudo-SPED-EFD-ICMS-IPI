# Estudo sobre: SPED Fiscal ICMS IPI (EFD ICMS IPI)

- Apenas empresas com regime tributário normal (real e lucro presumido) enviam sped icms ipi.
- O Arquivo à ser importado deve ter a extensão .efd.

## Pre-requisitos

- saber o que é o icms

## Por que é importânte

O sped está em todos os aspectos da tributação

## O que é

É um arquivo txt que contem informações sobre todas as notas
fiscais emitidas pela empresa, dentre outras informações.

O Arquivo sped icms ipi, contém todas as informações de todas
as notas fiscais, com fins de apuração dos impostos de icms e 
ipi.

O arquivo sped icms ipi, é enviado para a secretaria da fazenda 
de cada estado, por meio do programa sped.

Cada tributação tem o seu arquivo sped, e cada documento eletrônico,
também faz parte do arquivo sped.

Cada empresa tem um perfil, esse perfil tem 3 variações, e de acordo
com esse perfil, os documentos eletronicos podem variar.

- Perfil A: as informações devem ser passadas detalhadamente;
- Perfil B: as informações são passadas de forma sintética, totalizadas;
- Perfil C: as informações são passadas de forma simplificada.

Esse perfil é determinado por estado. Ou seja, estado do Ceará perfil B,
estado de são paulo, perfil A e assim por cada estado.

Alguns CNPJ estão obrigados a entrega do arquivo sped, outros não.

## Estrutura do arquivo "livros abrangidos"

- Registro de entradas
- Registro de saídas
- Registro de apuração de ICMS
- Registro de apuração de IPI
- Registro de inventário
- Registro de apuração CIAP
- Registro de apuração de controle de produção e estoque

Todas as notas que foram emitidas com o seu cnpj, seja entrada ou saída,
devem ser informadas no sped icms ipi.

Sobre os blocos. A estrutura pode ser dividida em blocos.

- Movimentações
- Apurações (totalizadores)
- Inventário (entregue no mes de fevereiro com relação ao periodo anterior)
- Bloco G: bloco de apuração do CIAP (livro de apuração do ativo imobilizado)
- Bloco K: bloco de controle de produção e estoque

## Processo de envio do sped, geração, ecosistema e tudo mais

## Gerando arquivo sped icms ipi

Para gerar o arquivo sped, precisaremos do leiaute atual, que pode ser encontrado no site
do sped, e também precisaremos do banco de dados do cliente, que é de onde iremos
obter todas as informações com relação aos documentos fiscais, e tudo mais
o que for necessário para a geração do arquivo sped icms ipi. Deve ser
gerado um arquivo de texto seguindo o leiaute do sped icms ipi com as informações
do banco de dados do cliente. Com isso teremos um arquivo sped icms ipi.

### Validar arquivo sped icms ipi

Para validar o arquivo sped icms ipi é necessário baixar o programa validador diretamente
do site do sped. Depois que o arquivo for validado (vale ressaltar que podem ocorrer erros 
de validação e se ocorrer, devem ser corrigidos) o arquivo deve ser assidado digitalmente
(semelhante a quando uma nota fiscal é gerada (requer certificado digital)) e depois 
disso, o arquivo deve transimito para a sefaz (semelhante ao envio de uma nota fiscal).
Todo esse processo de, assinatura e transmissão, devem ser feito pelos contadores. A
empresa de software, geralmente, gera o arquivo sped, com base no banco de dados
e no leiaute vigente, valida o arquivo e então, envio-o para a contabilidade, para que
a contabilidade assine e transmita à sefaz.

## Estruturação parte 2

A estrutura do arquivo sped é dividida em grandes grupos, e esses grupos contém blocos.

- Cadastros
  - Empresa
  - Fornecedor
  - Cliente
  - Produto
  - Unidade
  - Contador
  - Blocos
    - Bloco 0

- Movimentações
  - NFe entradas
  - NFe saídas
  - Blocos
    - Bloco B (apresentado apenas para o distrito federal contém 
    informações sobre as notas fiscais de serviço)
    - Bloco C
    - Bloco D
- Relatórios
  - Livros fiscais
  - Apurações
  - Blocos
    - Bloco E - icms, ipi, icms st
    - Bloco G - ciap
    - Bloco H - inventário
    - Bloco K - produção e estoque
- Configurações
  - Controles extras
  - Encerramento do arquivo
  - Plano de contas
  - Blocos
    - Bloco 1
    - Bloco 9

Estrutura em ordem:

- Bloco 0: Abertura da escrituração
- Blocos C e D: Documentos fiscais
- Bloco E: Apuração ICMS/IPI
- Bloco G: Ativo imobilizado
- Bloco H e K: Inventário e estoque
- Bloco 1: Informações gerais
- Bloco B: Informações do ISS

