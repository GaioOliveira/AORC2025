# Exercícios com Assembly MIPS

### 1. Criar um código em Assembly MIPS com 2 arrays para armazenar 7 números inteiros cada um. Somar os elementos nas posições correspondentes e armazenar o resultado em um terceiro array.

### Lembre-se:

Reservando 4 bytes na memória indicado pelo rótulo var:
``` 
.data
var .space 4
```

Gravando o endereço de memória ocupado por var no registrador $t2:
``` 
.text
la $t2, var 
```

Armazenando o inteiro imediato 100 no registrador $s3:
```
li $s3, 100
```

Gravando na memória no endereço de var guardado em $t2 o valor no registrador $s3:
```
sw $s3, $t2
```

### 2. Criar um código Assembly MIPS para guardar uma string em uma variável e imprimi-la na tela.
