# Protótipo de Sistema Automatizado de Limpeza de Placas Solares com Controle Web e Alimentação Autônoma

## 📝 Resumo do Projeto
Este projeto apresenta o desenvolvimento de um protótipo em escala reduzida para limpeza a seco de painéis fotovoltaicos utilizando o microcontrolador ESP32, escova cilíndrica de nylon e monitoramento remoto em tempo real via interface web integrada ao Firebase. 

O mecanismo demonstrou uma **eficiência média global de 94,0% na remoção mecânica de partículas** e validou a restauração da capacidade de geração elétrica através de ensaios comparativos de carregamento.

---

## 📺 Demonstração em Vídeo
▶️ **[Clique aqui para assistir ao vídeo de demonstração do protótipo no Google Drive](https://drive.google.com/file/d/1mZMj68gSKPB6pUv0N98ByAwMNWDLgsBo/view?usp=drive_link)**

---

## 📜 Artigo Científico Final (V-06)
📕 **[Clique aqui para ler o artigo completo em PDF](documentos/Artigo_Limpeza_Paineis_Fotovoltaicos.pdf)**

---

## ⚙️ Principais Recursos e Tecnologias
- **Hardware & Automação:** Microcontrolador ESP32 (WROOM-32), Drivers de acionamento BTS7960, Motores DC de alto torque, Sensores de Tensão e Sensores Ultrassônicos (HC-SR04).
- **Armazenamento & Nuvem:** Google Firebase (Realtime Database para sincronização em tempo real e Firebase Authentication para controle de acesso).
- **Interface Web:** Desenvolvida em HTML, CSS e JavaScript hospedada via GitHub Pages.
- **Engenharia & Modelagem:** Diagramas elétricos desenhados no EPLAN Electric P8 e modelagem mecânica 3D desenvolvida no Autodesk Inventor (conjunto modular de 23,75 kg distribuído em 8 rodas de elastômero).

---

## 📂 Estrutura do Repositório
- `/documentos`: Contém o artigo científico final do TCC em formato PDF.
- `/firmware`: Código-fonte (.ino) desenvolvido para o ESP32.
- `/interface-web`: Arquivos de código do painel de controle web (HTML/CSS/JS).
- `/eletrica`: Esquemas elétricos e diagramas gerados no EPLAN.
- `/mecanica`: Arquivos de modelagem completa (peças e conjuntos) do Autodesk Inventor.

---

## 🛠️ Análise de Engenharia (FMEA)
Foi aplicada a metodologia **FMEA (Failure Mode and Effects Analysis)** para mapear vulnerabilidades do projeto a longo prazo, definindo ações preventivas em software e hardware contra:
- Risco de microabrasões no vidro temperado por partículas rígidas externas.
- Perda de eficiência de varredura por desgaste natural das cerdas de nylon.
- Acúmulo de contaminantes aderidos (oleosidade/umidade).

---

## 🎓 Autores e Filiação Acadêmica

### Integrantes:
* Augusto Araujo Bueno
* Bruno Kayki Ribeiro de Souza
* Gustavo da Paz Coelho
* Itamar Silva de Sousa Júnior
* Rubens Melo de Souza

### Orientador:
* Me. Antônio José do Couto Pitta

### Instituição:
* Faculdade Engenheiro Salvador Arena (FESA)
* Bacharelado em Engenharia de Controle e Automação

---

## 📚 Como Citar este Trabalho (ABNT)

BUENO, A. A.; SOUZA, B. K. R.; COELHO, G. P.; SOUSA JÚNIOR, I. S.; SOUZA, R. M. **Protótipo de sistema automatizado de limpeza de placas solares com controle web e alimentação autônoma**. 2026. Artigo (Graduação em Engenharia de Controle e Automação) - Faculdade Engenheiro Salvador Arena, São Bernardo do Campo, 2026.
