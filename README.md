# Frontend Mentor - NFT preview card component solution

Esta é uma solução para o [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). 
Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação criando projetos realistas.

## Layout do projeto em tela de Desktop/Notebook/Tablet/Mobile.

<div align="center">

  <img src="https://github.com/HumbertoFox/repository/assets/126817628/135639df-c468-4271-8cbe-1bd4e1b3154f" width="400px"/>

</div>

### O que aprendi

```css
  .a-img-main::after {
    display: flex;
    position: absolute;
    content: url(../images/icon-view.svg);
    background-color: var(--Cyan-trans);
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 100%;
    opacity: 0;
    border-radius: 7px;
    transition: .3s ease-in-out;
  }
  .a-img-main:hover::after {
    opacity: 1;
  }
```

### Construído com

- Marcação semântica HTML5
- Propriedades personalizadas CSS
- Caixa flexível
## Desenvolvido em:

<div>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="30px"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="30px"/>
</div>
