<h1 align="center">The Ave. (Avenue)</h1>
<h3 align="center"><code>avəˌn(y)o͞o</code></h3>

<br>

<h4 align="center">A Mighty 50%, Ortolinear Battlestation </h4>

<p align="center">
    <img src="https://i.imgur.com/HstmD2y.png"
         alt="avebanner">
</p>

<p align="center">Designed by <a href="https://github.com/The-Royal/The_Royal_Open-Source-Projects/tree/master/01%20-%20Complete%20Kits/The_Ave-rev1.2">The Royal</a>. Modified by Michael Stowe</p>

<br>
<br>
<p align="center">
  <a href="https://github.com/mkstowe/ave_keyboard/tree/main/case/main-case/step-models">
    <img src="https://i.imgur.com/az4T1Yj.png"
         alt="rawmodels"></a>
  <a href="https://github.com/mkstowe/ave_keyboard/tree/main/case/main-case/stl-models"><img src="https://i.imgur.com/CQOSLNR.png"></a>
  <a href="https://github.com/mkstowe/ave_keyboard/tree/main/case/switch-plates"> 
      <img src="https://i.imgur.com/Ehp1EOl.png" alt="stlfiles">
  </a> 
  <a href="https://github.com/mkstowe/ave_keyboard/tree/main/pcb">
    <img src="https://i.imgur.com/765lBTE.png" alt="platefiles">
    </kbd>
  </a>
</p>

<br>
<br>

<p align="center">
<a href="https://geekhack.org/index.php?topic=103834.0">
    <img src="https://i.imgur.com/tB5gpn0.png"
         alt="linktogbforum"></a>
</p>

<p align="center">These items are open sourced files and are held under the MIT License. Free for almost all public use and/or distribution.</p>

<br>
<br>

# The Design & Inspiration

If you have ever been around professional studio workstations, or have seen them in TV or Movies before, you will notice instantly the inspiration for The Ave.

Boards like the **G80-9009HAU**:

<img src="https://i.imgur.com/an0CVS7.jpg" width=380px alt="g80"></a>
<br>
<br>

or the **Yamaha RM-804**:

<img src="https://i.imgur.com/9kcPWKn.jpg" width=380px alt="rm804"></a>
<br>
<br>

***OR*** the legendary **IBM-122**:

<img src="https://i.imgur.com/0WSziJa.jpg" width=380px alt="ibm122"></a>
<br>
<br>


The List just goes on-and-on. They all display their massive stature proudly.   

When you see or think of one of these types of boards, You know there some serious work to be done.

Now I've used 40% from the first moment I jumped onto this crazy train of a hobby.  Something about the simplicity of sub-60% Keybaord instantly drew me in.  And after the few months of frustration and re-learning to be a better typist.  I have found nothing to be as comfortable as 40-60% ortholinear keyboards.

But Sometimes, You need just a

Little.

Bit.

***Less!***...*/more.*

<sup>but not too much</sub>

<br>
<img src="https://i.imgur.com/eR9lDXH.jpg" width=900px alt="ibm122"></a>
<br>
<br>

# General Specs & Details

## LAYOUTS & Alternate Bottom-Row Options
<sup>**NOTE:** *These are 2 Independant PCB Configurations*
- "Ortholinear" PCB has a forced grid-style key layout
- "Staggered" PCB has a layout more akin to your average keyboard. Though undoubtedly more adorable.</sub>

<br>

```
                                                             
                                                         < SIDE NOTE >

                                                        if keyLeftBlank {
                                                        keySize = 1u
                                                        }

// ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
// ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
// ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀



// ┌────┐ ┌────┐                                       ┌────┬────┬────┐
// │    │ │    │  Ortholinear                          │    │    │    │
// └────┘ └────┘                                       └────┴────┴────┘
// ┌────┐ ┌────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┐
// │    │ │    │    │    │    │    │    │    │    │    │    │    │    │
// ├────┤ ├────┼────┼────┼────┼────┼────┼────┼────┼────┼────┼────┼────┤
// │    │ │    │    │    │    │    │    │    │    │    │    │    │    │
// ├────┤ ├────┼────┼────┼────┼────┼────┼────┼────┼────┼────┼────┼────┤
// │    │ │    │    │    │    │    │    │    │    │    │    │    │    │
// ├────┤ ├────┼────┼────┼────┼────┼────┼────┼────┼────┼────┼────┼────┤
// │    │ │    │    │    │    │    │    │    │    │    │    │    │    │
// └────┘ └────┴────┴────┴────┴────┴────┴────┴────┴────┴────┴────┴────┘
//      
//        ┌────┬────┬────┬────┬────┬─────────┬────┬────┬────┬────┬────┐
// OPT:1  │    │    │    │    │    │    2.0u │    │    │    │    │    │
//        └────┴────┴────┴────┴────┴─────────┴────┴────┴────┴────┴────┘
//
//        ┌────┬────┬────┬────┬─────────┬─────────┬────┬────┬────┬────┐
// OPT:2  │    │    │    │    │    2.0u │    2.0u │    │    │    │    │
//        └────┴────┴────┴────┴─────────┴─────────┴────┴────┴────┴────┘
//
//        ┌────┬───────┬─────────────────────────────────┬───────┬────┐
// OPT:3  │    │  1.5u │                            7.0u │  1.5u │    │
//        └────┴───────┴─────────────────────────────────┴───────┴────┘



// ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
// ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
// ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀



// ┌────┐ ┌────┐                                       ┌────┬────┬────┐
// │    │ │    │  Staggered                            │    │    │    │
// └────┘ └────┘                                       └────┴────┴────┘
// ┌────┐ ┌────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┐
// │    │ │    │    │    │    │    │    │    │    │    │    │    │    │
// ├────┤ ├────┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴────┤
// │    │ │1.25u│    │    │    │    │    │    │    │    │    │  1.75u │
// ├────┤ ├─────┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─────┤
// │    │ │  1.75u │    │    │    │    │    │    │    │    │    │1.25u│
// ├────┤ ├─────┬──┴─┬──┴──┬─┴────┴────┴──┬─┴────┴───┬┴────┼────┼─────┤
// │    │ │1.25u│    │1.25u│        2.75u │    2.25u │1.25u│    │1.25u│
// └────┘ └─────┴────┴─────┴──────────────┴──────────┴─────┴────┴─────┘

//        ┌─────┬────┬───────────────────────────────┬─────┬────┬─────┐
// Opt:1  │1.25u│    │                         6.25u │1.25u│    │1.25u│
//        └─────┴────┴───────────────────────────────┴─────┴────┴─────┘



// ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
// ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
// ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀

```
<br>
<br>

## Functions & Features
___

<br>

### PCB Features:
- Fully powered and supported by [*QMK Firmware*](https://github.com/qmk/qmk_firmware) and the [**QMK Online Configurator**](https://config.qmk.fm/#/kingly_keys/ave/ortho/LAYOUT_ortho_all)

- 2 Independent PCBs (I don't like Swiss Cheese)

- Fun, Eye-catching and Efficient layouts + Simple Routing = beautiful PCB

- THROUGH-HOLE "NeoPixel" RGB LEDs for customizable indicators

- EC11 Rotary encoder located in top left corner. (can also be Customized to you preferece)

- Through-Hole Diodes for the Vintage Look and Feel
   - There is a lot of satisfaction in putting the time in to building and soldering something that's yours.  Makes it all the more worth it :)

<br>

**Notable PCB Notices:**

- NO IN-SWITCH LEDs (Prettier PCB and I never use shine-through keycaps)

- PCB is only compatible with MX-Style Switches (Cherry, Gateron, Kaihl, etc.)
