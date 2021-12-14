* {
    padding: 0%;
    margin: 0%;
    box-sizing: border-box;
}

:root {

    /* COLORS */
    /* Primary */
    --soft-blue: hsl(215, 51%, 70%);
    --cyan: hsl(178, 100%, 50%);

    /* Neutural */
    --main-BG: hsl(217, 54%, 11%);
    --card-BG: hsl(216, 50%, 16%);
    --line: hsl(215, 32%, 27%);
    --white: hsl(0, 0%, 100%)

    /* TYPOGRAPHY */
}

body {
    font-family: 'Outfit', sans-serif;
    background-color: var(--main-BG);
    color: var(--white);
    font-size: 18px;
}

.card {
    margin: 0 auto;
    margin-top: 25%;
    width: 80%;
    padding: 1.2rem;
    display: flex;
    flex-direction: column;
    background-color: var(--card-BG);
    border-radius: 1rem;
}

.card__img img {
    width: 100%;
    border-radius: 0.5rem;
}

.card__info {
    display: flex;
    justify-content: space-between;
}
 