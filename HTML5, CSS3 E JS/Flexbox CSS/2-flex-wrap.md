<h2>Estrutura do flex wrap</h2>
    É a propriedade que define se os itens devem ou não quebrar a linha. Por padrão, eles não fazem essa quebra automática, fazendo com que os *flex itens* sejam compactados além do limite do conteúdo.
        **nowrap** é o padrão;
        **wrap** permite a quebra assim que um dos *flex items* não puder mais ser compactado;
        **wrap-reverse** faz o mesmo que o wrap, porém em direção oposta.

* Criei a classe *.flex-container* e dei display flex. Setei a *flex-direction* para column, defini *height*, *border* e *max-widht*
* Na classe *.item*, escolhi a *font-size*, *height*, alinhei o texto ao centro com *text-align* center, defini *min-width* e *line height*.
* Logo após, fiz as classes dos comportamentos que eu queria aplicar nos itens, no caso *nowrap*(padrão), *wrap* e *wrap-reverse*, além de classes para definir a cor de fundo dos itens.
* Criei os <div> em <body> para poder aplicar o comportamento das classes.