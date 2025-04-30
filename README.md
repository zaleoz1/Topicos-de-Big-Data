# Análise de Acidentes no Piauí

Este repositório contém scripts de análise de dados e gráficos relacionados a acidentes de trânsito no estado do Piauí, com base em uma base de dados fornecida. O objetivo principal é explorar os dados, identificar padrões e tendências, e apresentar essas informações de forma visual para facilitar a compreensão.

---

## Estrutura do Repositório

### **Arquivos Principais**
1. **`acidentes_pi.csv`**
   - Contém os dados dos acidentes, incluindo informações como data, horário, local, causa, tipo de veículo, condições meteorológicas, entre outros.
   - **Fonte**: [acidentes_pi.csv](https://github.com/zaleoz1/Topicos-de-Big-Data/blob/main/acidentes_pi.csv)
   
2. **`trabalho.py`**
   - Script em Python responsável por realizar a análise dos dados e gerar gráficos.
   - Utiliza as bibliotecas:
     - `pandas` para manipulação de dados,
     - `matplotlib` para geração de gráficos,
     - `numpy` para operações numéricas.
   - **Fonte**: [trabalho.py](https://github.com/zaleoz1/Topicos-de-Big-Data/blob/main/trabalho.py)

---

## Análises e Resultados

### **Análises Realizadas**

1. **Acidentes por Trimestre**
   - Os dados foram organizados por trimestre para identificar os períodos com maior ocorrência de acidentes.

2. **Acidentes por Dia da Semana**
   - Estatísticas sobre os dias da semana com maior número de acidentes.

3. **Intervalos de Horários**
   - Agrupamento dos horários dos acidentes em intervalos de 3 horas.

4. **Fase do Dia**
   - Distribuição dos acidentes por diferentes fases do dia (ex.: manhã, tarde, noite).

5. **Condições Meteorológicas**
   - Análise das condições climáticas durante os acidentes.

6. **Traçado da Via**
   - Identificação dos 10 tipos de traçados das vias com maior número de acidentes.

7. **Tipos de Veículo**
   - Principais tipos de veículos envolvidos em acidentes.

8. **Causas dos Acidentes**
   - Identificação das principais causas dos acidentes.

9. **Tipos de Acidentes**
   - Classificação dos acidentes por tipo (ex.: colisão frontal, atropelamento, etc.).

10. **Acidentes por Município**
    - Ranking dos municípios com maior número de acidentes.

11. **Resultados por Veículo**
    - Percentual de feridos, ilesos e mortos nos 5 tipos de veículos com mais acidentes.

12. **Acidentes por Rodovia**
    - Rodovias com mais acidentes e os quilômetros mais críticos.

---

### **Gráficos Gerados**
Os gráficos foram gerados para facilitar a visualização das análises realizadas:
- **Acidentes por Trimestre**
- **Acidentes por Dia da Semana**
- **Acidentes por Intervalo de Horário**
- **Acidentes por Fase do Dia**
- **Acidentes por Condição Meteorológica**
- **Acidentes por Traçado da Via**
- **Acidentes por Tipo de Veículo**
- **Principais Causas dos Acidentes**
- **Principais Formas de Acidentes**
- **Acidentes por Município**
- **Distribuição de Feridos, Ilesos e Mortos**
- **Percentual de Ilesos, Feridos e Mortos por Tipo de Veículo**
- **Rodovias com Mais Acidentes**
- **Trechos com Mais Casos nas 5 Rodovias com Mais Acidentes**

---

## Tecnologias Utilizadas

- **Python**: 100% do código, com bibliotecas:
  - `pandas`
  - `matplotlib`
  - `numpy`

---

## Como Executar

1. Certifique-se de ter Python instalado em sua máquina.
2. Instale as bibliotecas necessárias:
   ```bash
   pip install pandas matplotlib numpy
