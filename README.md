# Playing-with-CSS
## It is a very simple html & css files 
### just for the purpose of making css learning fun and easy and will keep updating this repo for more css drawings
### I wanted to practice the following conent for CSS :-
* using absolute and relative positions 
* using transform 
* making circles with css
* making shadows for boxes
* using sudo selectors for classes
#### here used to make the mouse of the drawing 
```css

.face::after{
    content: "";
    position: absolute;
    height: 14px;
    width: 14px;
    background: #fce2c4;
    border-left: 6px solid #ffa945;
    border-bottom: 4px solid #ffa945;
    border-bottom-left-radius: 10px;
    transform: skew(-40deg);
    top:170px;
    left: -12px;
}
```
* using direct child selectors
#### here used for making the hair of the drawing 
```css

.hair>div:nth-child(1){
    position: absolute;
    height: 30px;
    width: 100px;
    border-top: 20px solid green;
    left: 180px;
    bottom: 40px;
    border-radius: 50px 40px 0 0;
    transform: rotate(30deg);
}

```
## final outcome
![alt text](https://github.com/abdelrahmanbaher4/Playing-with-CSS/blob/main/css_drawing.PNG)




