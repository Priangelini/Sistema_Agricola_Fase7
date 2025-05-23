# FIAP - Faculdade de Informática e Administração Paulista

<img src="https://www.fiap.com.br/wp-content/themes/fiap2016/images/logo.png" alt="FIAP" width="200"/>

## Sistema Agrícola Inteligente – Fase 7  
**Grupo: Beginner Coders**

---

### 👩‍💻 Integrantes:
- Luana Porto Pereira Gomes  
- Luma Oliveira  
- Priscilla Oliveira  
- Paulo Bernardes  

---

### 👨‍🏫 Professores:
**Tutor:**  
- [Leonardo Ruiz](https://github.com/leoruiz197)

**Coordenador:**  
- André Godoi

---

### 📚 Descrição

Este projeto consolida todas as entregas das Fases 1 a 6 do curso de Inteligência Artificial da FIAP em um sistema integrado para gestão agrícola. O sistema permite calcular insumos, gerenciar sensores de irrigação, visualizar dados em tempo real via dashboard, realizar classificações com visão computacional e emitir alertas via AWS.

---

### 🌱 Sobre o Projeto

Cada fase do projeto foi integrada em um sistema coeso e funcional:

- **Fase 1:** Cálculo de área de plantio e insumos agrícolas.
- **Fase 2:** Estruturação de banco de dados relacional Oracle.
- **Fase 3:** Sensoriamento com ESP32 e leitura de umidade, pH e NPK.
- **Fase 4:** Dashboard interativo em Python com Streamlit.
- **Fase 5:** Alerta inteligente via Amazon SNS com envio de e-mail/SMS.
- **Fase 6:** Visão computacional com YOLO para detecção de anomalias.

---

### 📁 Estrutura de Pastas

```
fase7-sistema-agricola/
│
├── fase1_calculo_area_insumos/
├── fase2_banco_dados/
├── fase3_iot_irrigacao/
├── fase4_dashboard/
├── fase5_aws_servicos/
├── fase6_visao_computacional/
├── main.py
├── requirements.txt
└── README.md
```

---

### 🖥️ Como Executar o Projeto

1. Clone o repositório:
```bash
git clone https://github.com/SeuUsuario/Sistema_Agricola_Fase7.git
cd Sistema_Agricola_Fase7
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Rode a aplicação:
```bash
streamlit run main.py
```

---

### ☁️ Integração com a AWS

Utilizamos o **Amazon SNS** para envio de alertas automáticos com base nos dados de sensores e visão computacional.  
📷 *Prints e comentários estão na pasta `/fase5_aws_servicos/`.*

---

### 🎥 Vídeo de Demonstração

[📺 Clique aqui para assistir no YouTube](https://youtu.be/SEULINK)

---

### 🛠 Tecnologias Utilizadas
- Python, Streamlit
- Oracle Database
- ESP32 (simulado)
- OpenCV, Scikit-Learn
- Amazon Web Services (SNS)
