# Carousel (svelte-carousel)

O carousel é uma das mais comuns formas de criar uma galeria onde se rotaciona imagens. 

Para utilizar, no diretório raiz do projeto, instale os seguintes pacotes via `npm`

```
  npm i -D @beyonk/svelte-carousel
```
Para a lib 

```
  npm i -D svelte-feather-icons
```
Para os ícones de seta para esquerda e direita.

No exemplo abaixo foi utilizado imagens do [unsplash](https://unsplash.com)

```
<script>
	import Carousel from '@beyonk/svelte-carousel'
	import { ChevronLeftIcon, ChevronRightIcon } from 'svelte-feather-icons'
</script>
<Carousel>
  <span class="control" slot="left-control">
    <ChevronLeftIcon />
  </span>
  <div class="slide-content"><img src="https://images.unsplash.com/photo-1570942872213-1242607a35eb?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60"></div>
  <div class="slide-content"><img src="https://images.unsplash.com/photo-1569834381156-7b735e41e57d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60"></div>
  <div class="slide-content"><img src="https://images.unsplash.com/photo-1569402604464-6f466a53141e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60"></div>  
  <div class="slide-content"><img src="https://images.unsplash.com/photo-1569191086551-b3606745884f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60"></div>  
  <div class="slide-content"><img src="https://images.unsplash.com/photo-1569261995036-70d0dd50be24?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60"></div>  
  <span class="control" slot="right-control">
    <ChevronRightIcon />
  </span>
</Carousel>
```
