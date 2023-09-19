# SapGuiApiHelper - Automatização Simplificada do SAP GUI

![GitHub](https://img.shields.io/github/license/Neitan96/SapGuiApiHelper)
![Static Badge](https://img.shields.io/badge/version-Alpha%200.2-blue)
![GitHub last commit](https://img.shields.io/github/last-commit/Neitan96/SapGuiApiHelper)
[![Python](https://img.shields.io/badge/python-3.9.6%2B-blue)](https://www.python.org/downloads/release/python-396/)
[![VBA](https://img.shields.io/badge/VBA-Excel-green)](https://docs.microsoft.com/en-us/office/vba/api/overview/excel)

Este repositório é uma coleção de APIs desenvolvidas em *Python* e *VBA* projetadas para simplificar e acelerar a criação de automações no SAP GUI (Graphical User Interface). O SAP GUI é uma ferramenta poderosa para interagir com sistemas SAP, mas sua automação muitas vezes requer códigos extensos e complexos. Nossas APIs têm como objetivo resolver esse problema, fornecendo funcionalidades pré-fabricadas que permitem que você automatize tarefas SAP de forma eficiente e sem a necessidade de codificação extensiva.

## Autor - **Nathan Almeida** (Neitan96):

[![GitHub](https://img.shields.io/badge/GitHub-Profile-black?style=flat&logo=github)](https://github.com/Neitan96)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/neitan96/)
[![Instagram](https://img.shields.io/badge/Instagram-Profile-orange?style=flat&logo=instagram)](https://www.instagram.com/neitan96/)


## Exemplos:
Aqui estão alguns exemplos de uso das APIs em Python e VBA:

#### Python
```python
sap_gui = SapGui()
session = sap_gui.GetSessionLoged()
```

## Melhorias futuras:
* Documentações e tutoriais
* Registro de execução e erros
* Funções para lidar com tabelas do SAP
  * Funções para selecão de layouts
* Funções para pop-ups padrões:
  * Seleção multipla
  * Filtros
  * Etc
* Verificar tela de login ao verificar timeout
* Funções para lidar com a maioria dos companetes do SAP Gui
* Funções para ajudar em eventos do SAP
* Funções para lidar com exportações de arquivos
* Funções para ler arquivos para interagir com SAP

### Melhorias para Python:
* Classes que refletem a API do SAP Gui

### Melhorias para VBA:
* Voltar ao menu principal ao fazer login
* Retorna a nova sessão ao fazer login, para os casos que criamos nova sessão para login

## Aviso Legal

Este projeto não é afiliado, endossado ou mantido pela SAP SE. SAP é uma marca registrada da SAP SE em vários países.