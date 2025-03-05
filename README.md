# EBA_Airbnb

# **Análise Exploratória de Dados (EDA) - Airbnb NYC**

## **Visão Geral do Projeto**
Este projeto realiza uma Análise Exploratória de Dados (EDA) nos dados do Airbnb em Nova York. O objetivo é identificar padrões e tendências nas acomodações listadas, explorando variáveis como preços, tipos de quartos, localização e comportamento dos anfitriões.

## **Objetivos**
- Analisar a distribuição dos tipos de quartos e suas diferenças de preço.
- Explorar a relação entre disponibilidade, preço e número de avaliações.
- Identificar possíveis outliers e tendências nos preços dos imóveis.
- Fornecer insights para hóspedes e anfitriões sobre boas práticas de precificação e disponibilidade.

## **Conjunto de Dados**
O conjunto de dados utilizado possui 20.765 entradas e 22 variáveis, incluindo:
- **id**: Identificador único da listagem.
- **name**: Nome do anúncio.
- **host_name**: Nome do anfitrião.
- **neighborhood_group**: Grupo de bairro onde a listagem está localizada.
- **latitude/longitude**: Localização geográfica.
- **price**: Preço por noite.
- **room_type**: Tipo de acomodação (e.g., casa/apto inteiro, quarto privativo).
- **reviews_per_month**: Média de avaliações por mês.
- **availability_365**: Dias disponíveis no ano.

## **Fluxo de Trabalho**
1. **Limpeza de Dados**
   - Tratamento de valores ausentes.
   - Conversão de tipos de dados.
   - Remoção de outliers para análises mais realistas.

2. **Análise Exploratória de Dados (EDA)**
   - Distribuição dos tipos de quartos.
   - Preços médios por bairro.
   - Correlação entre disponibilidade e avaliações.
   - Distribuição e identificação de outliers nos preços.

3. **Visualização de Dados**
   - **Pairplot**: Explora relações entre preço, avaliações e disponibilidade.
   - **Heatmap**: Exibe correlação entre variáveis numéricas.
   - **Histogramas e Boxplots**: Identifica outliers e distribuições de preços.
   - **Gráficos de Barras**: Mostra a distribuição dos tipos de acomodação por bairro.

## **Principais Descobertas**
- **Tendências de Preços**:
  - Manhattan tem os preços mais altos.
  - Casas/apartamentos inteiros são significativamente mais caros do que quartos privados ou compartilhados.
- **Distribuição dos Tipos de Quartos**:
  - Casas/apartamentos inteiros são os mais comuns, mas quartos privados são uma opção mais econômica.
- **Padrões de Disponibilidade**:
  - Anúncios com alta disponibilidade tendem a ter preços mais baixos e mais avaliações.
- **Comportamento dos Anfitriões**:
  - Alguns anfitriões gerenciam várias listagens, indicando um mercado mais profissionalizado.

## **Como Executar o Projeto**
1. Clone o repositório:
   ```bash
   git clone [URL_DO_REPOSITORIO]
   ```
2. Instale as dependências necessárias:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Execute o notebook Jupyter:
   ```bash
   jupyter notebook airbnb_eda.ipynb
   ```

## **Recomendações**
- **Para Hóspedes:**
  - Escolher listagens com boas avaliações e alta disponibilidade para uma melhor experiência.
  - Quartos privados no Brooklyn oferecem boas opções custo-benefício.
- **Para Anfitriões:**
  - Melhorar a disponibilidade e o atendimento aos hóspedes pode aumentar o volume de reservas.
  - Ajustar os preços para competir com ofertas semelhantes na mesma região.


## **Licença**
Este projeto está licenciado sob a MIT License.



