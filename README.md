# CerrandoPesta-as
/* -----------MEDIA 600----------- */
@media (max-width: 790px) {
    body{
        scroll-snap-type: y mandatory;
        overflow-y: scroll;
    }
    header{
        border: 0ch;
        height: 100vh;
        width: 100vw;
        margin: 0%;
        padding-top: 0ch;
    }
    header h1{
        font-size: 4em;
    }
    header p{
        font-size: 1.5em !important;
        padding-bottom: 0%;
        text-align: justify;
    }
    #chevron {
        margin: auto;
        position: relative;
        text-align: center;
        padding: 1px;
        margin-bottom: 1,5px;
        height: 2px;
        width: 14em;
    }
    #chevron:before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        height: 100%;
        width: 50%;
        background: white;
        transform: skew(0deg, 9deg);
    }
    #chevron:after {
        content: '';
        position: absolute;
        top: 0;
        right: 0;
        height: 100%;
        width: 50%;
        background: white;
        transform: skew(0deg, -9deg);
    }
    .fecha{
        box-shadow: none;
        border: 0px;
        max-height: 3em;
        position: inherit;
    }
    .fecha h1{
        font-size: 2em !important;
        text-align: center;
        margin: 0%;
    }
    .noticias{
        text-align:left;
        border: 0ch;
        padding: 0em 0em;
        height: 100vh;
        width: 100vw;
        display: block;
    }
    .noticiaGrande{
        position: relative;
        padding: .5em .5em;
        margin-left: .1em;
        height: 30%;
        display: flex;
        flex-direction: column;
    }
    .noticiaGrande h2{
        word-wrap: break-word;
        overflow: hidden;
        min-height: 1em;
        margin: 0% !important;
        word-break: keep-all;
        font-weight: 100;
        font-size: 1.2em;
    }
    .noticiaGrande p{
        word-break: keep-all;
        overflow: hidden;
        min-height: 5em;
    }
    .noticiaChica{
        position: relative;
        padding: .5em .5em;
        margin: 0%;
        display: flex;
        justify-content: center;
        flex-direction: column;
        max-height: 25%;
    }
    .noticiaChica h2{
        word-break: keep-all;
        overflow: hidden;
        min-height: 1em;
        margin: 0%;
        font-weight: 100;
        font-size: 1.2em;
    }
    .linkNoticia{
        position: absolute;
        width: 90%;
        height: 1em;
        border-radius: 1%;
        font-size: 1.1em;
    }
    .border{
        display: none;
    }
}
/* -----------MEDIA 900----------- */
@media (max-width: 920px) {
    header{
        height: 100vh;
    }
    header h1{
        font-size: 5em;
    }
    header p{
        font-size: 1.8em;
        text-align: justify;
    }
    #chevron {
        margin: auto;
        position: relative;
        text-align: center;
        padding: 1px;
        margin-bottom: 1,5px;
        height: 2px;
        width: 14em;
    }
    #chevron:before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        height: 100%;
        width: 50%;
        background: white;
        transform: skew(0deg, 9deg);
    }
    #chevron:after {
        content: '';
        position: absolute;
        top: 0;
        right: 0;
        height: 100%;
        width: 50%;
        background: white;
        transform: skew(0deg, -9deg);
    }
    .fecha{
        width: 10em;
        height: 10em;
        left: 5em;
        top: 2em;
    }
    .fecha h1{
        font-size: 3em;
    }
    .noticiaGrande{
        margin-left: 0%;
    }
    .noticiaGrande h2{
        word-wrap: break-word;
        overflow: hidden;
        min-height: 1em;
        word-break: keep-all;
        font-weight: 100;
        font-size: 1.5em;
        margin: .5em .5em;
    }
    .noticiaGrande p{
        max-height: 9em;
        font-size: 1em;
    }
    .noticiaChica{
        margin: 0%;
    }
    .noticiaChica h2{
        word-break: keep-all;
        overflow: hidden;
        min-height: 1em;
        margin: 0%;
        font-weight: 100;
        font-size: 1.5em;
    }
    .noticiaChica p{
        word-break: keep-all;
        text-overflow: ellipsis;
        max-height: 9em;
        font-size: 1em;
    }
    #irAlTl{
        position: absolute;
        left: 35%;
        bottom: 5%;
        font-family: H1Exo;
        text-align: center;
    }
}
/* --------MEDIA 800---------- */
 @media (max-width: 800px) {
    header{
        height: 100vh;
    }
    header h1{
        font-size: 4em;
    }
    header p{
        font-size: 1.4em;
        text-align: justify;
    }
    #chevron {
        margin: auto;
        position: relative;
        text-align: center;
        padding: 1px;
        margin-bottom: 1,5px;
        height: 2px;
        width: 14em;
    }
    #chevron:before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        height: 100%;
        width: 50%;
        background: white;
        transform: skew(0deg, 9deg);
    }
    #chevron:after {
        content: '';
        position: absolute;
        top: 0;
        right: 0;
        height: 100%;
        width: 50%;
        background: white;
        transform: skew(0deg, -9deg);
    }
    .fecha{
        width: 8em;
        height: 8em;
        left: 8em;
    }
    .fecha h1{
        text-align: center;
        font-size: 1em;
    }
    .noticias{
        text-align:left;
        height: 100vh;
    }
    .noticiaGrande{
        margin-left: .1em;
        min-height: 33%;
        display: flex;
        flex-direction: column;
    }
    .noticiaGrande h2{
        word-wrap: break-word;
        overflow: hidden;
        min-height: 1em;
        word-break: keep-all;
        font-weight: 100;
        font-size: 1em;
        margin: .5em .5em;
    }
    .noticiaGrande p{
        word-break: keep-all;
        text-overflow: ellipsis;
        max-height: 9em;
        font-size: .9em;
    }
    .noticiaChica{
        margin-left: .1em;
        margin: 0%;
    }
    .noticiaChica h2{
        word-break: keep-all;
        overflow: hidden;
        min-height: 1em;
        margin: 0%;
        font-weight: 100;
        font-size: 1em;
    }
    .noticiaChica p{
        word-break: keep-all;
        text-overflow: ellipsis;
        max-height: 9em;
        font-size: .9em;
    }
    #irAlTl{
        margin-top: 3vh;
        font-family: H1Exo;
        font-weight: 200;
        display: block;
        text-align: center;
    }
} 
/* -----------MEDIA 1360----------- */
@media (min-width: 1360px){
    header{
        height: 100vh;
    }
    header h1{
        font-size: 7.5em;
        margin-bottom: 0%;
    }
    header p{
        font-size: 2em;
        padding-bottom: 0%;
        padding-top: 2vh;
        text-align: justify;
    }
    .fecha{
        width: 12em;
        height: 12em;
    } 
    .fecha h1{
        font-size: 4em;
    } 
    .noticias{
        row-gap: 1em;
        height: 100vh;
        padding-top: .5em;
        padding-bottom: .5em;
    }
    .noticiaGrande{
        height: 49vh;
        margin-left: .1em;
        display: flex;
        flex-direction: column;
    }
    .noticiaGrande h2{
        word-wrap: break-word;
        overflow: hidden;
        min-height: 1em;
        margin: 0%;
        word-break: keep-all;
        font-weight: 100;
    }
    .noticiaGrande p{
        word-break: keep-all;
        text-overflow: ellipsis;
        overflow:inherit;
        max-height: 13em;
    }
    .noticiaChica{
        height: 100%;
    }
    #irAlTl{
        margin-top: 0%;
        font-family: H1Exo;
        font-weight: 200;
        display: block;
        text-align: center;
    }
    .linkNoticia{
        position:absolute;
        bottom: 1.1em;
        right: 5%;
        border-radius: 5%;
        padding: 5px 10px;
        width: 100px;
        margin: .1em;
    }
}