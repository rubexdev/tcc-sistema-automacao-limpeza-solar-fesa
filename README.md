# Protótipo de Sistema Automatizado de Limpeza de Placas Solares com Controle Web e Alimentação Autônoma

## 📝 Resumo do Projeto
Este projeto apresenta o desenvolvimento de um protótipo em escala reduzida para limpeza a seco de painéis fotovoltaicos utilizando o microcontrolador ESP32, escova cilíndrica de nylon e monitoramento remoto em tempo real via interface web integrada ao Firebase. O sistema foi validado por meio de ensaios experimentais controlados e uma análise de modos de falha (FMEA).

---

## 📺 Demonstração em Vídeo
▶️ **[Clique aqui para assistir aos vídeos de demonstração do protótipo no Google Drive](https://drive.google.com/file/d/1mZMj68gSKPB6pUv0N98ByAwMNWDLgsBo/view?usp=drive_link)**

---

## 📜 Artigo Científico
📕 **[Clique aqui para ler o artigo completo em PDF](documentos/Artigo_Limpeza_Painéis_Fotovoltáicos.pdf)**

---

## ⚙️ Principais Recursos e Tecnologias
- **Hardware & Automação:** Microcontrolador ESP32 (WROOM-32), Drivers de acionamento BTS7960, Motores DC de alto torque e sensores fim de curso.
- **Armazenamento & Nuvem:** Google Firebase (Realtime Database para sincronização em tempo real e Firebase Authentication para controle de acesso).
- **Interface Web:** Desenvolvida em HTML, CSS e JavaScript hospedada via GitHub Pages.
- **Engenharia & Modelagem:** Diagramas elétricos desenhados no EPLAN Electric P8 e modelagem mecânica 3D desenvolvida no Autodesk Inventor.

---

## 📂 Estrutura do Repositório
- `/documentos`: Contém o artigo científico completo do TCC em formato PDF.
- `/firmware`: Código-fonte (.ino) desenvolvido para o ESP32.
- `/interface-web`: Arquivos de código do painel de controle web (HTML/CSS/JS).
- `/eletrica`: Esquemas elétricos e diagramas gerados no EPLAN.
- `/mecanica`: Arquivos de modelagem completa (peças e conjuntos) do Autodesk Inventor.

---

## 🛠️ Análise de Engenharia (FMEA)
Como parte do desenvolvimento e validação do processo industrial do sistema, foi aplicada a metodologia **FMEA (Failure Mode and Effects Analysis)** para mitigar riscos operacionais do protótipo, abordando fatores críticos como:
- Desgaste prematuro das cerdas de nylon.
- Riscos de microabrasões na superfície de vidro dos painéis.
- Tratamento de contaminantes aderidos (oleosidade/umidade) e a eficiência do método de limpeza a seco.

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
