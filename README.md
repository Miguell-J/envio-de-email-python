# envio de email com python

Este é um código de automação de envio de email utilizando a biblioteca PyAutoGUI em Python. O código é projetado para abrir o navegador Chrome, acessar o Gmail, preencher os campos necessários e enviar uma mensagem. Abaixo, você encontrará um guia passo a passo sobre como usar esse código.

## Pré-requisitos

Antes de executar este código, certifique-se de que você tenha o Python instalado em seu sistema. Além disso, instale a biblioteca PyAutoGUI usando o seguinte comando:

```bash
pip install pyautogui
```

## Como usar

- pyautogui.press (pressiona uma tecla)
- pyautogui.click (clica com o cursor na posição x,y)
- pyautogui.hotkey (aciona uma hotkey do teclado)

### O código automatizará os seguintes passos:

- Abre o navegador Chrome.
- Acessa o site do Gmail.
- Clica na caixa de composição de email.
- Preenche o destinatário com "seu email".
- Insere o assunto do email como "apenas um teste".
- Digita "Olá" no corpo do email.
- Envia o email pressionando Ctrl+Enter.
- Certifique-se de que você está logado em sua conta do Gmail no Chrome antes de executar o código.

O código contém intervalos de tempo (time.sleep) para aguardar a carga das páginas e evitar erros de execução. Você pode ajustar esses tempos conforme necessário.

Lembre-se de que a automação de tarefas pode ser sensível e pode variar dependendo do seu sistema e configurações específicas. Certifique-se de testar o código em um ambiente controlado e seguro, de preferência em uma conta de teste do Gmail.

### Nota
Este código é apenas um exemplo de automação simples. Para uso em produção ou tarefas mais complexas, é recomendável considerar outras abordagens, como usar APIs de email ou bibliotecas de automação mais avançadas. Tenha em mente que o uso indevido de automação pode violar os termos de serviço de serviços online, como o Gmail, então use-o com responsabilidade.
