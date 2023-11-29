# projeto3
.banner {
    background: var(--azul-degrade);
    color: var(--branco);
    text-align: center;
    padding: 2.5em 2em;
}

.banner__titulo {
    font-size: 18px;
    font-weight: 700;
}

.banner__texto {
    font-weight: 500;
    margin: 1em 0;
}

.banner__pesquisa {
    background-color: transparent;
    border: 1px solid var(--branco);
    color: var(--branco);
    border-radius: 24px;
    padding: 1em;
    width: 100%;
}

.banner__pesquisa::placeholder {
    font-family: var(--fonte-principal);
    font-size: 14px;
    font-weight: 400;
    text-align: center;
    color: var(--branco);
    background: url("../img/Lupa.svg") no-repeat;
    background-position: 1em;
}

@media screen and (min-width: 1024px) {
    .banner__titulo {
        font-size: 36px;
    }

    .banner__pesquisa {
        width: 50%;
    }

    .banner__pesquisa::placeholder {
        background-position: 7em;
    }
}

@media screen and (min-width: 1728px) {
    .banner__pesquisa {
        width: 35%;
    }

    .banner__pesquisa::placeholder {
        background-position: 12em;
    }

    .banner {
        padding: 6em 0;
    }
}

.carrossel__titulo {
    color: var(--laranja);
    background-color: var(--branco);
    text-align: center;
    text-transform: uppercase;
    font-size: 18px;
    font-weight: 700;
    padding: 1em 0 0.5em 0;
}

.swiper-slide img {
    width: 100%;
}

.swiper-button-prev,
.swiper-button-next {
    display: none;
}

.swiper-pagination {
    position: initial;
    margin: .5em 0;
}

.card__descrição {
    display: flex;
    justify-content: space-between;
    margin-bottom: 0.5em;
}

.card__botões {
    display: flex;
    justify-content: space-between;
}

.botões {
    display: flex;
}

.card {
    background: var(--branco);
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    border-radius: 10px;
    margin: 1em;
    padding: 1em;
}

.descrição__titulo {
    color: var(--laranja);
    font-weight: 700;
}

.descrição__titulo-livro {
    color: var(--azul);
    font-size: 18px;
    font-weight: 700;
    margin: 0.5em 0;
}

.descrição__texto {
    font-size: 14px;
}

.botões__item {
    margin: 0 0.5em;
}

.botões__ancora {
    background-color: var(--laranja);
    padding: 1em 2.2em;
    color: var(--branco);
    font-weight: 700;
    text-decoration: none;
}

@media screen and (min-width: 1024px) {
    .carrossel__titulo {
        font-size: 26px;
    }

    .swiper-pagination {
        margin: 2em 0 3em 0;
    }

    .swiper {
        width: 60%;
    }

    .swiper-button-prev,
    .swiper-button-next {
        display: block;
        top: 60%;
    }

    .card {
        width: 40%;
        margin: 2em auto;
    }
}

@media screen and (min-width: 1728px) {
    .carrossel__container {
        display: flex;
        margin: 0 20vw 3em 20vw;
        align-items: center;
    }

    .swiper-pagination {
        margin: 1em 0;
    }

    .swiper {
        width: 50%;
    }

    .descrição__titulo {
        font-size: 32px;
    }

    .descrição__texto {
        font-size: 16px;
    }

    .descrição {
        margin-right: 2em;
    }

    .card {
        width: 60%;
        margin-left: 3em;
    }

}

.carrossel__titulo {
    color: var(--laranja);
    background-color: var(--branco);
    text-align: center;
    text-transform: uppercase;
    font-size: 18px;
    font-weight: 700;
    padding: 1em 0 0.5em 0;
}

.swiper-slide img {
    width: 100%;
}

.swiper-button-prev,
.swiper-button-next {
    display: none;
}

.swiper-pagination {
    position: initial;
    margin: .5em 0;
}

.card__descrição {
    display: flex;
    justify-content: space-between;
    margin-bottom: 0.5em;
}

.card__botões {
    display: flex;
    justify-content: space-between;
}

.botões {
    display: flex;
}

.card {
    background: var(--branco);
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    border-radius: 10px;
    margin: 1em;
    padding: 1em;
}

.descrição__titulo {
    color: var(--laranja);
    font-weight: 700;
}

.descrição__titulo-livro {
    color: var(--azul);
    font-size: 18px;
    font-weight: 700;
    margin: 0.5em 0;
}

.descrição__texto {
    font-size: 14px;
}

.botões__item {
    margin: 0 0.5em;
}

.botões__ancora {
    background-color: var(--laranja);
    padding: 1em 2.2em;
    color: var(--branco);
    font-weight: 700;
    text-decoration: none;
}

@media screen and (min-width: 1024px) {
    .carrossel__titulo {
        font-size: 26px;
    }

    .swiper-pagination {
        margin: 2em 0 3em 0;
    }

    .swiper {
        width: 60%;
    }

    .swiper-button-prev,
    .swiper-button-next {
        display: block;
        top: 60%;
    }

    .card {
        width: 40%;
        margin: 2em auto;
    }
}

@media screen and (min-width: 1728px) {
    .carrossel__container {
        display: flex;
        margin: 0 20vw 3em 20vw;
        align-items: center;
    }

    .swiper-pagination {
        margin: 1em 0;
    }

    .swiper {
        width: 50%;
    }

    .descrição__titulo {
        font-size: 32px;
    }

    .descrição__texto {
        font-size: 16px;
    }

    .descrição {
        margin-right: 2em;
    }

    .card {
        width: 60%;
        margin-left: 3em;
    }

}

.cabeçalho__menu-hamburguer {
    width: 24px;
    height: 24px;
    background-image: url("../img/Menu.svg");
    background-repeat: no-repeat;
    background-position: center;
    display: inline-block;
}

.container__botao:checked~.container__rotulo>.cabeçalho__menu-hamburguer {
    background-image: url("../img/Menu Aberto.svg");
}

.container__botao:checked~.container__rotulo {
    background: var(--azul-degrade);
}

.cabeçalho {
    background-color: var(--branco);
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: relative;
}

.container {
    display: flex;
    align-items: center;
}

.container__imagem {
    padding: 1em;
}

.lista-menu {
    display: none;
    position: absolute;
    top: 100%;
    width: 60vw;
}

.container__botao:checked~.lista-menu {
    display: block;
}

.lista-menu__titulo,
.lista-menu__item {
    padding: 1em;
    background-color: var(--branco);
}

.lista-menu__titulo {
    color: var(--laranja);
    font-weight: 700;
}

.lista-menu__link {
    background: var(--azul-degrade);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    text-transform: uppercase;
}

.container__botao {
    display: none;
}

.container__titulo {
    display: none;
}

.opções {
    display: none;
}

.container__texto {
    display: none;
}

@media screen and (min-width: 1024px) {

    .container__titulo,
    .container__titulo--negrito {
        font-family: var(--fonte-secundario);
        font-size: 30px;
    }

    .container__titulo {
        font-weight: 400;
        display: block;
    }

    .container__titulo--negrito {
        font-weight: 700;
    }

    .opções {
        display: flex;
    }

    .opções__item {
        padding: 0 1em;
        text-transform: uppercase;
    }

    .opções__link {
        text-decoration: none;
        color: var(--preto);
    }

    .container__imagem-transparente {
        display: none;
    }

    .cabeçalho__menu-hamburguer {
        display: none;
    }

    .opções__botão:checked~.lista-menu {
        display: block;
        width: auto;
    }

    .opções__botão {
        display: none;
    }

    .opções__botão:checked~.opções__rotulo>.opções__item {
        background: var(--azul-degrade);
        color: var(--branco);
    }

    .opções__item {
        padding: 2em 1em;
    }

    .lista-menu__item:hover {
        background: var(--azul-degrade);
    }

    .lista-menu__item:hover>.lista-menu__link {
        -webkit-text-fill-color: var(--branco);
        text-decoration: none;
    }

}

@media screen and (min-width: 1728px) {
    .container__link {
        display: flex;
        align-items: center;
        text-decoration: none;
        color: var(--preto);
    }

    .cabeçalho {
        padding: 0 2em;
    }

    .opções {
        margin-right: auto;
    }

    .container__texto {
        display: block;
    }
}

hr {
    margin: 0;
}

.rodapé {
    background-color: var(--branco);
    padding: 1em;
}

.lista-rodapé {
    display: none;
}

@media screen and (min-width: 1024px) {
    .rodapé {
        display: flex;
        justify-content: space-around;
    }

    .lista-rodapé {
        display: block;
    }

    .lista-rodapé__item {
        display: flex;
        align-items: center;
        margin: 0.6em 0;
    }

    .lista-rodapé__link {
        color: var(--cinza);
        text-decoration: none;
        margin-left: 0.6em;
    }

    .lista-rodapé__titulo {
        font-size: 14px;
        color: var(--cinza-claro);
    }

    .rodapé__titulo {
        font-size: 24px;
    }
}

@media screen and (min-width: 1728px) {
    .lista-rodapé {
        border-left: 1px solid var(--cinza-claro);
        padding-left: 1em;
    }

    .rodapé {
        padding: 3em 0;
    }
}

.tópicos {
    background: var(--azul-degrade);
    text-align: center;
    padding: 1em 0;
}

.tópicos__titulo {
    color: var(--branco);
    font-weight: 300;
    margin-bottom: 1em;
}

.tópicos__lista {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.tópicos__item {
    margin: 2em 0.5em;
}

.tópicos__link {
    color: var(--branco);
    padding: 1em;
    background-color: var(--laranja);
    text-decoration: none;
    font-size: 14px;
    font-weight: 700;
}

@media screen and (min-width: 1024px) {
    .tópicos__titulo {
        font-size: 24px;
    }

    .tópicos__link {
        font-size: 24px;
    }
}

@media screen and (min-width: 1728px) {
    .tópicos {
        padding: 3em 30vw;
    }
}