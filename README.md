# 🚀 Zabbix Template Generator (JSON-to-Zabbix)

![Zabbix](https://img.shields.io/badge/Zabbix-6.0%2B-red?style=for-the-badge&logo=zabbix&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

Uma ferramenta poderosa para automatizar a criação de templates do Zabbix a partir de arquivos JSON, suportando tanto **LDR (Low-Level Discovery)** quanto **Itens Estáticos**.

## 💡 O Problema
Criar templates manualmente no Zabbix para grandes volumes de dados JSON é repetitivo, demorado e suscetível a erros humanos. 

## ✨ A Solução
Este programa lê a estrutura de um JSON e gera automaticamente o arquivo XML/YAML pronto para importação no Zabbix, oferecendo duas abordagens:

1.  **Regras de Descoberta (LLD):** Ideal para dados dinâmicos (ex: discos, interfaces de rede, processos).
2.  **Itens Estáticos:** Ideal para métricas fixas e conhecidas, garantindo simplicidade e performance.

## 🛠️ Tecnologias Utilizadas
* [Linguagem, ex: Python/Node.js]
* Bibliotecas: [ex: Pandas, Jinja2, etc]

## 🚀 Como Usar

### Pré-requisitos
* [Ex: Python 3.x instalado]
* [Ex: Pip para instalar dependências]

### Instalação
```bash
# Clone o repositório
git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)

# Entre na pasta
cd seu-repositorio

# Instale as dependências
pip install -r requirements.txt
