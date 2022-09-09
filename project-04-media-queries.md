# Media Queries

## @media screen and () {


}

### Media Types
- all
- screen
- print
- speech


### properties
- width
- min-width
- webkit-device-pixel-ratio
- webkit-max-device-pixel-ratio
- orientation

### logical operaitons
- (1) and
- (2) ,
- (3) not
    - 
    ```
    @media not screen and (min-width: 500px) {
        body {
            background-color: red;
        }
    }
    ```
- (4) only 

<br>

### Media quries breakpoint - based on bootstrap
- extra small   < 576px         
- small         576px - 768px       sm
- medium        768px - 992px       md
- large         992px - 1200px      lg
- x-large       1200px - 1400px     xlg
- xx-large      > 1400px           xxlg


## PC端优先 
- use `max-width` from 1200px to < 576px;

## 移动端优先
- use `min-width` from < 576px to 1200px;

