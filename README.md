# **Projeto EnergyWise**

## **Objetivo**
O projeto EnergyWise foi criado para prever a quantidade de energia que um condomínio (residencial ou de apartamentos) precisa armazenar para lidar com interrupções no fornecimento de energia. Essas interrupções podem ser causadas por:

- Danos nas placas solares.
- Excesso de neve ou poeira.
- Problemas climáticos, como falta de energia solar.

O foco principal é em sistemas elétricos cuja fonte primária de energia seja proveniente de placas solares.

---

## **Funcionalidades**

O EnergyWise conta com diversas funcionalidades que contribuem para a gestão de energia de forma eficiente:

1. **Rede Neural Treinada**:
   - Utiliza dados históricos gerados sinteticamente para prever necessidades energéticas.

2. **Aplicativo Mobile**:
   - Registro de informações sobre o condomínio.
   - Visualização do consumo de energia, armazenamento e geração


3. **API em Java**:
   - Desenvolvida para comunicação com o banco de dados.
   - Facilita a integração entre o aplicativo e o banco de dados.

4. **Interface Intuitiva**:
   - Design otimizado para usuários finais, com telas para criar, editar e excluir comunidades.

---

## **Inteligência Artificial Desenvolvida**

Para atender ao objetivo do projeto, desenvolvemos um modelo de regressão baseado no framework **Keras**:

- **Estrutura do Modelo**:
  - Utilizamos a classe `Sequential`, que permite organizar camadas de forma sequencial, uma após a outra.
  - Este modelo foi projetado para lidar com previsões de energia com alta precisão, considerando os dados da comunidade como quantidade de habitantes, energia consumida e afins.

- **Treinamento do Modelo**:
  - Baseado em dados históricos gerados sinteticamente, garantindo maior robustez e confiabilidade nas previsões.

---

## **Como Contribuir**

1. Faça um fork do repositório.
2. Crie uma branch para sua feature ou correção:
   ```bash
   git checkout -b minha-feature
