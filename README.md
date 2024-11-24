# Análise de IDHM e Educação Infantil nos Municípios Brasileiros

Este repositório contém análises e visualizações baseadas em dados de **IDHM (Índice de Desenvolvimento Humano Municipal)** e outras variáveis relacionadas à educação nos municípios brasileiros. O objetivo é identificar prioridades de investimento em educação, com foco em regiões com menor desenvolvimento humano e infraestruturas educacionais limitadas.

## Conteúdo do Repositório

1. **Dataset**: 
   - O dataset contém informações detalhadas sobre municípios brasileiros, incluindo dados sobre IDHM, subíndices de renda e educação, número de crianças entre 1 e 4 anos, além de informações sobre a quantidade de empresas do setor educacional.

2. **Análises Realizadas**:
   - **Média do IDHM por Região**: Cálculo e visualização da média do IDHM e categorização das regiões brasileiras em Baixo, Médio, Alto e Muito Alto desenvolvimento humano.
   - **Boxplot do IDHM_Educacao por Região**: Gráfico que permite comparar a distribuição do IDHM relacionado à educação nas regiões Norte, Nordeste, Centro-Oeste, Sul e Sudeste.
   - **Identificação de Municípios com Mais Crianças (1-4 anos)**: Foco nos municípios que estão acima do 3º quartil nacional em quantidade de crianças em idade pré-escolar, na região com o menor IDHM_Educacao.
   - **Empresas de Educação**: Análise dos municípios com o menor número de empresas educacionais, identificando áreas com baixa infraestrutura educacional.
   - **Proposta de Prioridade de Investimento**: Uma ordem de priorização para investimentos em educação infantil, com base nas análises de concentração de crianças e baixa infraestrutura educacional.

3. **Scripts e Visualizações**:
   - Todos os scripts utilizados para manipulação de dados, cálculos e geração de gráficos estão incluídos no repositório. Estes scripts foram escritos em **Python**, utilizando as bibliotecas **pandas** e **matplotlib** para análise de dados e visualização.

## Como Utilizar

1. **Requisitos**:
   - Certifique-se de ter o **Python 3.x** instalado.
   - Instale as bibliotecas necessárias:
     ```bash
     pip install pandas matplotlib
     ```

2. **Rodar as Análises**:
   - Clone o repositório:
     ```bash
     git clone https://github.com/seu-usuario/repo-nome.git
     ```
   - Execute os scripts de análise e visualize os gráficos diretamente no seu ambiente local ou no **Google Colab**.

## Contribuições

Contribuições são bem-vindas! Caso tenha sugestões ou melhorias, sinta-se à vontade para abrir uma **issue** ou enviar um **pull request**.

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.
