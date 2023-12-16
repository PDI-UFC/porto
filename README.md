# PDI - UFC - PORTO

Projeto para a cadeira de PDI da UFC-CE

## How to run

Dentro das pastas Backend e Frontend existe um README.md proprio que explica como configurar cada parte. Após subir os sistemas do backend e frontend seguindo o seus respectivos README's, há duas possibilidades: executar o programa python com a solução principal ou o programa da solução secundária. Só é necessário rodar os respectivos comandos abaixo para iniciar o script de processamento:

#### Main solution:
```python
python Video-Processing/trackship.py
```
#### Secondary solution:
```python
python Video-Processing/classic_segmentation.py
```

Em ambientes linux talvez seja necessário substituir ```python``` por ```python3``` para executar o interpretaor do python.



 Com isso, o script de processamento começa a enviar os dados de velocidade e distancia para o backend e você poderá ter acesso a eles no front do sistema. Para mais informações sobre o processamento, vale ler o README.md desse repositório.


 **OBS:** Dentro dos scripts 'Video-Processing/trackship.py' e 'Video-Processing/classic_segmentation.py' existe um campo para colar o endereço onde o servidor do backend está, caso haja alteração nas portas do backend, lembrar de alterar dentro do script de trackship, além disso checkar se os endereços do frontend também seguem a nova porta.

 > Queremos reforçar que cada uma das três partes do projeto contém README próprio para estudo.
