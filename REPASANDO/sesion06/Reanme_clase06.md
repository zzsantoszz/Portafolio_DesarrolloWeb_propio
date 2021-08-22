# el ancho y alto no lo considera los inline

## flex 
### PROPIEDADES para el EJE PRINCIPAL
# display: flex;
# flex-direction: row;
/*flex-direction: /* 󰘲 row | row-reverse | column | column-reverse ;*/
# justify-content: flex-end;
/*justify-content: center; /* 󰘲 normal | center | space-around | space-between | flex-start | flex-end */
# flex-wrap: no-wrap;
/* 󰘲 nowrap | wrap | wrap-reverse */
# une flex-direction y flex wrap
flex-flow: flex-direction flex-wrap;


### PROPIEDADES para el EJE SECUNDARIO
# align-items: center;
 /* 󰘲 normal | center | flex-start | flex-end | stretch |baseline */
# align-content: center;
/* 󰘲 normal | center | flex-start | flex-end |
space-around | space-between | stretch */
Nos permite posicionar / distribuir elementos (Eje secundario)
Igual que align-items, solo que align-content solo funciona cuando los
elementos están distribuidos en múltiples líneas