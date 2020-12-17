# smartCycle.js
### Easy diagram cycle

![smartCycle with only color](https://mhvdeveloper.github.io/smartCyclic/sc.jpg)


[View Demo](https://mhvdeveloper.github.io/smartCyclic/)

### HOW TO USE:
```javascript
<script type="text/javascript" src="http://code.jquery.com/jquery-latest.min.js"></script>
```
and smartCycle
```javascript
<script type="text/javascript" src="smartCycle.min.js"></script>
```

in body
```javascript
<div class="anyone">
    <a class="sc_object">A</a>
    <a class="sc_object">B</a>
    <a class="sc_object">C</a>
    <a class="sc_object">D</a>
    <a class="sc_object">E</a>
    <a class="sc_object">F</a>
    <a class="sc_center">center</a>
</div>

<script>
  $(".anyone").smartCycle();
</script>
```

###OPTIONS:
```javascript
$(".anyone").smartCycle({
    container_width: '420px', //container width (.anyone), default: 420px
    container_height: '420px',//container height (.anyone), default: 420px
    radio: 160, //radio of the center of objects from the center, default: 160px
    angle_ini: 0, //starting angle in radians, default: 0
    direction: 'right', //arrow's direction, right or left, default: right
    diameter_object: 100, //diameter of objects in px, default: 100
    diameter_center: 100,//diameter of center object in px, default: 100
    font_size:'20px',//font size, default: 20px
    type_arrows: ['➡'], //type arrow, just paste the symbol one or more (array)
    arrows_size: '60px',//arrow size in px, default: 60px
    radio_arrows: 140,//radio of the arrows from the center, default: 140px
    arrows_colors:['#40A4C0'],//arrow's colors one or more (array)
    colors:['#40A4C0','#40A4C0'],//object's colors one or more (first is center) (array)
    union:['false','#F79646','10px']//circle union: visible, color and width, default: false #F79646 10px. same radio_arrows
});
```
###CALL
```javascript
$(".anyone").smartCycle('realign');
```


[View Demo](https://mhvdeveloper.github.io/smartCyclic/)
