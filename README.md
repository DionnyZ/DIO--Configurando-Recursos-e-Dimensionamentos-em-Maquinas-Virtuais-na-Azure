# Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

O objetivo desse desafio foi escrever um resumo sobre a configuração de uma Máquina Virtual da Azure.

## Máquina Virtual

Existe uma página de padrões recomendados para as máquinas virtuais. É possível selecionar algumas opções para gerar uma configuração pré-definida, facilitando a criação. Outros serviços também possuem essas predefinições.

**Configurações de uma máquina virtual:**
- Assinatura
- Grupo de recursos
- Nome da máquina virtual
- Região
- Opções de disponibilidade
- Zona de disponibilidade
- Contagem de instâncias
- Modo de dimensionamento: pode ser feito automaticamente ou manualmente para escalonar conforme a necessidade
- Executar com desconto de Spot do Azure: é possível utilizar os recursos por um menor preço, porém com uma disponibilidade menor
- Tamanho da VM: são as configurações como memória RAM, CPUs, discos de dados, IOPs e outros
- Nome de usuário e senha
- Portas de entrada
- Tamanho do disco do SO
- Tipo de disco: SSD, HD
- Excluir o disco com a VM: é uma opção para excluir o disco junto ao VM ou não, pois os discos criados geram cobrança
- Desligamento automático: para evitar gastos desnecessários com VM ligadas sem necessidade
- Habilitar backup
- Alertas
- Marcações

No fim, é feito uma revisão com a previsão do preço.

Também é possível criar um pool para compartilhar a máquina virtual com outros usuários.

**Na criação de um Aplicativo de Funções, é necessário:**
- Selecionar a Pilha de runtime: que é a linguagem da função, como Python, .NET, Node.js, etc.
- Selecionar a versão
