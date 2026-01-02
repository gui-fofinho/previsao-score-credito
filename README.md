# 💳 Previsão de Score de Crédito com Inteligência Artificial

Este projeto utiliza **Python**, **Machine Learning** e **Streamlit** para prever o **score de crédito** de clientes de um banco, classificando-os como:

- **Ruim**
- **Ok**
- **Bom**

O modelo foi treinado com uma base de dados realista e disponibilizado em uma **interface web interativa**, permitindo a simulação do score de crédito de novos clientes.

---

## 🚀 Funcionalidades

- Treinamento de modelo de Machine Learning (**Random Forest**)
- Tratamento e codificação automática de variáveis categóricas
- Interface web interativa com **Streamlit**
- Previsão do score de crédito a partir de dados informados pelo usuário
- Seleção de campos categóricos por nome (profissão, tipo de crédito, comportamento de pagamento)

---

## 🧠 Tecnologias utilizadas

- **Python**
- **Pandas**
- **Scikit-learn**
- **Streamlit**

---

## 📦 Estrutura do projeto

```text
📦 previsao-score-credito
 ┣ 📄 app.py
 ┣ 📄 clientes.csv
 ┣ 📄 requirements.txt
 ┣ 📄 README.md

▶️ Como executar o projeto localmente
1️⃣ Instalar as dependências

No terminal, execute:

pip install -r requirements.txt

2️⃣ Executar a aplicação

⚠️ IMPORTANTE:
Este projeto deve ser executado utilizando o Streamlit.

streamlit run app.py

Após executar o comando:

- o navegador será aberto automaticamente
-  a interface do sistema estará pronta para uso

🖥️ Aplicação online

Você também pode acessar a aplicação rodando online no Streamlit Cloud:
   https://owner-avatar-python-ia-inteligencia-artificial-e-previsoes-6y3.streamlit.app/


📊 Sobre os dados utilizados

-clientes.csv contém informações como:

   idade;
   profissão;
   salário anual;
   histórico de crédito;
   comportamento de pagamento;

-Esses dados são utilizados para treinar o modelo de previsão

📚 Observações

Projeto com finalidade educacional
Ideal para estudo de:

   -Machine Learning
   -classificação de dados
   -integração de modelos com interface web

Pode ser expandido com:

   -salvamento do modelo treinado
   -gráficos de análise
   -explicação da previsão (feature importance)

👨‍💻 Autor

Projeto desenvolvido por Guilherme Matté
Durante o curso da Hashtag Treinamentos

   
