# 🏷️ Gerador de Etiquetas

Este projeto é um gerador de etiquetas desenvolvido em Python e empacotado com Inno Setup para distribuição no Windows.

## 📁 Conteúdo

O instalador inclui:
- `etiqueta.exe`: Aplicação principal
- `Produtos.csv`: Ficheiro com a lista de produtos
- Ícone personalizado
- Atalho no ambiente de trabalho
- Desinstalador automático

## 🖥️ Requisitos

- Sistema operativo: **Windows 10 ou superior**
- Impressora compatível (ex: Citizen)
- Drivers da impressora (opcional: pasta `Seagull`)

## 🚀 Instalação

1. Copie para o computador destino:
   - `Instalador_Etiquetas.exe`
   - `Produtos.csv`
   - (Opcional) Pasta `Seagull` com drivers da impressora
   - Ficheiro `INSTALAR_IMPRESSORA.txt` com instruções

2. Execute `Instalador_Etiquetas.exe`.

3. Siga os passos do instalador:
   - Uma pasta será criada em `C:\Program Files\Gerador de Etiquetas`
   - Um atalho será criado automaticamente no ambiente de trabalho

4. (Opcional) Instale a impressora:
   - Siga o ficheiro `INSTALAR_IMPRESSORA.txt`
   - Execute `DriverWizard.exe` da pasta `Seagull`

## 🧹 Desinstalação

- Pode ser desinstalado pelo **Painel de Controlo > Programas > Desinstalar um programa**
- Ou usando o atalho criado no Menu Iniciar

---

Desenvolvido com ❤️ para facilitar o processo de geração e impressão de etiquetas.
