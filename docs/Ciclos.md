<h1>Life Cycle Hooks</h1>

    //Executa quando o componente é montado e iniciado
    1. ngOnInit( )
<br/>

    //Executar quando o valor da propriedade é alterado via input()
    2. ngOnChanges( )
<br/>

    //Executa quando propriedades do componente são verificadas
    3. ngDoCheck( )


<h1>Eventos de Check</h1>

    //Executa quando Angular realiza qualquer projeção de conteúdo em seus componentes
    3.1 ngAfterContentInit( )

<br/>

    //Executa sempre que conteúdo do componente é verificado pelo mecanismo de alteração do Angular
    3.2 ngAfterContentCheck( )

<br/>

    //Executa depois que um componente é totalmente inicializado (carregou tudo)
    3.3 ngAfterViewInit( )

<br/>

    //Executa quando a visualização de um componente é verificado pelo algoritmo de detecção do Angular
    3.4 ngAfterViewChecked( )

<h1>Evento ao destruir</h1>