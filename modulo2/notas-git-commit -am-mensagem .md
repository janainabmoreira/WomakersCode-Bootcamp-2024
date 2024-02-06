# Notas de Aula Referente ao Módulo 2 do Curso: Git e GitHub da WomarksCode 2024

O comando **git commit -am "mensagem"** no Git é uma forma abreviada de realizar duas ações comuns em um único comando. Aqui está o que cada parte faz:


O comando git commit -am 'mensagem' no Git é uma forma abreviada de realizar duas ações comuns em um único comando. Aqui está o que cada parte faz:

## git commit: 
Este comando é usado para salvar as mudanças feitas no repositório. Ele cria um novo commit que armazena o estado atual do seu projeto.

## -a: 
Esta opção indica ao Git para incluir automaticamente todas as mudanças nos arquivos rastreados (já adicionados ao repositório) no commit. Isso evita a necessidade de usar o comando git add separadamente para cada arquivo modificado.

## -m "mensagem": 
Esta opção permite que você inclua uma mensagem de commit diretamente na linha de comando. A mensagem de commit descreve brevemente as alterações feitas no commit.

## IMPORTANTE
Portanto, o comando git commit -am 'mensagem' faz o commit de todas as alterações nos arquivos rastreados e adiciona uma mensagem de commit ao mesmo tempo. Este é um atalho útil quando você fez pequenas alterações e deseja realizar um commit rápido. **No entanto, tenha cuidado ao usá-lo, pois ele não adicionará ou realizará commit de alterações nos arquivos não rastreados (novos arquivos). Se você adicionou novos arquivos, ainda precisará usar git add para incluí-los no commit.**