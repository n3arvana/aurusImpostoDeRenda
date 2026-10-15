# Aurus Imposto de Renda
 Aurus IR --- Organizador de Imposto de Renda no Excel
Uma planilha com aparência de aplicativo para organizar dados do
titular, informes bancários e entradas financeiras, além de visualizar
a distribuição de valores por instituição.




 Sobre o projeto
O Lyon IR é um projeto desenvolvido em Microsoft Excel com o
objetivo de centralizar e organizar informações que podem ser úteis
durante a preparação da declaração do Imposto de Renda. A proposta
visual utiliza uma identidade dark premium, inspirada em tons de
preto, grafite e dourado, para aproximar a experiência de uma interface
de aplicativo.
O arquivo reúne áreas para cadastro do titular, registro de informações
bancárias, anotação de entradas financeiras e um dashboard com a
distribuição dos valores registrados por instituição financeira.
Importante: o Lyon IR é uma ferramenta de organização e
acompanhamento. Ele não substitui o programa oficial da Receita Federal,
orientação contábil ou conferência das regras tributárias aplicáveis. Os
valores exibidos no dashboard representam os dados cadastrados na
planilha e não devem ser interpretados automaticamente como rendimentos
tributáveis ou como cálculo do imposto devido.

 Objetivos
- Centralizar informações em uma única pasta de trabalho.
- Organizar os dados cadastrais do titular.
- Registrar instituições financeiras, valores informados e referências
  aos informes bancários.
- Registrar entradas financeiras por data, categoria e valor.
- Visualizar a distribuição dos valores cadastrados entre os bancos.
- Aplicar princípios de design de dashboards: hierarquia visual,
  consistência de cores e leitura rápida.
- Praticar recursos do Excel, como fórmulas, listas de seleção,
  formatação de células e gráficos.
   Estrutura da pasta de trabalho
O arquivo é composto pelas seguintes abas:
  Aba                                 Finalidade
  TITULAR                           Área para preenchimento dos dados
                                      cadastrais do contribuinte e
                                      informações relacionadas à
                                      declaração.
  INFORME                           Área para registrar instituições
                                      financeiras, valores atuais e
                                      nomes/referências dos arquivos de
                                      informes bancários. Também
                                      consolida os valores cadastrados.
  NOTAS                             Registro de entradas financeiras
                                      mês a mês, com campos para data,
                                      categoria e valor.
  DASHBOARD                         Tabela auxiliar com banco, valor e
                                      participação percentual, utilizada
                                      para visualizar a distribuição
                                      financeira por instituição.
  BANCOS                            Lista de instituições financeiras
                                      usada como referência para seleção
                                  e padronização dos nomes.
1. TITULAR
Reúne campos para organizar informações como nome, CPF, data de
nascimento, título de eleitor, endereço, contatos e respostas cadastrais
relacionadas à declaração.
Preencha os campos com dados atualizados e confira cuidadosamente cada
informação. Para publicar o projeto no GitHub, utilize apenas dados
fictícios ou anonimizados.
2. INFORME
Permite registrar informações de diferentes instituições financeiras.
Cada registro inclui:
- Nome da instituição;
- Valor informado na planilha;
- Nome ou referência do arquivo do informe bancário.
A área também calcula o total dos valores registrados nos bancos
contemplados. Na versão atual, a estrutura está preparada visualmente
para três instituições, portanto a inclusão de bancos adicionais pode
exigir a atualização das fórmulas e da fonte de dados do gráfico.
3. NOTAS
Área destinada ao registro de entradas financeiras, com campos de:
- Data;
- Categoria da entrada;
- Valor.
Essa área pode ajudar a manter um histórico organizado de entradas ao
longo do ano. Os registros precisam ser classificados e conferidos pelo
usuário; uma entrada financeira não é necessariamente tributável, e a
categoria usada na planilha não determina, por si só, o tratamento
fiscal.
4. DASHBOARD
Apresenta uma visão resumida dos valores cadastrados por instituição
financeira. A tabela auxiliar possui as colunas:
- Banco: nome da instituição referenciada na aba INFORME;
- Valor: valor associado à instituição;
- Participação: percentual daquele valor em relação ao total dos
  bancos considerados.
A participação é calculada pela divisão do valor de cada instituição
pela soma dos valores apresentados no dashboard. O gráfico de barras
permite comparar os valores entre os bancos, enquanto os percentuais
mostram a participação relativa de cada um.
Título do gráfico: Distribuição Financeira por Banco
Texto de apoio: Visualize os valores registrados em cada
instituição financeira e sua participação no total consolidado.
O gráfico representa os valores cadastrados na planilha. Ele não
calcula a incidência de imposto, não valida os informes e não deve ser
usado isoladamente para concluir qual valor deve ser declarado.

5. BANCOS
Contém uma lista de instituições financeiras para padronizar o
preenchimento. A lista pode ser atualizada conforme a necessidade do
projeto, mantendo consistência nos nomes selecionados.

 Como utilizar
1. Baixe ou clone este repositório.
2. Abra o arquivo .xlsx em uma versão compatível do Microsoft Excel.
3. Leia as instruções apresentadas em cada aba.
4. Preencha a aba TITULAR com os dados necessários.
5. Registre as instituições e os valores correspondentes em INFORME.
6. Registre as entradas financeiras na aba NOTAS.
7. Consulte a aba DASHBOARD para comparar os valores e percentuais
   calculados.
8. Mantenha a lista da aba BANCOS atualizada quando necessário.
9. Revise as informações e fórmulas antes de utilizar os dados em
   qualquer procedimento fiscal.
Dica: mantenha uma cópia original vazia como modelo e trabalhe em
uma cópia separada para os dados de cada pessoa ou exercício.

 Privacidade e segurança dos dados
Informações fiscais e cadastrais são sensíveis. Não publique no GitHub
arquivos preenchidos com dados reais.
Antes de versionar ou compartilhar o projeto:
- Remova CPF, título de eleitor, endereço, telefone, e-mail e demais
  dados pessoais;
- Não inclua informes bancários, extratos, holerites ou documentos
  anexos reais;
- Substitua os dados de demonstração por dados fictícios;
- Verifique o histórico do Git: excluir um arquivo em um commit
  posterior não remove necessariamente versões anteriores;
- Guarde arquivos preenchidos em local privado e com acesso restrito;
- Compartilhe documentos somente com pessoas autorizadas.
Se dados reais já tiverem sido enviados a um repositório público, remova
o acesso público e avalie a necessidade de limpar o histórico do
repositório e tomar medidas adicionais.

   Limitações e melhorias futuras
O projeto está em desenvolvimento. Algumas melhorias que podem ser
consideradas:
- [ ] Criar uma tela de checklist para acompanhar documentos e etapas
  da declaração;
- [ ] Transformar as áreas de registro em tabelas estruturadas para
  facilitar a expansão;
- [ ] Permitir adicionar bancos sem editar manualmente as fórmulas e o
  gráfico;
- [ ] Adicionar filtros por período e categoria na área de entradas;
- [ ] Criar indicadores de total registrado e quantidade de
  instituições;
- [ ] Melhorar mensagens de validação e campos obrigatórios;
- [ ] Adicionar instruções sobre anexos e conferência de documentos;
- [ ] Testar as fórmulas com células vazias, valores zerados e novos
  registros;
- [ ] Revisar acessibilidade, contraste e usabilidade em diferentes
  resoluções;
- [ ] Validar os conceitos fiscais com fontes oficiais antes de
  incluir qualquer cálculo tributário.

Aviso:

Este projeto tem finalidade educacional e organizacional. Não é um
produto oficial da Receita Federal e não substitui o sistema oficial de
declaração do Imposto de Renda, um profissional de contabilidade ou a
consulta às orientações oficiais vigentes. O usuário é responsável por
conferir a exatidão dos dados e a adequação de qualquer informação
utilizada para fins fiscais.

A referência visual à Lyon Esports é uma inspiração de design. Antes de
distribuir ou divulgar publicamente uma versão que utilize logotipos ou
ativos de terceiros, verifique as permissões de uso aplicáveis.

Autor
Guilherme Breno Martins
Projeto desenvolvido para praticar organização de dados, fórmulas,
visualização de informações e design de interfaces no Microsoft Excel.
