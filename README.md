# CSS3, Please!

```css
.box_round {
  border-radius: 12px; /* Android 2.1+, Chrome, Firefox 4+, IE 9+, iOS 4+, Opera 10.50+, Safari 5+ */

  /* useful if you don't want a bg color from leaking outside the border: */
  background-clip: padding-box; /* Android 2.2+, Chrome, Firefox 4+, IE 9+, iOS 4+, Opera 10.50+, Safari 4+ */
}

.box_shadow {
  -webkit-box-shadow: 0px 0px 4px 0px #ffffff; /* Android 2.3+, iOS 4.0.2-4.2, Safari 3-4 */
          box-shadow: 0px 0px 4px 0px #ffffff; /* Chrome 6+, Firefox 4+, IE 9+, iOS 5+, Opera 10.50+ */
}

.box_gradient {
  background-color: #444444;
  background-image: -webkit-linear-gradient(top, #444444, #999999); /* Chrome 10-25, iOS 5+, Safari 5.1+ */
  background-image:         linear-gradient(to bottom, #444444, #999999); /* Chrome 26, Firefox 16+, IE 10+, Opera */
}

.box_rgba {
  background-color: transparent;
  background-color: rgba(180, 180, 144, 0.6);  /* Chrome, Firefox 3+, IE 9+, Opera 10.10+, Safari 3+ */
}

.box_rotate {
  -webkit-transform: rotate(7.5deg);  /* Chrome, Opera 15+, Safari 3.1+ */
      -ms-transform: rotate(7.5deg);  /* IE 9 */
          transform: rotate(7.5deg);  /* Firefox 16+, IE 10+, Opera */
}

.box_scale {
  -webkit-transform: scale(0.8);  /* Chrome, Opera 15+, Safari 3.1+ */
      -ms-transform: scale(0.8);  /* IE 9 */
          transform: scale(0.8);  /* Firefox 16+, IE 10+, Opera */
}

.box_3dtransforms {
  -webkit-perspective: 300px;  /* Chrome 12+, Safari 4+ */
      -ms-perspective: 300px;  /* IE 10 */
          perspective: 300px;
  -webkit-transform: rotateY(180deg);  -webkit-transform-style: preserve-3d;
      -ms-transform: rotateY(180deg);      -ms-transform-style: preserve-3d;
          transform: rotateY(180deg);          transform-style: preserve-3d;
}

.box_transition {
  -webkit-transition: all 0.3s ease-out;  /* Android 2.1+, Chrome 1-25, iOS 3.2-6.1, Safari 3.2-6  */
          transition: all 0.3s ease-out;  /* Chrome 26, Firefox 16+, iOS 7+, IE 10+, Opera, Safari 6.1+  */
}

.box_textshadow {
  text-shadow: 1px 1px 3px #888; /* Chrome, Firefox 3.5+, IE 10+, Opera 9+, Safari 1+ */
}

.box_opacity {
  opacity: 0.9; /* Android 2.1+, Chrome 4+, Firefox 2+, IE 9+, iOS 3.2+, Opera 9+, Safari 3.1+ */
}

* {
  -webkit-box-sizing: border-box; /* Android ≤ 2.3, iOS ≤ 4 */
     -moz-box-sizing: border-box; /* Firefox ≤ 28 */
          box-sizing: border-box; /* Chrome, Firefox 29+, IE 8+, Opera, Safari 5.1 */
}

.box_bgsize {
  -webkit-background-size: 100% 100%; /* Safari 3-4 */
          background-size: 100% 100%; /* Chrome, Firefox 4+, IE 9+, Opera, Safari 5+ */
}

.box_columns {
  -webkit-column-count: 2;  -webkit-column-gap: 15px; /* Chrome, Safari 3 */
     -moz-column-count: 2;     -moz-column-gap: 15px; /* Firefox 3.5+ */
          column-count: 2;          column-gap: 15px; /* Opera 11+ */
}

.box_animation:hover {
  -webkit-animation: myanim 5s infinite; /* Chrome, Opera 15+, Safari 5+ */
          animation: myanim 5s infinite; /* Chrome, Firefox 16+, IE 10+, Opera */
}

@-webkit-keyframes myanim {
  0%   { opacity: 0.0; }
  50%  { opacity: 0.5; }
  100% { opacity: 1.0; }
}
@keyframes myanim {
  0%   { opacity: 0.0; }
  50%  { opacity: 0.5; }
  100% { opacity: 1.0; }
}

@font-face {
  font-family: 'WebFont';
  src: url('myfont.woff') format('woff'), /* Chrome 6+, Firefox 3.6+, IE 9+, Safari 5.1+ */
       url('myfont.ttf') format('truetype'); /* Chrome 4+, Firefox 3.5, Opera 10+, Safari 3—5 */
}

.box_tabsize {
  -moz-tab-size: 2; /* Firefox 4+ */
       tab-size: 2;
}
```
