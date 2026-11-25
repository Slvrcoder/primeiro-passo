# Primeiro Passo

Plataforma digital e gratuita que prepara jovens de escola pública para o primeiro emprego e entrega às empresas um **primeiro filtro**: candidatos que já provaram preparo técnico e socioemocional e demonstraram interesse real.

Projeto desenvolvido para o **Bootcamp ONE 2026** (UFMA), Problema 01: dificuldade de acesso ao primeiro emprego para jovens da periferia, alinhado ao **ODS 10 (Redução das Desigualdades)**.

> O nome "Primeiro Passo" é provisório. Este repositório é um **protótipo de demonstração**: não há servidor, banco de dados nem empresas reais, e todos os dados são fictícios.

## O problema

- Desemprego de jovens de 18 a 24 anos: 13,8%, mais que o dobro da média nacional de 5,8%. Entre 14 e 17 anos, 25,1% ([MTE, 1º tri de 2026](https://agenciagov.ebc.com.br/noticias/202606/emprego-formal-alcanca-57-2-dos-jovens-ocupados-no-brasil-aponta-estudo-do-mte)).
- 6,2 milhões de jovens não estudam nem trabalham (MTE, 2026).
- Escriturários gerais são a 2ª maior ocupação dos jovens, com 1,07 milhão de pessoas (MTE, 2026). Por isso a primeira trilha é administrativa.
- 80% dos empregadores brasileiros têm dificuldade para contratar (ManpowerGroup, 2026, via reportagens).
- O socioemocional pesa: 61,7% das empresas apontam a inteligência emocional como a soft skill mais importante ([Catho, 2026](https://jornaldobras.com.br/noticia/130429/inteligencia-emocional-e-ia-podem-abrir-as-portas-do-primeiro-emprego-para-os-jovens)) e 69% dos empresários têm mais dificuldade para achar o perfil comportamental do que o conhecimento técnico ([Heach RH, via Correio Braziliense](https://www.correiobraziliense.com.br/euestudante/trabalho-e-formacao/2026/08/7476049-mercado-de-trabalho-soft-skills-ja-pesam-mais-que-o-curriculo.html)).
- Substituir quem sai custa, em funções operacionais, cerca de 30% a 50% do salário anual segundo estimativas de mercado ([Gupy](https://www.gupy.io/blog/custo-do-turnover)).

## A solução

1. **Aprender:** trilha administrativa com módulos técnicos e socioemocionais.
2. **Provar:** cada módulo termina com um mini-projeto e uma situação do dia a dia, que alimentam o perfil do jovem.
3. **Filtrar:** o jovem recebe uma nota de prontidão (técnica e socioemocional). A empresa define a prontidão mínima e só vê quem a atingiu.
4. **Contratar:** vaga de entrada e acompanhamento nos primeiros meses, para reduzir a rotatividade.

O acesso é gratuito para o jovem. O modelo é financiado por apoio do governo, como política pública de educação e emprego jovem, e por empresas parceiras (taxa por contratação e mensalidade).

## O que já existe e o que acrescentamos

Instituições como o Instituto PROA, o CIEE, o Senai e o Senac já formam e conectam jovens, e são parceiros naturais. O Primeiro Passo acrescenta: o primeiro filtro para a empresa, formação técnica e socioemocional juntas, trilha desenhada a partir da demanda das empresas locais e foco na permanência no emprego, com escala de política pública.

## O que o protótipo mostra

- **Início:** progresso na trilha e vagas mais próximas de serem liberadas.
- **Trilhas:** 6 módulos, 3 técnicos e 3 socioemocionais, em sequência. Cada um tem mini-projeto e uma situação do dia a dia com escolha de resposta.
- **Vagas:** cada vaga mostra as competências que a empresa pede e só libera a candidatura quando os módulos exigidos estão concluídos.
- **Perfil:** progresso, prontidão técnica e socioemocional, competências, portfólio, candidaturas e histórico.
- **Empresa:** painel com a prontidão mínima ajustável, mostrando quantos candidatos passam no filtro e quantas triagens manuais foram evitadas.

O estado fica salvo no navegador (localStorage). O botão "Reiniciar demonstração", no Perfil, volta ao começo.

## Como rodar

Não precisa instalar nada. Abra o arquivo `index.html` no navegador.

Para publicar de graça no GitHub Pages: no repositório, vá em **Settings > Pages**, escolha a branch `main` e a pasta `/ (root)`. O link aparece depois de um minuto.

## Tecnologias

HTML, CSS e JavaScript puros, em um único arquivo. A fonte Rawline (licença SIL OFL 1.1) vai embutida no arquivo.

## Identidade visual

O visual se inspira no Padrão Digital de Governo (fonte Rawline e paleta de azul, amarelo e verde), para transmitir a ideia de política pública. O projeto **não tem vínculo com o governo** e não usa brasão, selo ou símbolo oficial.

## Cuidados com o filtro

O filtro não pode excluir quem mais precisa. Os critérios devem ser transparentes, baseados no que o jovem faz na plataforma (entregas e escolhas) e nunca em escola ou bairro, com revisão humana. Esses critérios ainda precisam ser definidos e validados.

## Limitações

- Dados e empresas fictícios, sem banco de dados nem login real.
- As situações socioemocionais e a nota de prontidão são ilustrativas, ainda sem validação de especialistas.
- Os valores de receita e custo do modelo de negócios são estimativas do piloto e precisam de validação com empresas.

## Próximos passos

- Piloto em Joinville/SC: uma trilha administrativa, uma escola pública e de 3 a 5 empresas.
- Conversar com jovens do público e com o RH de empresas para validar o filtro.
- Definir os critérios do filtro e a parceria com entidades qualificadoras da aprendizagem.
- Novas trilhas (comércio, tecnologia) e rede de contatos entre jovens, na fase 2.

## Autor

Matheus Henrique da Silveira, Joinville/SC.

## Licença

O código está sob a licença MIT (veja `LICENSE`). A fonte Rawline segue a licença SIL OFL 1.1.
