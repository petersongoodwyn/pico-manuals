---
Title: Colour Duo Assembly Guide
Date: 11-11-2020
Template: manual
---
<!-- if you want to exclude something from the mcb_toc just make it and 'H1' as opposed to an 'h1' -->

<div>
  <div class="step-image">
    <a href="https://www.diyrecordingequipment.com/collections/colour/products/colour-duo">
             <img src="%base_url%/assets/duo/14.4-finished-three-quarter-600.jpg">    	
    </a>
  </div>
  <div class="step-header">Welcome to the Colour Duo assembly guide.</div>
  <div class="step-description">
      <p>Thank you for purchasing a <a href="https://www.diyrecordingequipment.com/collections/colour/products/colour-duo">Colour Duo!</a></p>
      <p>The Duo is intended for intermediate builders. If you have built a 500-series module or several guitar pedals before you should have no problem with the Duo. However, keep in mind it's a big kit! There are hundreds of parts to place, so plan to split the building over several sessions.</p>
      
  </div>
</div>

<h2>Required Tools</h2>

@[/tools/soldering-iron.html]
@[/tools/solder.html]
@[/tools/wire-cutters.html]

<h2>Optional Tools</h2>

@[/tools/multi-meter.html]
@[/tools/tape.html]
@[/tools/desoldering-pump.html]

<h2>Component Sorting Sheet</h2>
<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/duo-sorting-1.1.pdf" target="_blank">
    <img src="%base_url%/assets/pdf-download.png" />
    </a>
    </div>
    <div class="step-description">
        <p>To identify and keep track the resistors, download and print the <a href="%base_url%/assets/duo/duo-sorting-1.1.pdf" target="_blank">Component Sorting Sheet (PDF)</a>.</p>
    </div>
</div>

<div id="assembly-guide-content">
<H1 class="exclude" style="clear: both">I/O Board Assembly</H1>

<div class="manual-step">
    <div class="step-description">
    <p>The Colour Duo is split into two sections, the I/O Board and Drawer. In this guide we'll build the I/O Board first and then the Drawer.</p>
    </div>
    <div><a href="https://maps.diy.re/duo-io" target="_blank" rel="noopener noreferrer"><img src="https://cdn.shopify.com/s/files/1/0698/2265/files/IBMicon.png?10596201697740015471" width="60" height="48">Duo IO PCB Interactive Build Map</a></div>
</div>

<h2>I/O Board Resistors (Bag 1)</h2>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/res-bend.jpg" target="_blank">
    <img src="%base_url%/assets/duo/res-bend-600.jpg" />
    </a>
    </div>
    @[/mods/res-bend.html]
    <p><strong>Parts in this step:</strong> Refer to the component <a href="%base_url%/assets/duo/duo-sorting-1.1.pdf">sorting sheet</a>.</p>
    
</div>

<div class="manual-step">
    @[/mods/res-sort.html]
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/1.3-place-res.jpg" target="_blank">
    <img src="%base_url%/assets/duo/1.3-place-res-600.jpg" />
    </a>
    </div>
    @[/mods/res-place.html]
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/1.4-solder-res.jpg" target="_blank">
    <img src="%base_url%/assets/duo/1.4-solder-res-600.jpg" />
    </a>
    </div>
    @[/mods/res-solder.html]
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/1.5-trim-res.jpg" target="_blank">
    <img src="%base_url%/assets/duo/1.5-trim-res-600.jpg" />
    </a>
    </div>
    @[/mods/res-trim.html]
</div>

<h2>I/O Board IC, Transistors, Caps, Diodes (Bag 2)</h2>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/2.1-pop-trans.jpg" target="_blank">
    <img src="%base_url%/assets/duo/2.1-pop-trans-600.jpg" />
    </a>    
    </div>
    <h3 class="step-header">Populate Transistors</h3>

<div class="step-description">
        <p>There are two important things to note about the transistors. First, one side of the body is flat while the
                other is round. And second, one is a BC327 (black top) while the other is a BC337 (silver top).
        </p>
        <p>
                Place the BC327 in Q1 and the BC337 in Q2. Place both of them so that the shape of the body matches the
                shape on the circuit board. Double check the positions and orientation, then solder and trim.
        </p>
</div>
        <div class="step-parts">
        <p><strong>Parts in this step:</strong></p>
        <div class="part">
            <p>Q1<br>BC327 transistor</p>
            <img src="%base_url%/assets/parts/com-t-to92.png">
        </div>
        <div class="part">
            <p>Q2<br>BC337 transistor</p>
            <img src="%base_url%/assets/parts/com-t-to92-silver.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/2.2-ic-sockets.jpg" target="_blank">
    <img src="%base_url%/assets/duo/2.2-ic-sockets-600.jpg" />
    </a>    
    </div>
    @[/mods/ic-sockets.html]
        <div class="step-parts">
        <div class="part">
            <p>IC1, IC2<br>IC socket (x2)</p>
            <img src="%base_url%/assets/parts/com-h009.png">
        </div>
    </div>

</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/2.3-place-ics.jpg" target="_blank">
    <img src="%base_url%/assets/duo/2.3-place-ics-600.jpg" />
    </a>    
    </div>
    @[/mods/ics.html]
        <div class="step-parts">
        <div class="part">
            <p>IC1, IC2<br>1256 line receiver (x2)</p>
            <img src="%base_url%/assets/parts/com-u-dip8.png">
        </div>
        </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/2.4-pop-byp-caps.jpg" target="_blank">
    <img src="%base_url%/assets/duo/2.4-pop-byp-caps-600.jpg" />
    </a>    
    </div>
    <h3 class="step-header">Populate Bypass Capacitors</h3>
    <div class="step-description"><p>Populate the yellow .1uF capacitors in the positions marked CB, as well as C10 and C11. These capacitors are not polarized and can therefore be installed in either direction. After soldering, trim the leads.</p></div>
        <div class="step-parts">
        <div class="part">
            <p>CB1-CB4, C10, C11<br>.1u ceramic cap (x6)</p>
            <img src="%base_url%/assets/parts/com-c004.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/2.5-pop-diodes.jpg" target="_blank">
    <img src="%base_url%/assets/duo/2.5-pop-diodes-600.jpg" />
    </a>    
    </div>
    @[/mods/diodes.html]
    <div class="step-parts">
        <div class="part">
            <p>D1<br>1N4004 diode</p>
            <img src="%base_url%/assets/parts/com-d005.png">
        </div>
        <div class="part">
            <p>D2<br>5.6v zener diode</p>
            <img src="%base_url%/assets/parts/com-d010.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/2.6-pop-small-caps.jpg" target="_blank">
    <img src="%base_url%/assets/duo/2.6-pop-small-caps-600.jpg" />
    </a>    
    </div>
    @[/mods/caps-small.html]
     <div class="step-parts">
        <div class="part">
            <p>C2, C3, C6, C7<br>470p caps</p>
            <img src="%base_url%/assets/parts/com-c009.png">
            <p>Markings: 471</p>
        </div>
        <div class="part">
            <p>C4, C8<br>47p caps</p>
            <img src="%base_url%/assets/parts/com-c010.png">
            <p>Markings: 47j</p>
        </div>
    </div>
</div>

<h2>I/O Board Connectors (Bag 3)</h2>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/3.1-pop-btb-cons.jpg" target="_blank">
    <img src="%base_url%/assets/duo/3.1-pop-btb-cons-600.jpg" />
    </a>    
    </div>
    @[/mods/board-to-board-connectors.html]
        <div class="step-parts">
        <div class="part">
            <p>CON1A, CON2A<br>Board-to-board connector (x2)</p>
            <img src="%base_url%/assets/parts/com-j023.png">
        </div>
        <div class="part">
            <p>CON1A, CON2A<br>3-48 Screw (x4)</p>
            <img src="%base_url%/assets/parts/hw-s021.png">
        </div>
        <div class="part">
            <p>CON1A, CON2A<br>Nylon washer (x4)</p>
            <img src="%base_url%/assets/parts/hw-w002.png">
        </div>
        <div class="part">
            <p>CON1A, CON2A<br>3-48 Nut (x4)</p>
            <img src="%base_url%/assets/parts/hw-n006.png">
        </div>
        </div>
</div>

<h2>I/O Board Large Capacitors, Inductors, and Relay (Bag 4)</h2>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/4.1-pop-relay.jpg" target="_blank">
    <img src="%base_url%/assets/duo/4.1-pop-relay-600.jpg" />
    </a>    
    </div>
    @[/mods/relay.html]
        <div class="step-parts">
        <div class="part">    
            <p>U1<br>24V relay</p>
            <img src="%base_url%/assets/parts/com-z010.png">
        </div>
        </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/4.2-pop-inductors.jpg" target="_blank">
    <img src="%base_url%/assets/duo/4.2-pop-inductors-600.jpg" />
    </a>    
    </div>
    @[/mods/inductors.html]
        <div class="step-parts">
        
        <div class="part">    
            <p>L1-L3<br>470u inductor (x3)</p>
            <img src="%base_url%/assets/parts/com-l008.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/4.3-pop-large-caps.jpg" target="_blank">
    <img src="%base_url%/assets/duo/4.3-pop-large-caps-600.jpg" />
    </a>    
    </div>
    @[/mods/caps-large.html]
       <div class="part">    
            <p>C1, C5<br>100u cap (x2)</p>
            <img src="%base_url%/assets/parts/com-c022.png">
        </div>
        <div class="part">    
            <p>C9, C16<br>100u/63v cap (x2)</p>
            <img src="%base_url%/assets/parts/com-c028.png">
        </div>
        <div class="part">    
            <p>C12-C15<br>2200u cap (x4)</p>
            <img src="%base_url%/assets/parts/com-c043.png">
   </div>
</div>

<h2>Jacks (Bag 5)</h2>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/5.1-pop-trs.jpg" target="_blank">
    <img src="%base_url%/assets/duo/5.1-pop-trs-600.jpg" />
    </a>    
    </div>
    @[/mods/trs-jacks.html]
        <div class="step-parts">
        <div class="part">    
            <p>J1, J5<br>TRS jack (x2)</p>
            <img src="%base_url%/assets/parts/com-j010.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/5.2-pop-xlr.jpg" target="_blank">
    <img src="%base_url%/assets/duo/5.2-pop-xlr-600.jpg" />
    </a>    
    </div>
    @[/mods/xlrs.html]
    <div class="step-parts">
        <div class="part">
            <p>J2, J6<br>3-pin XLR male jack (x2)</p>
            <img src="%base_url%/assets/parts/com-j007.png">
        </div>
        <div class="part">
            <p>J3, J7<br>Combo jack (x2)</p>
            <img src="%base_url%/assets/parts/com-j024.png">
        </div>
        <div class="part">
            <p>J4, J8<br>3-pin XLR female jack (x2)</p>
            <img src="%base_url%/assets/parts/com-j008.png">
        </div>
        <div class="part">
            <p>J9<br>5-pin XLR female jack</p>
            <img src="%base_url%/assets/parts/com-j017.png">
        </div>
        <div class="part">
            <p>J10<br>5-pin XLR male jack</p>
            <img src="%base_url%/assets/parts/com-j016.png">
        </div>
</div>
</div>


<H1 class="exclude" style="clear:both">Drawer Assembly</H1>

<h2>Active Switch Parts (Bag 6)</h2>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/6.1-pop-res.jpg" target="_blank">
    <img src="%base_url%/assets/duo/6.1-pop-res-600.jpg" />
    </a>    
    </div>
    <h3 class="step-header">Populate Resistors</h3>
    <div class="step-description">
    <p>Populate the resistors as in step 1.</p>
    </div>
        <div class="step-parts">
        <div class="part">
            <p>R40<br>2.2k resistor</p>
            <img src="%base_url%/assets/parts/com-r-2.2k.png">
        </div>
        <div class="part">
            <p>R41<br>47k resistor</p>
            <img src="%base_url%/assets/parts/com-r-47k.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/6.2-pop-diode.jpg" target="_blank">
    <img src="%base_url%/assets/duo/6.2-pop-diode-600.jpg" />
    </a>    
    </div>
    @[/mods/diode.html]
        <div class="step-parts">
        <div class="part">
            <p>D3<br>1N4004 diode</p>
            <img src="%base_url%/assets/parts/com-d005.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/6.3-pop-relay.jpg" target="_blank">
    <img src="%base_url%/assets/duo/6.3-pop-relay-600.jpg" />
    </a>    
    </div>
    <h3 class="step-header">Populate Relay</h3>
    <div class="step-description">
    <p>Populate the relay as before.</p>
    </div>
        <div class="step-parts">
        <div class="part">    
            <p>U1<br>24V relay</p>
            <img src="%base_url%/assets/parts/com-z010.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/6.4-lightpipe-cap.jpg" target="_blank">
    <img src="%base_url%/assets/duo/6.4-lightpipe-cap-600.jpg" />
    </a>    
    </div>
    @[/mods/lightpipe-switch-cap.html]
    <div class="step-parts">
        <div class="part">
            <p><br>Lightpipe switch cap</p>
            <img src="%base_url%/assets/parts/com-k010.png">
        </div>
        <div class="part">
            <p>SW4<br>DPDT switch</p>
            <img src="%base_url%/assets/parts/com-e006.png">
        </div>
</div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/6.5-pop-switch.jpg" target="_blank">
    <img src="%base_url%/assets/duo/6.5-pop-switch-600.jpg" />
    </a>
    </div>
    @[/mods/switch-pushbutton.html]
</div>

<H1 class="exclude" style="clear: both">Populating the Channels</H1>


<div class="manual-step">
    <div class="step-description">
    <p>Since channels 1 and 2 of the Duo are identical, the steps below are written for just one channel. The kit bags are also split up by channel, so there are two of each bag for the following steps. It’s up to you whether you want to build one channel at a time or both at the same time. If you choose to build them one at a time, repeat steps 7-12 for each channel.</p>
    </div>

    <div><a href="https://maps.diy.re/duo" target="_blank" rel="noopener noreferrer"><img src="https://cdn.shopify.com/s/files/1/0698/2265/files/IBMicon.png?10596201697740015471" width="60" height="48">Duo Drawer PCB Interactive Build Map</a></div>
</div>

<h2>Drawer Resistors (Bag 7)</h2>

<div class="manual-step">    
    <h3 class="step-header">Sort Resistors</h3>
        <div class="step-description">
        <p>Here's a link to that same resistor tool from above: <a href="https://maps.diy.re/res-calc/" target="_blank">Resistor Calculator</a></p>
        </div>
        <p><strong>Parts in this step:</strong> Refer to the component <a href="%base_url%/assets/duo/duo-sorting-1.1.pdf">sorting sheet</a>.</p>
</div>
<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/7.2-pop-res.jpg" target="_blank">
    <img src="%base_url%/assets/duo/7.2-pop-res-600.jpg" />
    </a>    
    </div>
    <h3 class="step-header">Populate Resistors</h3>
    <div class="step-description">
    <p>Populate the resistors as you did before.</p>
    </div>
</div>

<h2>Drawer ICs and Colour Sockets (Bag 8)</h2>


<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/8.1-pop-colour-sockets.jpg" target="_blank">
    <img src="%base_url%/assets/duo/8.1-pop-colour-sockets-600.jpg" />
    </a>    
    </div>
<h3 class="step-header">Populate Colour Sockets</h3>
    
<div class="step-description">
    <p>Flip the PCB over and place the 8-pin Colour sockets in their positions. Solder one leg of each socket from the bottom to hold them in place, then flip the PCB over and solder all of the joints. Make sure that you have placed the sockets on the underside of the PCB before soldering!</p>
</div>
    <div class="step-parts">
        <div class="part">    
            <p>CON6-CON8<br>Colour socket (x3)</p>
            <img src="%base_url%/assets/parts/com-h001.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/8.2-ic-sockets.jpg" target="_blank">
    <img src="%base_url%/assets/duo/8.2-ic-sockets-600.jpg" />
    </a>
    </div>
    <div class="step-description">
    <h3 class="step-header">Populate IC sockets</h3>
    <p>Tape and solder the IC sockets as you did before.</p>
    </div>
        <div class="step-parts">
        <div class="part">
            <p>IC1-IC5<br>IC socket (x5)</p>
            <img src="%base_url%/assets/parts/com-h009.png">
        </div>
    </div>
</div>


<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/8.3-pop-diode-bridge.jpg" target="_blank">
    <img src="%base_url%/assets/duo/8.3-pop-diode-bridge-600.jpg" />
    </a>    
    </div>
    @[/mods/diode-bridge.html]
        <div class="step-parts">
        <div class="part">    
            <p>BR1<br>Diode bridge</p>
            <img src="%base_url%/assets/parts/com-u001.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/8.4-pop-ics.jpg" target="_blank">
    <img src="%base_url%/assets/duo/8.4-pop-ics-600.jpg" />
    </a>
    </div>
    <h3 class="step-header">Populate ICs</h3>
    <div class="step-description">
    <p>Place the ICs in their sockets as you did before, playing close attention to their orientation. Note that some NE5532 ICs have a dot on the body to indicate pin 1 instead of a notch. In this case, orient the ICs so that the dot on the IC aligns with the notch on the IC socket.</p>
    </div>
        <div class="step-parts">
        <div class="part">
            <p>IC1<br>1512 mic preamp</p>
            <img src="%base_url%/assets/parts/com-u-dip8.png">
            <p>Markings: THAT 1512</p>
        </div>
        <div class="part">
            <p>IC2-IC5<br>NE5532 opamp (x4)</p>
            <img src="%base_url%/assets/parts/com-u-dip8.png">
            <p>Markings: NE5532P</p>
        </div>
    </div>
</div>

<h2>Drawer Capacitors and Diodes (Bag 9)</h2>


<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/9.1-pop-byp-cap.jpg" target="_blank">
    <img src="%base_url%/assets/duo/9.1-pop-byp-cap-600.jpg" />
    </a>    
    </div>
    <h3 class="step-header">Populate Bypass Capacitors</h3>
    <div class="step-description">
    <p>Populate the bypass capacitors as you did before.</p>
    </div>
        <div class="step-parts">
        <div class="part">
            <p>CB1-CB10<br>.1u ceramic cap (x10)</p>
            <img src="%base_url%/assets/parts/com-c004.png">
        </div>
    </div>
</div>


<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/9.2-pop-diodes.jpg" target="_blank">
    <img src="%base_url%/assets/duo/9.2-pop-diodes-600.jpg" />
    </a>    
    </div>
    <h3 class="step-header">Populate Diodes</h3>
    <div class="step-description">
    <p>Populate the diodes as before, paying close attention to the black lines for orientation.</p>
    </div>
     <div class="step-parts">
        <div class="part">
            <p>D1, D2<br>1N914 diode (x2)</p>
            <img src="%base_url%/assets/parts/com-d002.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/9.3-pop-small-caps.jpg" target="_blank">
    <img src="%base_url%/assets/duo/9.3-pop-small-caps-600.jpg" />
    </a>    
    </div>
    <h3 class="step-header">Populate Remaining Small Capacitors</h3>
<div class="step-description">
    <p>Place the remaining capacitors in their respective places. As before, these capacitors are not polarized.</p>
</div>
     <div class="step-parts">
        <div class="part">
            <p>C4<br>82n cap</p>
            <img src="%base_url%/assets/parts/com-c057.png">
        </div>
         <div class="part">
            <p>C6-C8<br>22p cap (x3)</p>
            <img src="%base_url%/assets/parts/com-c003.png">
        </div>
    </div>
</div>

<h2>Drawer Large Capacitors (Bag 10)</h2>


<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/10.1-pop-large-caps.jpg" target="_blank">
    <img src="%base_url%/assets/duo/10.1-pop-large-caps-600.jpg" />
    </a>    
    </div>
    <h3 class="step-header">Populate Large Capacitors</h3>
    <div class="step-description">
    <p>Populate the large capacitors as you did on the IO board. Remember that these are all polarized and must be placed in a particular direction.</p>
    </div>
    <div class="step-parts">
        <div class="part">    
            <p>C1, C2<br>100u/63v cap (x2)</p>
            <img src="%base_url%/assets/parts/com-c028.png">
        </div>
       <div class="part">    
            <p>C5, C9<br>100u cap (x2)</p>
            <img src="%base_url%/assets/parts/com-c022.png">
        </div>
        <div class="part">    
            <p>C3<br>3300u cap</p>
            <img src="%base_url%/assets/parts/com-c030.png">
   </div>
   </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/10.2.cap-fix.jpg" target="_blank">
    <img src="%base_url%/assets/duo/10.2-cap-fix-600.jpg" />
    </a>    
    </div>
    <h3 class="step-header">Populate Bug Fix Capacitors</h3>
    <div class="step-description">
    <p>These two capacitors have been added to the kit to fix a bug where, in rare cases, IC1 will fail when the drawer is plugged and unplugged.</p>
    <p>Before placing the capacitors, bend their leads so that they have approximately the same spacing as the distance between the +16v, Gnd, and -16v test points near U1. Then place the capacitors in the test points with the positive lead of in +16v, the negative lead of the other in -16v, and the remaining leads of both in Gnd. Solder and trim the capacitors.</p>
    </div>
    <div class="step-parts">
        <div class="part">    
            <p>N/A<br>220u cap (x2)</p>
            <img src="%base_url%/assets/parts/com-c002.png">
        </div>
   </div>
   </div>
</div>

<h2>Drawer Connectors, Switches, and Sockets (Bag 11)</h2>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/11.1-pop-btb-cons.jpg" target="_blank">
    <img src="%base_url%/assets/duo/11.1-pop-btb-cons-600.jpg" />
    </a>    
    </div>
    @[/mods/board-to-board-connector.html]
        <div class="step-parts">
        <div class="part">
            <p>CON1B/CON2B<br>Board-to-board connector</p>
            <img src="%base_url%/assets/parts/com-j023.png">
        </div>
        <div class="part">
            <p>CON1A, CON2A<br>3-48 Screw (x2)</p>
            <img src="%base_url%/assets/parts/hw-s021.png">
        </div>
        <div class="part">
            <p>CON1A, CON2A<br>Nylon washer (x2)</p>
            <img src="%base_url%/assets/parts/hw-w002.png">
        </div>
        <div class="part">
            <p>CON1A, CON2A<br>3-48 Nut (x2)</p>
            <img src="%base_url%/assets/parts/hw-n006.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/11.2-pop-switches.jpg" target="_blank">
    <img src="%base_url%/assets/duo/11.2-pop-switches-600.jpg" />
    </a>    
    </div>
    <h3 class="step-header">Install Switch Caps and Populate Switches</h3>
<div class="step-description">
    <p>Press the caps onto the switches. This may require a bit more force than you’d expect.</p>
    <p>Place the switches and use a small screwdriver to bend a couple of the leads against the bottom of the PCB. Solder and trim.</p>
</div>
    <div class="step-parts">
        <div class="part">
            <p><br>Switch cap (x3)</p>
            <img src="%base_url%/assets/parts/com-k007.png">
        </div>
        <div class="part">
            <p>SW1-SW3<br>DPDT switch (x3)</p>
            <img src="%base_url%/assets/parts/com-e006.png">
        </div>
</div>
</div>

<div class="manual-step">
<h3>Quick Question</h3>
    <form action="https://formsubmit.co/hi2zl04q@robot.zapier.com" method="POST" target="_blank" id="form-usage">
    <input type="hidden" name="_replyto">
    <input type="hidden" name="_subject" value="%meta.title%">
        @[/mods/usage-feedback.html]
    </form>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/11.3-pop-header-sockets.jpg" target="_blank">
    <img src="%base_url%/assets/duo/11.3-pop-header-sockets-600.jpg" />
    </a>
    </div>
    @[/mods/header-sockets.html]
<div class="step-parts">
        <div class="part">
            <p>CON3, CON4<br>12-pin socket (x2)</p>
            <img src="%base_url%/assets/parts/com-h002.png">
        </div>
        <div class="part">
            <p>CON5<br>6-pin socket</p>
            <img src="%base_url%/assets/parts/com-h029.png">
        </div>
</div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/11.4-pop-pots.jpg" target="_blank">
    <img src="%base_url%/assets/duo/11.4-pop-pots-600.jpg" />
    </a>
    </div>
    @[/mods/potentiometers.html]
    <div class="step-parts">
        <div class="part">
            <p>VR1<br>C1k pot</p>
            <img src="%base_url%/assets/parts/com-e-pot-single.png">
            <p>Markings: C1k</p>
        </div>
        <div class="part">
            <p>VR5<br>B10k pot</p>
            <img src="%base_url%/assets/parts/com-e-pot-single.png">
            <p>Markings: B10k</p>
        </div>
        <div class="part">
            <p>VR2, VR3, VR4, VR6<br>B20k pot (x4)</p>
            <img src="%base_url%/assets/parts/com-e-pot-single.png">
            <p>Markings: B20k</p>
        </div>
</div>
</div>

<h2>Drawer Daughter Board Parts (Bag 12)</h2>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/12.1-pop-res.jpg" target="_blank">
    <img src="%base_url%/assets/duo/12.1-pop-res-600.jpg" />
    </a>
    </div>
    <h3 class="step-header">Populate Resistors</h3>
<div class="step-description">
    <p>Populate the resistors as before.</p>
</div>
    <div class="step-parts">
        <div class="part">
            <p>R1_DB<br>47k resistor</p>
            <img src="%base_url%/assets/parts/com-r-47k.png">
        </div>
         <div class="part">
            <p>R2_DB<br>100k resistor</p>
            <img src="%base_url%/assets/parts/com-r-100k.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/12.2-pop-header-pins.jpg" target="_blank">
    <img src="%base_url%/assets/duo/12.2-pop-header-pins-600.jpg" />
    </a>
    </div>
    @[/mods/header-pins.html]
    <div class="step-parts">
        <div class="part">
            <p>CON3_DB, CON4_DB<br>12-pin header (x2)</p>
            <img src="%base_url%/assets/parts/com-h003.png">
        </div>
        <div class="part">
            <p>CON5_DB<br>6-pin header</p>
            <img src="%base_url%/assets/parts/com-h003-6.png">
        </div>
</div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/12.3-pop-switches.jpg" target="_blank">
    <img src="%base_url%/assets/duo/12.3-pop-switches-600.jpg" />
    </a>    
    </div>
    <h3 class="step-header">Install Switch Caps and Populate Switches</h3>
    
<div class="step-description">
    <p>As you did before, position the lightpipe switch cap so that the flat surface faces the bottom of the switch. Then press the cap onto the switch until it snaps into place. Also install the black switch caps on the remaining switches.</p>
    <p>Then place and solder all the switches.</p>
</div>
<div class="step-parts">
        
        <div class="part">
            <p><br>Switch cap (x2)</p>
            <img src="%base_url%/assets/parts/com-k007.png">
        </div>
        <div class="part">
            <p><br>Lightpipe switch cap (x4)</p>
            <img src="%base_url%/assets/parts/com-k010.png">
        </div>
        <div class="part">
            <p>SW1_DB-SW6_DB<br>DPDT switch (x6)</p>
            <img src="%base_url%/assets/parts/com-e006.png">
        </div>
</div>
</div>

<H1 class="exclude" style="clear: both">Chassis Assembly</H1>

<h2>Chassis Fasteners (Bag 13)</h2>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/13.1-insert-rails.jpg" target="_blank">
    <img src="%base_url%/assets/duo/13.1-insert-rails-600.jpg" />
    </a>
    </div>
<h3 class="step-header">Insert Drawer Rails</h3>
    
<div class="step-description">
    <p>Position the drawer rails on the inside of the case with the wider opening facing the front of the case. Then snap them into the holes indicated above.</p>
</div>
    <div class="step-parts">
        
        <div class="part">
            <p>PCB rail (x2)</p>
            <img src="%base_url%/assets/parts/com-z011.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/13.2-io-board-to-case.jpg" target="_blank">
    <img src="%base_url%/assets/duo/13.2-io-board-to-case-600.jpg" />
    </a>
    </div>
<h3 class="step-header">Fasten IO Board to Case</h3>
    
<div class="step-description">
    <p>Mount the assembled IO board to the case. You will need to tilt it slightly to get the PUSH tabs of the XLR jacks through the holes first. Then fasten the nuts and washers to the TRS jacks, and screw in the mounting screws for the XLR jacks.</p>
</div>
    <div class="step-parts">
        <div class="part">
            <p>XLR screw (x16)</p>
            <img src="%base_url%/assets/parts/hw-s022.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/13.3-nut-plates.jpg" target="_blank">
    <img src="%base_url%/assets/duo/13.3-nut-plates-600.jpg" />
    </a>
    </div>
<h3 class="step-header">Install Nut Plates</h3>
    
<div class="step-description">
    <p>
    Place each nut plate behind one of the flanges at the front of the case, so that the holes line up with those on the flange. Then fasten them to the case with the included screws.
    </p>
</div>
    <div class="step-parts">
        <div class="part">
            <p>Nut plate (x2)</p>
            <img src="%base_url%/assets/parts/hw-c040.png">
        </div>
        <div class="part">
            <p>Nut plate screw (x4)</p>
            <img src="%base_url%/assets/parts/hw-s025.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/13.4-pcb-brackets.jpg" target="_blank">
    <img src="%base_url%/assets/duo/13.4-pcb-brackets-600.jpg" />
    </a>
    </div>
<h3 class="step-header">Install PCB Support Brackets</h3>
    
<div class="step-description">
    <p>Place each L-bracket over the pots of the Colour section. Check that the standoffs on the brackets align with the holes in the PCB. Then fasten the brackets to the motherboard via the screws and standoffs. Use standoffs for the three holes closest to the front of the circuit board, and screws for the rest.</p>
</div>
    <div class="step-parts">
        <div class="part">
            <p>PCB bracket screw (x8)</p>
            <img src="%base_url%/assets/parts/hw-s027.png">
        </div>
        <div class="part">
            <p>Standoff (x6)</p>
            <img src="%base_url%/assets/parts/hw-y020.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/13.5-daughterboards.jpg" target="_blank">
    <img src="%base_url%/assets/duo/13.5-daughterboards-600.jpg" />
    </a>
    </div>
<h3 class="step-header">Mount Daughter Boards</h3>
    
<div class="step-description">
    <p>Plug the daughter boards for each channel into the two sets of header sockets. Then screw them to the support standoffs.</p>
</div>
    <div class="step-parts">
        <div class="part">
            <p>PCB bracket screw (x6)</p>
            <img src="%base_url%/assets/parts/hw-s027.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/13.6-lid.jpg" target="_blank">
    <img src="%base_url%/assets/duo/13.6-lid-600.jpg" />
    </a>
    </div>
<h3 class="step-header">Install Lid</h3>
    
<div class="step-description">
    <p>Place the lid on the case with the countersunk side facing up. Then screw it to the case.</p>
</div>
    <div class="step-parts">
        <div class="part">
            <p>Lid screw (x7)</p>
            <img src="%base_url%/assets/parts/hw-s026.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/13.7-rack-ears.jpg" target="_blank">
    <img src="%base_url%/assets/duo/13.7-rack-ears-600.jpg" />
    </a>
    </div>
<h3 class="step-header">Install Rack Ears (Optional)</h3>
    
<div class="step-description">
    <p>If you plan to use your Duo in a rack, screw the rack ears to the case.</p>
</div>
    <div class="step-parts">
        <div class="part">
            <p>Rack ear screw (x6)</p>
            <img src="%base_url%/assets/parts/hw-s024.png">
        </div>
    </div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/13.8-rubber-feet.jpg" target="_blank">
    <img src="%base_url%/assets/duo/13.8-rubber-feet-600.jpg" />
    </a>
    </div>
<h3 class="step-header">Apply Rubber Feet (Optional)</h3>
    
<div class="step-description">
    <p>If you plan to use your Duo on a desktop, you may choose to apply the rubber feet to the bottom of the case. Keep in mind that you will need to remove them later if you want to use the Duo in a rack with another unit directly below it.</p>
</div>
    <div class="step-parts">
        <div class="part">
            <p>Rubber foot (x5)</p>
            <img src="%base_url%/assets/parts/hw-y021.png">
        </div>
    </div>
</div>

 <h2>Front Panel (Bag 14)</h2>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/14.1-nuts-to-pots.jpg" target="_blank">
    <img src="%base_url%/assets/duo/14.1-nuts-to-pots-600.jpg" />
    </a>
    </div>
<h3 class="step-header">Fasten Nuts to Pots</h3>
    
<div class="step-description">
    <p>Place the front panel over the pots and switches (yes, this might be the trickiest part of the build). Place washers over the pot shafts, then screw on the nuts. Note that depending on variations in the length of the threads on the pots and nuts, you may not be able to fit the washer under the nut. In this case, just leave the washer off and fasten the nut directly to the panel.
</p>
</div>
    <div class="step-parts">
        <div class="part">
            <p>Pot washer (x12)</p>
            <img src="%base_url%/assets/parts/hw-w004.png">
        </div>
        <div class="part">
            <p>Pot nut (x12)</p>
            <img src="%base_url%/assets/parts/hw-n005.png">
        </div>
    </div>
</div>


<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/14.2-pots-to-middle.jpg" target="_blank">
    <img src="%base_url%/assets/duo/14.2-pots-to-middle-600.jpg" />
    </a>
    </div>
<h3 class="step-header">Set Pots to Middle Position</h3>
    
<div class="step-description">
    <p>To prepare for adding the knobs, set all the pots to the middle position (10 clicks in).</p>
</div>
</div>


<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/14.3-knobs-to-pots.jpg" target="_blank">
    <img src="%base_url%/assets/duo/14.3-knobs-to-pots-600.jpg" />
    </a>
    </div>
<h3 class="step-header">Fasten Knobs to Pots</h3>
    
<div class="step-description">
    <p>Place the wider, skirted knobs on the two preamp gain pots, and the non-skirted knobs on the rest of the pots. Orient all of them so that the indicator line points precisely to the 12 o’clock position. Then fasten the knobs to the pot shafts by tightening the set screws with the included hex wrench.</p>
    <div class="step-parts">
        <div class="part">
            <p>Skirted knob (x2)</p>
            <img src="%base_url%/assets/parts/com-k008.png">
        </div>
        <div class="part">
            <p>Non-skirted knob (x10)</p>
            <img src="%base_url%/assets/parts/com-k009.png">
        </div>
    </div>
</div>
</div>

<div class="manual-step">
    <div class="step-image">
    <a href="%base_url%/assets/duo/14.4-finished-three-quarter.jpg" target="_blank">
    <img src="%base_url%/assets/duo/14.4-finished-three-quarter-600.jpg" />
    </a>
    </div>
<h3 class="step-header">Insert Drawer into Case</h3>
    
<div class="step-description">
    <p>Insert the drawer PCB into the PCB rails, then slide the assembly into the case. There should be some resistance at the end when the board-to-board connectors mate. Then fasten the front panel to the case by tightening the thumb screws.</p>
</div>
</div>

<h2>Final Checks</h2>
<div class="manual-step">
<ul class="manual-checks">
<p>Before you wrap up, check the following things:</p>

@[/checks/capacitor.html]  
@[/checks/diode.html]
@[/checks/ic.html]   
@[/checks/resistor.html]
@[/checks/transistor.html]
@[/checks/solder.html]
</ul>
</div>

<div class="manual-step">
    <div class="step-image">
    <img src="%base_url%/assets/duo/audio-tests-600.jpg" />
    </div>
<h3 class="step-header">Optional: Run Audio Tests</h3>
    
<div class="step-description">
    <p>If you're unit powers up and passes audio fine, most likely it's functioning exactly as it should. But if you want to really be sure, follow the steps in this video to test your Duo with the free software Room Eq Wizard (REW) and your interface:</p>
    <p><a href="https://youtu.be/Qf_rXdLhY1g">Colour Duo Audio Test Process (YouTube)</a></p>
    <p>If you are unfamiliar with the software, please watch our series of videos on measuring gear with REW:</p>
    <p><a href="https://www.youtube.com/watch?v=OwwKV4QTfwU&list=PLLjcaIlBVjDO5CgfHU5WSBKv7Aj13RG2K">Measuring Your Audio Gear with REW (YouTube Playlist)</a></p>
</div>
</div>

<div class="manual-step">
    <div class="step-image">
        <a href="%base_url%/assets/duo/14.4-finished.jpg" target="_blank">
        <img src="%base_url%/assets/duo/14.4-finished-600.jpg" />
        </a>
    </div>
    @[/mods/finished.html]
</div>

</div>

<div class="manual-step">
<h2>Help Us Improve</h2>
    <form action="https://formsubmit.co/support@diyrecordingequipment.com" method="POST" id="form-contact">
      <input type="hidden" name="_subject" value="%meta.title% Feedback">
<p>
    @[mods/contact.html]   
    </form>
</div>




