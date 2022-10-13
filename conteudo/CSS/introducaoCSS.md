*{ /*pegou todo documento html e tirou a margem*/
    margin:0;
  }
h1, h2 { Podemos agrupar elementos com a mesma formataçao colocando virgula + elemento 
    color: blue; /*cor da fonte*/
    font-size: 60px; /*tamanho da fonte*/
    background: gray; /*fundo do h1*/
}
  
  /*Seletors - conecta um elemento html com o css
  */
  #container{
    width: 250px; /*Largura*/
    
  }
  .m-40{
    margin: 40px; /*margem da caixa*/
    
  }

  h1 {
    border: 1px solid red; /* borda da caixa*/
    margin: 200px; /*espaçamento por fora da caixa */
    padding: 60px; /* preenchimento interno*/
  }


!important

São raras as ocasiões nas quais se devem usar um iportant, pois é em geral uma má pratica, visto que quebra o fluxo natural da cascata e pode acabar te atrapalhando caso você a deixe em algum lugar no seu código.
