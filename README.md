# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Consolidação do Sistema Agrícola

## Beginner Coders

---

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/luana-porto-pereira-gomes/">Luana Porto Pereira Gomes</a>
- <a href="https://www.linkedin.com/in/luma-x">Luma Oliveira</a>
- <a href="https://www.linkedin.com/in/priscilla-oliveira-023007333/">Priscilla Oliveira </a>
- <a href="https://www.linkedin.com/in/paulobernardesqs?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app">Paulo Bernardes</a> 

---

## 👨‍🏫 Professores:
### Tutor:
- <a href="https://www.linkedin.com/in/leonardoorabona/">Leonardo Ruiz</a>

### Coordenador:
- <a href="https://www.linkedin.com/in/profandregodoi/">André Godoi</a>

---

## 📜 Descrição

Este projeto consolida todas as entregas das Fases 1 a 6 do curso de Inteligência Artificial da FIAP em um sistema integrado para gestão agrícola. O sistema permite calcular insumos, gerenciar sensores de irrigação, visualizar dados em tempo real via dashboard, realizar classificações com visão computacional e emitir alertas via AWS.

---

## 📝 Sobre o Projeto

Cada fase do projeto foi integrada em um sistema coeso e funcional:

- **Fase 1:** Cálculo de área de plantio e insumos agrícolas.
- **Fase 2:** Estruturação de banco de dados relacional Oracle.
- **Fase 3:** Sensoriamento com ESP32 e leitura de umidade, pH e NPK.
- **Fase 4:** Dashboard interativo em Python com Streamlit.
- **Fase 5:** Alerta inteligente via Amazon SNS com envio de e-mail/SMS.
- **Fase 6:** Visão computacional com YOLO para detecção de anomalias.

---

## 📁 Estrutura de Pastas

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

## 🖥️ Como Executar o Projeto


---

## ☁️ Integração com a AWS

Utilizamos o **Amazon SNS** para envio de alertas automáticos com base nos dados de sensores e visão computacional.  
📷 *Prints e comentários estão na pasta `/fase5_aws_servicos/`.*

---

## 🎥 Vídeo de Demonstração

[📺 Clique aqui para assistir no YouTube](https://youtu.be/)

---

## 🛠 Tecnologias Utilizadas
- Python, Streamlit
- Oracle Database
- ESP32 (simulado)
- OpenCV, Scikit-Learn
- Amazon Web Services (SNS)
