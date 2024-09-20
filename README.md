Atividade do Curso de Desenvolvimento de Sistema do Professor Silvio, mais conhecido como Solado 0.

Installation:
```bash
Set-ExecutionPolicy RemoteSigned
npm install -g nodemon
nodemon index.js
```

Caso ocorra o erro, veja as alterações
necessárias.

1 - Abra o PowerShell como Administrador:

Clique com o botão direito no menu Iniciar e
selecione "Windows PowerShell (Admin)" ou
"Windows Terminal (Admin)" se estiver disponível.

2 - Verifique a Política de Execução Atual:

Digite o seguinte comando para ver a política de
execução atual:

```
Get-ExecutionPolicy
```
Isso geralmente retorna Restricted, o que significa
que a execução de scripts está desabilitada.

3 - Alterar a Política de Execução:

Para permitir a execução de scripts, use o comando:

```bash
Set-ExecutionPolicy RemoteSigned
```
Isso permite a execução de scripts que você mesmo escreveu (locais) e
scripts baixados de outros lugares que são assinados por um editor
confiável.

Você será solicitado a confirmar a mudança. Digite Y e pressione Enter.

4 - Verifique se a Política foi Alterada:

Você pode verificar novamente a política de execução usando o
comando 
```
Get-ExecutionPolicy 
```
para garantir que a mudança foi aplicada.

