---

## 📖 Sobre o Projeto

Este utilitário foi desenvolvido para resolver o trabalho repetitivo de criação de itens no Zabbix. Ele lê a estrutura de um arquivo JSON e gera um arquivo de template pronto para importação, suportando as duas principais metodologias de monitoramento:

1.  **Regra de Descoberta (LLD):** Gera automaticamente a `Discovery Rule` e os `Item Prototypes`. Ideal para quando o JSON contém uma lista de elementos dinâmicos (ex: partições de disco, serviços, etc).
2.  **Itens Estáticos:** Cria itens fixos diretamente no template. Ideal para métricas específicas e constantes.

## 🛠️ Como Utilizar (Executável Windows)

Por ser um programa compilado (`.exe`), você não precisa instalar Python ou qualquer outra dependência. 

### Passo a Passo:
1. Baixe o arquivo exe **[EXE](https://github.com/Wigney-Sarmento/WigBix/archive/refs/heads/main.zip)** deste repositório.
2. Execute o programa no seu Windows.
3. Selecione o arquivo JSON de origem.
4. Escolha o modo de geração (**Estático** ou **LLD**).
5. Salve o arquivo gerado (`.yaml`).
6. No Zabbix, vá em **Data Collection > Templates > Import** e selecione o arquivo gerado pelo programa.
