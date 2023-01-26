## Descrição:

 Este projeto tem como finalidade executar um robô de forma assistida utilizando o UiPath Studio.
 
 - Acessa o sistema web do Vincix Group;
 - Navega até a sessão nível 1 e realiza o download do arquivo excel para execução;
 - Trata os dados para leitura;
 - Insere os dados em fila do Orquestrador;
 - Processa os dados nos campos do formulário solucionando as perguntas das janelas pop-up que eventualmente aparecerão;
 - Efetua logout do sistema web Vincix Group;
 - Encerra o navegador;

## Instruções:

- Criar um fluxo de trabalho que insira dados de uma planilha nos campos do formulário na tela;
- Os campos mudarão de posição na tela após cada envio ao longo de 10 rodadas, portanto;
- O fluxo deve identificar corretamente onde cada registro da planilha deve ser digitado todas as vezes;

## Requisitos:

 Os requisitos para a execução deste robô são:

- Ter o navegador Google Chrome instalado;
- Ter a extensão UiPath Automation para guias anônimas ativada;
- Ajustar arquivo de configuração 'Data\Config.xlsx' conforme os parâmetros do usuário;
