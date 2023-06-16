# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

Very Dark Magenta: hsl(300, 43%, 22%)
Soft Pink: hsl(333, 80%, 67%)

### Neutral

Dark Grayish Magenta: hsl(303, 10%, 53%)
Light Grayish Magenta: hsl(300, 24%, 96%)
White: hsl(0, 0%, 100%)

## Typography

### Body Copy

- Font size: 15px

### Font

- Family: [League Spartan](https://fonts.google.com/specimen/League+Spartan)
- Weights: 400, 500, 700

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=League+Spartan:wght@400;500;700&display=swap" rel="stylesheet">

font-family: 'League Spartan', sans-serif;

body {
    /* background-color: var(--clr-primary-400); */
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 100vh;
    min-height: 80em;
    width: 100%;
  }
  .wrapper {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    width: 100%;
  }
  header {
    text-align: left;
    width: 50%;
  }
  header article p {
    color: var(--clr-secondary-200);
    font-weight: var(--fw-regular);
    font-size: 1rem;
    line-height: 1.5;
    padding-bottom: 2rem;
  }
  .top-container {
    display: flex;
    flex-direction: row;
    min-width: 50em;
    justify-content: space-evenly;
  }
  .buyer {
    /* background-color: var(--clr-primary-400); */
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: row;
    min-width: 50em;
    /* width: 100%; */
  }
  .rating {
    width: 50%;
  }
  /* .rating__Reviews {
    display: flex;
    flex-direction: flex-start;
    width: 80%;
    min-width: 25.375rem;
    margin-left: 6rem;
  }
  .rating__Report_Guru {
    display: flex;
    flex-direction: flex-start;
    width: 80%;
    min-width: 26.375rem;
    margin-left: 8rem;
  }
  .rating__BestTech {
    display: flex;
    flex-direction: flex-start;
    width: 80%;
    min-width: 27.375rem;
    margin-left: 10rem;
  } */
  /* .bottom-container .buyer {
    display: flex;
    flex-direction: row;
  }
  .buyer__CSmith {
    min-width: 21.6rem;
    margin-right: 1rem;
  }
  .buyer__IRoberts {
    min-width: 21.6rem;
    margin-right: 1rem;
  }
  .buyer__AWallace {
    min-width: 21.6rem;
    margin-right: 1rem;
  } */