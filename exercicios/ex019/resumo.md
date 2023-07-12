# ID CSS # 

em HTML é id = em CSS é #
em HTML é class = em CSS é .

como selecionar o idn o css

ex: h1#principal { 
    background color: blue;
}
(**não se pode usar mais de um elemento**)
# CLASS CSS # 
 class no css é identificado por . não é necessário identificar o elemento, ele é usando sozinho .class (**pode ser utilizado mais de um elemento**)
 # HIERARQUIA #
 no css a ordem importa, e existe uma força em cada classificador do css, existem os gerais, h1,h2,body e etc... que tem uma força menor, então qualquer um q venha abaixo vai sobrepor ele, por exemplo:
 
 h1{
    color: white;
 }

 h1#principal{
    color: blue;
    **o h1 com o id principal será alterado, mesmos já estando setado como branco.**
 }
.destaque{
    color: red;
    **caso algum h1 esteja com a tag destaque vai sobrepor todas os outros seletores colocando a cor em vermelho**
}
