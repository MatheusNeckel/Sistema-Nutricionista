# Sistema de Nutricionista 🥗

Sistema desktop em **Java (Swing)** para **cálculo de IMC**, **estimativa de gasto calórico diário** e **recomendações nutricionais**.  
Projeto acadêmico com foco em **POO** e organização de camadas.

<p align="left">
  <img alt="Java" src="https://img.shields.io/badge/Java-8%2B-orange">
  <img alt="Build" src="https://img.shields.io/badge/build-Ant-blue">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-success">
</p>

---

## ✨ Funcionalidades
- 📏 Cálculo de **IMC (Índice de Massa Corporal)**
- 🔥 Estimativa de **gasto calórico diário**
- 🥦 **Recomendações nutricionais** simples
- 🖥️ Interface **Swing** com telas dedicadas (IMC, Gasto Calórico, Recomendações)

---

## 🧰 Tecnologias
- Java 8+ (POO, Swing)
- NetBeans/Ant

---

## ⚙️ Como executar

> **Importante:** publique quaisquer **.zip** do projeto em **Releases**; mantenha o **código-fonte descompactado** no repositório para melhor visualização.

### 1) Pré-requisitos
- **Java 8+**
- **NetBeans** (ou outra IDE compatível)

### 2) Abrir o projeto
- Extraia o código-fonte (se estiver em `.zip`) para a **raiz do repositório**.
- Abra o projeto no **NetBeans**.

### 3) Executar
- Compile e execute a **classe principal** (ex.: `TelaInicial.java`).

---

## 📁 Estrutura sugerida
```
/README.md
/LICENSE
/.gitignore
/.github/workflows/build.yml
/src/
  TelaInicial.java
  TelaIMC.java
  TelaGastoCalorico.java
  TelaRecomendacoes.java
nbproject/            # se NetBeans/Ant
```
> Mantenha apenas **código-fonte e configs** no versionamento. Binários e zips devem ir nas **Releases**.

---

## 🧪 CI (GitHub Actions)
Este repositório inclui um workflow de exemplo para compilar com **Ant** (se `build.xml` existir).

---

## 📝 Licença
Distribuído sob a licença **MIT**. Veja `LICENSE` para mais detalhes.
