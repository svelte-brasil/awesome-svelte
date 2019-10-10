# Bind Value e Operações Matemáticas

```
<script>
	let number = 0;
</script>
<input type="number" bind:value="{number}">
<h1>Seu dobro é {number*2}!</h1>
<h1>Sua metade é {number/2}!</h1>
<h1>Menos 42 é {number-42}!</h1>
<h1>Mais 42 é {number+42}!</h1>
```

Criando o number, eu posso atrelar o seu valor no input, fazendo com que as informações abaixo dele sempre sejam atualizadas, com a expressão `bind:value={number}`.