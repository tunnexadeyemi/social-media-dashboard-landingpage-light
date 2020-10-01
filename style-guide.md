# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Lime Green: hsl(163, 72%, 41%) fb-today
- Bright Red: hsl(356, 69%, 56%)

- Facebook: hsl(208, 92%, 53%)
- Twitter: hsl(203, 89%, 53%)
- Instagram: linear gradient hsl(37, 97%, 70%) to hsl(329, 70%, 58%)
- YouTube: hsl(348, 97%, 39%)

#### Dark Theme

- Toggle: linear gradient hsl(210, 78%, 56%) to hsl(146, 68%, 55%)

#### Light Theme

- Toggle: hsl(230, 22%, 74%) for darkmode text

### Neutral

#### Dark Theme

- Very Dark Blue (BG): hsl(230, 17%, 14%) 
- Very Dark Blue (Top BG Pattern): hsl(232, 19%, 15%)
- Dark Desaturated Blue (Card BG): hsl(228, 28%, 20%)
- Desaturated Blue (Text): hsl(228, 34%, 66%)
- White (Text): hsl(0, 0%, 100%)

#### Light Theme

- White (BG): hsl(0, 0%, 100%)----background
- Very Pale Blue (Top BG Pattern): hsl(225, 100%, 98%)--inner button
- Light Grayish Blue (Card BG): hsl(227, 47%, 96%)---fb-dashboard
- Dark Grayish Blue (Text): hsl(228, 12%, 44%)-----darkmode text
- Very Dark Blue (Text): hsl(230, 17%, 14%)---social media, 1987

## Typography

### Body Copy

- Font size (Overview Card Headings): 14px

### Font

- Family: [Inter](https://fonts.google.com/specimen/Inter)
- Weights: 400, 700


















.dashboard {
  margin-top: 5em;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  width: 100%;
}


#fb-screen{
  
  margin-top: 16px;
}
/* .fb-board {
  background-color: hsl(225, 100%, 98%);
  padding: 112px;
  border-radius: 0.5rem;
  height: 0rem; */
  
  


.border-top {
  margin-top: -6.95em;
  margin-left: -6.96em;
  background-color: hsl(208, 92%, 53%);
  padding: 0.199rem 6.97rem;
  border-radius: 0.5rem 0.5rem 0rem 0rem;
  width: 100%;
}

.fb-img {
  display: flex;
  justify-content: center;
  margin-top: 1.5em;
}

.fb-handle {
  margin-left: 0.7em;
  font-size: 11px;
  margin-top: 0.2rem;
  font-weight: 500;
}
.fb-year {
  text-align: center;
  font-size: 53px;
  font-weight: 800;
  font-family: lato;
  margin-top: 1.6rem;}

  .fb-follower {
    text-align: center;
    font-weight: 750;
    font-family: lato;
    text-transform: uppercase;
    letter-spacing: 3px;
    margin-top: 6px;
    font-size: 15px;
    color: hsl(230, 22%, 74%);
}

.fb-today {
  text-align: center;
  margin-top: 1.5em;
  font-size: 13px;
  font-weight: 900;
  font-family: lato;
  color: hsl(163, 72%, 41%);
  margin-right: 35px;
}

.today-icon-up {
  margin-top: 17px;
  margin-left: -12px;
  margin-right: -56px;
}
.icon-up {
  margin-bottom: -32.962px;
  margin-left: 0.8em;
  margin-top: 1px;
}

.twitter-board {
  margin-top: 1em;
 background-color: hsl(225, 100%, 98%);
    padding: 112px;
    border-radius: 0.5rem;
    height: 0rem;
}


.instagram-board {
margin-top: 1em;
}

.youtube-board {
margin-top: 1em;
}


#insta-top{ background-image: linear-gradient(to right, hsl(37, 97%, 70%),hsl(329, 70%, 58%));

}

#twitter-top{
background-color:hsl(203, 89%, 53%);
}
#youtube-top{
background-color:hsl(348, 97%, 39%);
}




#youtube-text{
color: hsl(356, 69%, 56%);
}


.overview-text {
  margin-top: 1.5em;
  margin-bottom: 1em;
  font-size: 28px;
  font-weight: 900;
  font-family: lato;
  color: hsl(228, 12%, 44%);
}



.views-flex {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.drop-down {
  margin-top: 0.5em;
  margin-left: 0.5rem;
}

.views-flexy {
  display: flex;
  flex-direction: row;
  margin-top: 2em;
}
.fb-views {
  height: 224px;
  width: 322.96px;
    background-color: hsl(225, 100%, 98%);
    border-radius: 1em
}


.views-text-fb-img {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  margin-top: -7px;
  padding: 2.5em 2.2em;
  font-size: 19px;
}


.views-text {
  font-weight: 900;
  font-family: lato;
  color: hsl(228, 12%, 44%);
}

.number-today-arrow-up-number-icon {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 1em 2.2em;
}

.views-flexy {
  display: flex;
  flex-direction: row;
  margin-top: 2em;
  justify-content: space-between;
}

#shift {
  margin-left: 2.21em;
}

.number-today {
  margin-top: 15px;
  font-size: 35px;
  font-weight: 800;
  font-family: lato;
}

.arrow-up{
  margin-left: -12px;
  margin-top: 30px;
  margin-bottom: -15px;
}

element.style {
  font-size: 17px;
  font-weight: 900;
}


.number-icon{
  font-weight: 900;
  font-family: lato;
  color:hsl(163, 72%, 41%);
}



#red{
color: hsl(356, 69%, 56%);
}


.dashboard {
    margin-top: 5em;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    width: 100%;
}


  .fb-board {
    background-color: hsl(225, 100%, 98%);
    padding: 5em;
    border-radius: 0.5rem;
    height: 0rem;
  }

  .border-top {
    margin-top: -5em;

    margin-left: -5em;

    background-color: hsl(208, 92%, 53%);
    padding: 0.199rem 5rem;
    border-radius: 0.5rem 0.5rem 0rem 0rem;
    width: 100%;
  }

  .fb-img {
    display: flex;
    justify-content: center;
    margin-top: 1.5em;
  }

  .fb-handle {
    margin-left: 0.7em;
    font-size: 11px;
    margin-top: 0.2rem;
    font-weight: 500;
  }
  .fb-year {
    text-align: center;
    font-size: 35px;
    font-weight: 800;
    font-family: lato;
    margin-top: 0.6rem;
  }

  .fb-follower {
    text-align: center;
    font-weight: 750;
    font-family: lato;
    text-transform: uppercase;
    letter-spacing: 3px;
    margin-top: 6px;
    font-size: 9px;
    color: hsl(230, 22%, 74%);
  }
  .fb-today {
    text-align: center;
    margin-top: 1.5em;
    font-size: 8px;
    font-weight: 700;
    font-family: lato;
    color: hsl(163, 72%, 41%);
  }

  .icon-up {
    margin-bottom: -22.962px;
    margin-left: 3.8em;
  }

  .today-icon-up {
    margin-top: 0.5em;
  }

  .twitter-board {
    margin-top: 1em;
    width: 100%;
}

.instagram-board {
  margin-top: 1em;
  width: 100%;
}

.youtube-board {
  margin-top: 1em;
  width: 100%;
}


#insta-top{ background-image: linear-gradient(to right, hsl(37, 97%, 70%),hsl(329, 70%, 58%));

}

#twitter-top{
  background-color:hsl(203, 89%, 53%);
}
#youtube-top{
  background-color:hsl(348, 97%, 39%);
}




#youtube-text{
  color: hsl(356, 69%, 56%);
}


.overview-text {
    margin-top: 1.5em;
    margin-bottom: 1em;
    font-size: 28px;
    font-weight: 900;
    font-family: lato;
    color: hsl(228, 12%, 44%);
}

.fb-views {
    padding: 1.9em;
    background-color: hsl(225, 100%, 98%);
}
.views-text-fb-img {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin-top: -7px;
}

.views-text {
    font-weight: 900;
    font-family: lato;
    color: hsl(228, 12%, 44%);
}

.number-today-arrow-up-number-icon{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}

.number-today {
    margin-top: 15px;
    font-size: 35px;
    font-weight: 800;
    font-family: lato;
}

.arrow-up{
    margin-left: -12px;
    margin-top: 30px;
    margin-bottom: -15px;
}

element.style {
    font-size: 17px;
    font-weight: 900;
}


.number-icon{
    font-weight: 900;
    font-family: lato;
    color:hsl(163, 72%, 41%);
}

.drop-down{
  margin-top: 1.2em;
}

#red{
 color: hsl(356, 69%, 56%);
}


.views-flex {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
.views-flexy {
  display: flex;
  flex-direction: column;
  margin-top: 2em;
  justify-content: space-between;
}

#shift {
    margin-left: 0.21em;
}