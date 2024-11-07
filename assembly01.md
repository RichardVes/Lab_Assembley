# Assembly Aula 01

# Introdução

---

## Comandos iniciais:

> **Iniciando o programa na memoria 00h**
>
> > org 00h
>
> **Fim do programa**
>
> > end
>
> **Rotulo**
>
> > nome_do_rotulo:
>
> **Incremento de valor em +1**
>
> > inc a
>
> **Movimentar valores pelo microcontrolador**
>
> > MOV (posição fim, posição inicial ou valor)
> >
> > > MOV a,r0
> > >
> > > MOV a,#10h[num]
> > >
> > > MOV r0,20H
> > >
> > > MOV 20h[mem]

# Operações Aritmeticas

Soma
ADD A,<byte><reg><mem>

SUBB A,<byte><reg><mem>

INC A // incremento

DEC A // Decremento

MUL AB //multiplica os registradores A e B

DIV AB // Divide os registradores a/b

DA A //ajuste decimal

**Outros Parametros**

> **jmp rotulo**
>
> > Salto direto (faz um looping para o rotulo)
>
> jmp $ --> salto direto, ( faz o programa parar nessa linha)
>
> RET // é nessa linha que volta do rotulo
>
> RETI // se tiver interrupção externa volta do rotulo aqui
