# Tachyons Helpful Classes
##### Star this repo :star:
> Note: this is a personal preference on what I would use in Tachyons, which classes I feel like are most useful.

**If you think theres important classes that I missed or you have a question please feel free to raise an issue**



#### Margin and Padding:

- Base:
    - p = padding
    - m = margin
- Modifiers:
    - a = all
    - h = horizontal
    - v = vertical
    - t = top
    - r = right
    - b = bottom
    - l = left
  - Media Query Extensions:
    - ns = not-small
    - m  = medium
    - l  = large
- Sizes:
    - 0 = none
    - 1 = 1st step in spacing scale
    - 2 = 2nd step in spacing scale
    - 3 = 3rd step in spacing scale
    - 4 = 4th step in spacing scale
    - 5 = 5th step in spacing scale
    - 6 = 6th step in spacing scale
    - 7 = 7th step in spacing scale

      - .pa0 { padding: 0; }
      - .pl1 { padding-left: .25rem; }
      - .pr2 { padding-right: .5rem; }
      - .pb3 { padding-bottom: 1rem; }
      - .pt4 { padding-top: 2rem; }
      - .pv5 { padding-top: 4rem; padding-bottom: 4rem; }
      - .ph6 { padding-left: 8rem; padding-right: 8rem; }
      - .ma7 { margin: 16rem; }
      - .ml0 { margin-left: 0; }
      - .mr1 { margin-right: .25rem; }
      - .mb2 { margin-bottom: .5rem; }
      - .mt3 { margin-top: 1rem; }
      - .mv4 { margin-top: 2rem; margin-bottom: 2rem; }
      - .mh5 { margin-left: 4rem; margin-right: 4rem; }

#### Borders:
  - .br0 { border-radius: 0; }
  - .br1 { border-radius: .125rem; }
  - .br2 { border-radius: .25rem; }
  - .br3 { border-radius: .5rem; }
  - .br4 { border-radius: 1rem; }
  - .br-100 { border-radius: 100%; }
  - .shadow-1 { box-shadow: 0 0 4px 2px
    rgba( 0, 0, 0, .2 ); }
  - .shadow-2 { box-shadow: 0 0 8px 2px rgba( 0, 0, 0, .2 ); }
  - .shadow-3 { box-shadow: 2px 2px 4px 2px rgba( 0, 0, 0, .2 ); }
  - .shadow-4 { box-shadow: 2px 2px 8px 0 rgba( 0, 0, 0, .2 ); }
  - .shadow-5 { box-shadow: 4px 4px 8px 0 rgba( 0, 0, 0, .2 ); }

#### Positioning:
  - .dn { display: none; }
  - .di { display: inline; }
  - .db { display: block; }
  - .dib { display: inline-block; }
  - .fl { float: left; display: inline; }
  - .fr { float: right; display: inline; }
  - .fn { float: none; }
  - .tl { text-align: left; }
  - .tr { text-align: right; }
  - .tc { text-align: center; }
  - .tj { text-align: justify; }
  - .center { margin-right: auto; margin-left: auto; }

 - .flex { display: flex; }
 - .flex-column { flex-direction: column; }
 - .flex-row { flex-direction: row; }
 - .flex-wrap|nowrap { flex-wrap: wrap|nowrap; }
 - .justify-center|start|end|around|between { justify-content: center|start|end|around|between; }
 - .align-center/end/start { align-items: center/end/start; }

#### Height and Widths:
 - Base:
  - w = width
  - h = height
 - Modifiers
  - 1 = 1st step in width scale
  - 2 = 2nd step in width scale
  - 3 = 3rd step in width scale
  - 4 = 4th step in width scale
  - 5 = 5th step in width scale

- Media Query Extensions:
  - ns = not-small
  - m  = medium
  - l  = large

 - Sizes
  - -10  = literal value 10%
  - -20  = literal value 20%
  - -25  = literal value 25%
  - -30  = literal value 30%
  - -33  = literal value 33%
  - -34  = literal value 34%
  - -40  = literal value 40%
  - -50  = literal value 50%
  - -60  = literal value 60%
  - -70  = literal value 70%
  - -75  = literal value 75%
  - -80  = literal value 80%
  - -90  = literal value 90%
  - -100 = literal value 100%
  - -third      = 100% / 3 (Not supported in opera mini or IE8)
  - -two-thirds = 100% / 1.5 (Not supported in opera mini or IE8)

    - .h1 { height: 1rem; }
    - .h2 { height: 2rem; }
    - .h3 { height: 4rem; }
    - .h4 { height: 8rem; }
    - .h5 { height: 16rem; }
    - .h-25 { height: 25%; }
    - .h-50 { height: 50%; }
    - .h-75 { height: 75%; }
    - .h-100 { height: 100%; }
    - .min-h-100 { min-height: 100%; }
    - .vh-25 { height: 25vh; }
    - .vh-50 { height: 50vh; }
    - .vh-75 { height: 75vh; }
    - .vh-100 { height: 100vh; }

    - .w1 { width: 1rem; }
    - .w2 { width: 2rem; }
    - .w3 { width: 4rem; }
    - .w4 { width: 8rem; }
    - .w5 { width: 16rem; }
    - .w-10 { width: 10%; }
    - .w-20 { width: 20%; }
    - .w-25 { width: 25%; }
    - .w-30 { width: 30%; }
    - .w-33 { width: 33%; }
    - .w-34 { width: 34%; }
    - .w-40 { width: 40%; }
    - .w-50 { width: 50%; }
    - .w-60 { width: 60%; }
    - .w-70 { width: 70%; }
    - .w-75 { width: 75%; }
    - .w-80 { width: 80%; }
    - .w-90 { width: 90%; }
    - .w-100 { width: 100%; }
    - .w-third { width: calc( 100% / 3 ); }
    - .w-two-thirds { width: calc( 100% / 1.5 ); }

#### Font:
  - .f1 { font-size: 3rem; }
  - .f2 { font-size: 2.25rem; }
  - .f3 { font-size: 1.5rem; }
  - .f4 { font-size: 1.25rem; }
  - .f5 { font-size: 1rem; }
  - .f6 { font-size: .875rem; }
  - .f7 { font-size: .75rem; }
  - .ttc { text-transform: capitalize; }
  - .ttl { text-transform: lowercase; }
  - .ttu { text-transform: uppercase; }
  - .ttn { text-transform: none; }


## Resources
  - Main Tachyons website [Link](http://tachyons.io/).
  - Tachyons's css file on github [Link](https://github.com/tachyons-css/tachyons/blob/master/css/tachyons.css) (if you actually need more classes to play with click that link).
