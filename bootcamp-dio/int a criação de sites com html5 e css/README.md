# INTRODUÇÃO A CRIAÇÃO DE WEBSITES COM HTML5 E CSS3
## HISTÓRIA DO HTML
         .CRIADORES
         .COMO SURGIU
         .QUAL O OBJETIVO
## HTML SEMÂNTICO
### TAGS:
**HEADER**: É UTILIZADO PARA REPRESENTAR O CABEÇALHO DE UM DOCUMENTO.
        NELE PODEMOS INSERIR ELEMENTO COMO h1 ATÉ h6 E O NAV.

**NAV**: É UTILIZADO PARA REPRESENTAR UM AGRUPAMENTO DE LINKS DE NAVEGAÇÃO.

**MAIN**: ESPECIFICA O CONTEÚDO PRINCIPAL E, CONSEQUENTEMENTE, DE MAIOR
        RELEVÂNCIA DENTRO DA PÁGINA.

**SECTION**: REPRESENTA UMA SEÇÃO DENTRO DE UM DOCUMENTO E GERALMENTE CONTÉM 
            UM TÍTULO QUE É DEFINIDO PELOS ELEMENTOS h1 ATÉ h6.

**ARTICLE**: É UTILIZADO QUANDO PRECISAMOS DECLARAR UM CONTEÚDO QUE NÃO PRECISADE OUTRO PARA FAZER SENTIDO EM UM DOCUMENTO HTML, POR EXEMPLO,  UM           ARTIGO EM  UM BLOG.

**ASIDE**: É UTILIZADO QUANDO PRECISAMOS CRIAR UM CONTEÚDO DE APOIO/ADICIONAL AO 
            CONTEÚDO PRINCIPAL.

**FOTTER**: REPRESENTA UM RODAPÉ DE UM DOCUMENTO, COMO A ÁREA PRESENTE NO FINAL 
            DE UMA PÁGINA WEB. NORMALMENTE UTILIZADA PARA INFORMAÇÕES DE AUTORIA, 
            CONTATO E DATA DE CRIAÇÃO DO AUTOR.
## TAGS HTML(TEXTOS, LINKS,IMAGENS E LISTAS)
### TAGS DE TEXTO
    h1 até h6
    p: indica uma parágrafo
### TAG PARA LINK
    a: indica um link e, para funcionar, precisa botar a url do link detro do atributo href
    ATRIBUTO target:  indica como esse nosso link vai ser aberto, o valor mais usado é o "_blak"
    ATRIBUTO href com prefixo mailto:  indica a caixa de mansagem do email especificado, onde o cliente
    será redirecionado ao clicar no link
### TAG IMG
    img:  serve para por uma imagem na página, para funcionar é preciso botar a url da imagem no atributo src
    ATRIBUTO alt:  indica a descrição da imagem, serve para a questão de acessibilidade
    DICA IMPORTANTE:  VÁ NO SITE tinypng.com PARA OTIMIZAR A SUA IMAGEM
### TAGS DE LISTA
    ul: indica uma lista não ordenada
    ol: indica uma lista ordenada
    li: indica um elemento de uma lista, seja ela ordenada ou não

# INTRODUÇÃO AO CSS3
## CSS3
    .OBJETIVO: CRIADO COM O INTUITO DE DAR "VIDA" AS PÁGINAS WEB
    .O QUE SÃO SELETORES (TAG X ID X CLASSE)
    .USO BÁSICO
### BOX MODEL
    MARGIN: ESPAÇO EXTERNO DO ELEMENTO
    PADDING: ESPAÇAMENTO INTERNO
    BORDER: ELE CIRCUNDA ENTRE O ESPAÇAMENTO INTERNO E O EXTERNO
    CONTENT: CONTEÚDO DA SUA CAIXA

### ESTILIZANDO ELEMENTOS
#### PADDING
- PADDING: VALOR(ADICIONA ESPAÇAMENTO EM TODOS OS LADOS)
- PADDING: VALOR1 (EIXO Y) VALOR2(EIXO X)
- PADDING: EPAÇAMENTO SUPERIOR, DIREITO, ESPAÇAMENTO INFERIOR, ESQUERDO
- TAMBÉM PODEMOS USAR VALORES ESPECIFCOS DO PADDING COMO, PADDING-TOP, BOTTOM, RIGHT E LEFT
#### BACKGROUND
**SERVE PARA MODIFICAR O FUNDO DE UM ELEMENTO(COR, TAMANHO E ETC...), MAS AQUI SÓ VEREMOS A COR**
 - BACKGROUND-COLOR: COR(PRÉ DEFINIDA"WHITE, RED, BLUE...", HEXADECIMAL, HSL, HSLA)
 #### BORDER
 - BORDER: LARGURA(EM PX, REM, EM...),ESTILO DA BORDA(SOLID, DOTTED...) E COR(PRÉ DEFINIDA"WHITE, RED, BLUE...", HEXADECIMAL, HSL, HSLA)
 - PROPRIEDADES ESPECIFICAS: BORDER-TOP,LEFT,BOTTOM OU RIGHT, BORDER-STYLE, BORDER-COLOR, BORDER-WIDTH...
 - PROPRIEDADES MUITO ESPECIFICAR: EX = BORDER-TOP-WIDTH, BORDER-RIGHT-BOTTOM...
 - BORDER-RADIUS: ARREDONDA AS BORDAS, 1 VALOR ARREDONTA TUDO POR IGUAL, 2 ARREDONDA O EIXO X EO Y, 4 ARREDONDA O CANTO
    SUPERIOR DIREITO, SUPERIOR ESQUERDO, INFERIOR ESQUERDO, INFERIOR DIREITO
#### ESTILIZANDO TEXTO
- FONT-FAMILY: ALTERA A FONTE DO NOSSO TEXTO SEJA ELA PRÉ DEFINIDA NO EDITOR(ARIAL,VERDANA,GERGIA)
    TAMBÉM PODEMOS PEGAR FONTES DA INTERNET(SITE PARA PEGAR FONTES: GOOGLE FONTS)
- FONT-SIZE: ALTERA O TAMANHO DAS LETRAS DO NOSSO TEXTO. UNIDADES DE MEDIDAS: PX(MAIS USADA), EM, REM...
- FONT-STYLE: ESTILO DO NOSSO TEXTO, ELE PODE SER NORMAL OU ITALIC
- FONT-WEIGHT: DEFINE O PESO(GROSSURA) DO NOSSO TEXTO, PODE SER DEFINIDO COMO NORMAL,LIGHT OU BOLD,
     ALÉM DE ACEITAR VALORES DE 100,200,300 ATÉ O 900
#### TEXT-TRANSFORM
- DEFININE SE O TEXTO VAI ESTAR EM CAIXA ALTA(UPPERCASE) CAIXA BAIXA(LOWERCASE) OU COM APENAS A PRIMEIRA LETRA
    DE CADA PALAVRA EM CAIXA ALTA(CAPTALIZE)
#### TEXT-DECORATION
- USADO PARA COLOCAR LINHAS, VALORES: UNDERLINE, OVERLINE, LINE-THOUGHTH...
### ESTILIZANDO LISTAS
#### LIST-STYLE-TYPE
- ULTILIZADO PARA DEFINIR O TIPO DA LISTA, ALGUNS VALORES PRÉ DEFINIDOS: DECIMAL, CIRCLE, DISC, NONE...
    OU TAMÉM PODEMOS ALTERAR OS MARCADORES COM EMOJIS E IMAGENS
- COMO O CSS É UM ESTILIZADOR DE CASCATA, PODEMOS USAR SELETORES EM TAGS QUE ESTÃO DENTRO UMAS DAS OUTRAS
    COMO: ul li a{}
### DIMENSÃO E ALINHAMENTO
- WIDTH e HEIGHT: SERVEM, RESPECTIVAMENTO, PARA DEFINIR A LARGURA E A ALTURA DE UM ELEMENTO(QUALQUER UNIDADE DE MEDIDAD SERVE)
- MAX-WIDTH e MAX-HEIGHT: SE ULTILIZA QUANDO SE QUER DEFINIR UMA LARGURA E ALTURA MAXÍMA PARA UM ELEMENTO
- MARGIN: SERVE PARA COLOCAR ESPAÇAMENTO ENTRE ELEMENTOS
- TEXT-ALIGN: SERVE PARA ALINHAR TEXTOS COMO CENTRO(CENTER), LEFT, RIGHT