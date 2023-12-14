# PDI - UFC - PORTO

Projeto para a cadeira de PDI da UFC-CE

## How to run

Dentro das pastas Backend e Frontend existe um readme.md proprio que explica como configurar cada parte. Após subir os sistemas do backend e frontend seguindo o seus respectivos readmes você só precisará rodar o comando a baixo para iniciar o script de processamento:

```bash
  $ python3 trackship.py
```
 com isso o script de processamento começa a enviar os dados de velocidade e distancia para o backend e você poderá ter acesso a eles no front do sistema


 OBS: Dentro do script de trackship.py existe um campo para colar o endereço onde o servidor do backend está, caso haja alteração nas portas do backend, lembrar de alterar dentro do script de trackship, além disso checkar se os endereços do frontend também seguem a nova porta
