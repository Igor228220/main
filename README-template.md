* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body, html {
    width: 100%;
    height: 100%
}
body {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    background-color: #f2e9e3;
    font-family: 'Montserrat', sans-serif;
    color: hsl(228, 12%, 48%);
}
.desktop {
    display: none;
}
.panel {
    width: 90%;
    max-width: 1440px;
    background-color: white;
    margin: auto;
    border-radius: 15px;
}

.panel img {
    width: 100%;
    border-radius: 15px 15px 0 0;
}

.content-container {
    /* border: 1px solid black; */
    width: 100%;
    padding: 1em;
}

.text-content {
    /* border: 1px solid red; */
}

.product-title, .product-price {
    font-family: 'Fraunces';
}

.flow > * + * {
    margin-bottom: var(--flow-space, 1em) ;
}

p {
    font-size: .8rem;
    line-height: 1.8;
}
.product-type {
    font-size: clamp(.7rem, .9rem, 1rem);
    text-transform: uppercase;
    letter-spacing: .5em;
    margin-bottom: 1em;
}

.product-title {
    font-size: clamp(1.9rem, 2rem, 2.3rem);
    font-family: 'Fraunces';
    color: hsl(212, 21%, 14%);
}
.product-description {
    font-size: 1rem;
    line-height: 1.5rem;
}
.price-ctr {
    display: flex;
    align-items: center;
    padding-top: 1em;
}
.product-price {
    font-size: 1.9rem;
    color: hsl(158, 36%, 37%);
}
.product-sale-price {
    padding-left: 1em;
    text-decoration: line-through;
}
.btn {
    display: inline-block;
    text-align: center;
    text-decoration: none;
    text-transform: capitalize;
    width: 100%;
    padding: 1em 0;
    border-radius: 5px;
    background: hsl(158, 36%, 37%);
    color: white;
    font-weight: 600;
}



@media(min-width: 40em) {

    .mobile {
        display: none;
    }
    .desktop {
        display: flex;
    }
    .panel {
        display: flex;
        max-width: 50%;
    }
    .panel > img {
        width: 50%;
        border-radius: 15px 0 0 15px;
    }
    .content-container {
        width: 50%;
        padding: 2.5em;
    }
    .text-content {
        width: 92%;
    }
    .price-ctr {
        padding-bottom: 1em;
    }
    
}
