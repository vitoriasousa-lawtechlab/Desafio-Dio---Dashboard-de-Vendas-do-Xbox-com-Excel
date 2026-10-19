Dashboard de Vendas — Xbox Game Pass
Projeto desenvolvido em Microsoft Excel para o desafio de criação de um dashboard de vendas da DIO (Digital Innovation One). A proposta é transformar registros de assinaturas do Xbox Game Pass em indicadores e gráficos que facilitem a análise do desempenho comercial.
Objetivo
Organizar uma base de vendas, elaborar cálculos de apoio e apresentar os resultados em um painel visual, com foco em receita, planos de assinatura, periodicidade, renovação automática e produtos adicionais.
Estrutura do arquivo
O arquivo Dashboard_Xbox_Autoral_Indicadores_DIO.xlsx contém quatro abas:
Aba	Finalidade
Assets	Paleta de cores, identidade visual e orientações de utilização.
Bases	Base de 295 registros de assinaturas, com informações dos clientes, planos, datas, valores, renovação, passes adicionais e cupons.
Cálculos	Central de indicadores e tabelas-resumo calculados com fórmulas; permite selecionar plano e renovação automática.
Dashboard	Painel gerencial com indicadores e gráficos relacionados às informações da aba Cálculos.


Indicadores apresentados
O dashboard reúne os seguintes indicadores gerais:
- Faturamento total registrado: 7.633 unidades monetárias.
- Total de assinaturas: 295 registros.
- Ticket médio: 25,87 unidades monetárias por registro.
- Cupons concedidos: 2.122 unidades monetárias.
Também apresenta indicadores específicos das perguntas de negócio:
Indicador	Resultado da base
Faturamento de assinaturas com periodicidade anual	1.754
Faturamento anual com renovação automática	1.537
Faturamento anual sem renovação automática (na aba Cálculos)	217
Receita de EA Play em assinaturas mensais	1.350
Receita de Minecraft em assinaturas mensais	1.800


Nota de interpretação: “anual” e “mensal” classificam a modalidade de assinatura informada na base. Esses valores não são, necessariamente, receitas contabilizadas em um ano ou mês-calendário específico. Os números são provenientes dos dados de exercício fornecidos no desafio, e as unidades monetárias seguem essa base.
Análises e funcionalidades
- Indicadores de receita, volume de assinaturas, ticket médio e descontos.
- Comparação da receita por plano Core, Standard e Ultimate.
- Análise por periodicidade Monthly, Quarterly e Annual.
- Comparação por renovação automática (Yes/No).
- Acompanhamento de adesão e receita de passes adicionais EA Play e Minecraft.
- Seletores na aba Cálculos para plano e renovação automática, vinculados aos resumos gerais e gráficos correspondentes.
- Gráficos e cartões com identidade visual própria, utilizando tons de azul e verde.
Recursos do Excel aplicados
Foram utilizados SOMASES, CONT.SES, SE, SEERRO, operações aritméticas e referências entre planilhas para obter totais e médias. A solução também utiliza formatação de células, formatos numéricos, listas de validação de dados e gráficos vinculados às tabelas de apoio.
A lógica principal é:
Bases (registros de vendas)
    ↓
Cálculos (fórmulas, indicadores e tabelas-resumo)
    ↓
Dashboard (cartões e gráficos)
Os cálculos desta versão são realizados por fórmulas, não por tabelas dinâmicas.
Como abrir e reproduzir
1. Faça o download de Dashboard_Xbox_Autoral_Indicadores_DIO.xlsx neste repositório.
2. Abra o arquivo no Microsoft Excel.
3. Consulte os registros e campos da aba Bases.
4. Acesse Cálculos para verificar as fórmulas e testar os filtros de plano e renovação.
5. Abra Dashboard para observar os indicadores e os gráficos vinculados.
6. Para experimentar outras análises, altere os filtros na aba Cálculos ou atualize os registros da base existente. Os resumos estão configurados para o intervalo original dos 295 registros; para acrescentar mais linhas, será necessário ampliar os intervalos das fórmulas.
Para utilizar os filtros e verificar o recálculo, recomenda-se o Excel com cálculo automático habilitado.

Aprendizados
O desenvolvimento permitiu praticar organização de bases, utilização de fórmulas condicionais, criação de indicadores de desempenho, elaboração de gráficos, estruturação de um dashboard e comunicação visual orientada por perguntas de negócio.
Origem e finalidade dos dados
Os registros foram disponibilizados como base de exercício no desafio da DIO. O dashboard é um projeto educacional e não representa números oficiais de vendas da Microsoft ou do Xbox Game Pass.
