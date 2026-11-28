# M490L Stereo Input Module · Input Pre Amps

Ward-Beck Systems M490L, 1983|16. Wiki page: [M490L on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/WBSps.ca/Github.WardBeckSystems/MODULES.INPUT-PRE-AMPS.M490L-Stereo-Input-Module/)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 44 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 15 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 5 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 97 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 8 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 45 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

## Specifications

From the technical data sheet: [1983 - M490L - P004 - 1-2.jpg](MANUALS/1983%20-%20M490L%20-%20P004%20-%201-2.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Minimum load impedance** | Maximum Load current: Maximum supp voltage: Saturated collector voltage: 600 ohms 40 MA. +24 volts_ volts maximum 40 MA load. |
| **Power requirements** | +/-25 volts dc, MA maximum MA nominal |
| **Ambient temperature** | degrees Celsius |
| **Dimensions** | wide 14.15&quot; high (41 Mm 360 mm 165 Mm) deep |

## Circuit description

From [1983 - M490L - Stereo Input Module (2).pdf](MANUALS/1983%20-%20M490L%20-%20Stereo%20Input%20Module%20(2).pdf) pages 2-7 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

Parts List

Connector Layou l

Appendi,,:

C04016 Circuit Data C04016 74C 76 Circuit Dll t a 74C76 74C221 Circui l Data 74C221

Drawings' Front Panel 8 490-04_024 Functional 8490_0 1-0 12 Sehematic 8490-02_0 10 Component Layout 8490-06_020

'&quot; MOdules and Sub -Assembly

7 _ 112A Channel Amplifier

Parts List Drawings:

Se hema tic 87-tI 2-02_ oo 2 Componen l Lay o ul 8 7-11 2_06 _00 2 a

**1014901.. STEREO INPUT MODULE**

In!,ut Sen s i ti v it y: _ 10 to +10 dBm (re f. 600 ol'lm source).

F.. eQuen c y Response: +/ _0.5 d B fr-om 30 Hz 1020 kHz.

75 dB below nomin el OPe&quot;.lin g le&quot;e l, will'l mixing anenulno.. 5e l. 1 10 dB &quot;in_l'Iand&quot; (20 Hz 10 20 kHz).

H&quot;,..monic Di Sto.. t lon: Less 1I.,,,,n 0.25' THD from 30 Hz 10 20 kHz e t 20 dB e bov e nominal ope &quot;a ling le &quot;el.

Less lnan 0.1'., I kHz al 20 dB ebeve nominal OPe&quot;.l lng level.

Less Il'Ian 0.51., 1 kHz Il'Irougl'l Cue c l'lanne l.1 20 d B.bo&quot;e nominal op e &quot; ali n g l e&quot;e l.

Source Impedence: 600 ohm &quot; or less, b&quot;, l&quot;, nced.

lnpul Imped.. n c e:

OUlpul lmped.. n ce s: 30,000 otun s, balanced (prog..am c ircu il s). 60,000 ohms, balanced (cue c i..cu il s).

1,000 ohms, balanced {poSI directl.

OU lp UI Le &quot;e l: o dBm nomin.l, +20 dBm m&quot;,x imum. CI'I.nnet Sep..... lion:

P l'le sing: l np u land OUI!'ut lerm inal s de signaled by numbe..s e &quot; eIn p l'l e se, or low e..

numbe.. of numb e..ed p e l.. i&quot; in p l'l e se wi ll'l lowe.. numb e.. 0 1 o ll'le.. nu mbe.. ee

Logle I n !' ul Levels: (to ope &quot;a teCH ON, CH OFF Ct CUE).

Logic 0: 0 10 +1) &quot; 0 115.

Logic 1: +16 10 +2 4,,0 115.

EX l e..nel Con l..er OUl !, u t: (O !'. m col leo:to.. c u....en t sink).

**TECHNICAL DATA**

Minimum IOll'd imp ed llnc e: 6 00 ohm l.

Max im&quot; m load curr e n t' 40 mA.

Maximum 11.Ipply vol lage: +24 vol lS.

SlItur&quot;tedcollec tor voltllge:

Power ReQuirements, +/_25 vol lS dc, 40 mA nomin&quot;l, eo mA m.&quot;imum.

o to 60 degrees Celsius.

1.6 &quot; wide x 14.1 5 &quot; high x 6.5 &quot; deep (4 1 mm x 36D mm x 165 mmJ.

**MA90L STEREO INPUT MOOULE**

The M490L provides complete Sl e..eo c h.. n nel rec r uue s, IU.. equired f_ a miNing console, inclusive oft h e Slereo miNing all enu e t_, input seleclo&quot; and mi&quot;i ng buses.ignmen l switches.

All audio circuits pe&quot; la i ning 10 Ihe left ere..eo c h.. nn el es wet lest h e logic conlrol c irc: u i l r y.. relocated on the mo lh erboa rd o f the module. Thee ud io circuits re ta l ing 10 Ih e ri gh l channel are elect.. ic.. lly i den l lc alto Ih e left c h.. nnel and are placed on a sep ee-ale plug-on boa rd, I y pe 7 _1 12A.

Unless nOled otherwise, Ihe fo t lowing description..e fe.. s 10 the che nne les well as I h e con l ro l ci rcu ll s common 10 both ch.. nne ls.

The mutually In te.. locked INPUT SELECTOR swilch.,. SWI end SW2 permlt Ihe setee uee o f one o f two avail able Slereo sources. An add ilione l cO''lIact Is supplied one e ch s wi l ch f_ con lro l pur-poses.

Follow ing the INPUT SELECTORS, two bel anced insert points ere provided, one, _ eech channel. Their purpose is to pe rml l; n s e &quot; l lon o f ancillary equipment, such as equalizers, fll te rs orc omp..e s50...., l n lot he l efl orr i g h t channels ignal path.

The Is ol all o n net w_ k R l to R4 p..e sen ts bridging imp eden c e of app..o,dma tely 30,000 ohms tot he source. In e p pl ice tion s where aline terminal Ion Is reQui..ed, a 150 0 &quot; 6 00 ohm.. e,.i,. lo.. maybe connected across the module In p u l. Un balanced sign e l sources will require the addition of isole t; o n I..ando..me.. s e&quot; l erna ito I h e module.

The Input ne two..k feeds I hep..eam plifi e.., consisting o f ZI, Z2, 0 1 and 02. RIO Is a continuously ve ri a bl.. SENSITIVITY control for Ih e LEFT channel. II eev e r l a range o f 20 dB, perm ill ing Input le l/ e II f..om -10 dBm 10 +10 dBm 10 b.. a c co mmo dated.

Simila.. ly, R I 35 le,.ves a s t t-e SENSITIVITY cont..ol fo.. I heR IGHT

chan n e l. Both cont,.o ls a,... access i b let h.. ough opening,. i n 11'1e module f..on l panel, with R13S placed j U11 eb c ve RIO.

**M4 90L STEREO INPUT MODULE**

The preampl lf lel&quot; OUIPu l is coup led via C1 10 one half o f I h e ml&quot; lng alt e n u a tOI&quot; ATTI, wilh I h e second half of ATT I used for Ihe I&quot;i g hl Channel. The CUE channel feed is taken fl&quot;Om I h e inputs ide of Ihe attenuatol&quot;.

Progl&quot;am Channel Switch

Z3 is a CM.OS ana log SWi lCh, serving as I h e a Clive swi l ching element of lhe l efl PROGRAM channel. The conlro l voltage 10 oe e r-et e Z3 I. de l&quot;lved from Ihe logic c il&quot;Cui ll&quot;Y within Ih e module and I. coupled to Z 3 via CR2. to switch the channel ON, this cont l&quot;ol voltage is In Ih e ol&quot;del&quot; 01.10 vol IS • When the con ll&quot;Ol voltage dl&quot;DP S to 0 voh., l he switch will b e OFF, I&quot;e s u l lin gIna signal allen ua tlon of more than 100 dB. The control voltage used 10 OPel&quot;ate Z 3 is also fed Into the.. igh t channel c il&quot;Cult l&quot;y via pin E5 on l he 1 _ 112A ca.. d.

Following ZJ, the signal Is amplified by i nteg.-al e d circui ls Z4 and Z5 10 a nominal level o f +3 dBm (e Qu iva len l vot tage) and !&quot;OUted tot he PROGRAM ASSIGN switches SWlI and SW5, via BALANCE sw i lch SW3 and BALANCE cont.-o l R4 2 to R' 5. Due to the J d B inserlion lou 01 Ih e BALANCE control, the signal level 11.1 the i npu l of SW' and SW5 is 0 dBm (e q ui val en t voltage).

In Ih. I&quot;igh t channel, Ih e gain is fixed 10.. e s ull ina +3 dBm oulPul b y insertion o f jumper wire Jl o n PCB 7 _ 112A. The left channel contains Ih e LEVEL BALANC!: con t.. ol R3 1 which is used 10 match Ihe level of I h e left chan n e l tot he &quot;; g h l c h lln ne l. R3 1 is factory set and Should require no I&quot; rt hera dj us tmen t.

Unequal level balance would normally be c orr e c ted b y adjustment oft h e S;;NS I TlV ITY I,. im c ont,.ol s R10 and R1 35. The mixing a llenua to,. ATT I should b e placed int h e to dB &quot; in h and&quot; position to make I h l. lldj u s lmen t.

Switch SW3 se &quot; v es to inse.-t the BAL.ANCE control R42 to R45 Into the signal paths. Op e.-a tlon o f this cO&lt;'t.-ol p e.-miu raising I h e level o f

one oft hes t e r-eo chan n e l s while &quot; educing Ih e level oft h e c rb er-.

**MI&lt;90L STEREO INPUT MODULE**

The maximum dell ia lion from the center position allows e l ell e l change from +3 dB to - SOd B, thus &quot; s s u ring thai I he sum t OI,, 1 power cut put of Ihe I WO Slereo ou tpu lS remains essen ti &quot; l l y cons l &quot;nl e tall times.

The P 1 and P2 ASSIGNMENTs witches SW4 and SW5 simultaneously assign both left and r igh l channels to Ih e PI and/or P 2 PROGRAM mixing buses.

The CUEs lgn e ls o.. l gin &quot; te from bridging l a keo ff salt h ein puts 01 t ha slide &quot; tten ua l o r. Owing tot h e high in p u lImped.. n ceo f the CUE channels, their operation has no effect on the main PROGRAM channels. Z7 rep..esents Ih e &quot;udio switCh for I h e left CUE chan n e l. Sim i l.. rly to Z 3, Ih eco n t r o l 1 to 11&quot; g e for Z7 is generated int h e logic circuitry as d e sc.. ib ed f u &quot;lher o n. The output 01 Z7 is followed b y the booster amp l i lie.. za, which int urn feeds the Cue bus m;x lng network R72 /73.

The.. ig h t CUE chen n e l operates ina n identical man ne.. 10 the le tt ~~:'r d.howell e.., the ci..c ult is located o n the 7_ 1 12A p.. in ted circuit

Post Direct Output

The outputs oft he left and right c b.. n ne l.. mp l lf ie.. s a&quot;e summed toge l he.. before the balances witCh Il ia R38/ R4 1. This node, ale nominal level of 0 dBm, is then brought Out tot h e POST DIRECT output atP I_ 20, 21.

Foldba c k Outputs

The FOL DBACK out p ul S, FBI (l e ftc han n e l) &quot; n d F B2 (right ch&quot; nnel),.... eta ken f..om the POST DIRECTs u mm ing node v i&quot; level controls R52 / R53 (F BI) and R5 4/ R55 (FB 2). The nom in,, 1 output level is 0 dBm with each level con l ro l fully cw.

The cOl'1trol 1I0 i t ages required 10 operate the left and.. i g h l solid

srere PROGRAM &quot; n d CUEs wltc tve s are generated w il h thea id of logic circuitry utilizIng i n te grated c irc u; t s Z9 through Z l2.

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdmswNFRuaExVdVU/view?resourcekey=0-9ubdN9eYHR6KhyYDIgB6rw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdmswNFRuaExVdVU&resourcekey=0-9ubdN9eYHR6KhyYDIgB6rw" width="240" alt="1983 - M490L - 490-04-024 - SMILCH SWI THIS SICH THE MOMENIARY JCION IDC.jpg"></a><br><sub>1983|16 · 490-04-024 - SMILCH SWI THIS SICH THE MOMENIARY JCION IDC · <a href="MECHANICAL/1983%20-%20M490L%20-%20490-04-024%20-%20SMILCH%20SWI%20THIS%20SICH%20THE%20MOMENIARY%20JCION%20IDC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQkxvcldrb0Y2ZTg/view?resourcekey=0-9qeOtFu1WxNuMBpqcQTsWA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQkxvcldrb0Y2ZTg&resourcekey=0-9qeOtFu1WxNuMBpqcQTsWA" width="240" alt="1983 - M490L - 490-04-024 - TOR THE INEI CONTROI RIO IDES CONT NUOUS.jpg"></a><br><sub>1983|16 · 490-04-024 - TOR THE INEI CONTROI RIO IDES CONT NUOUS · <a href="MECHANICAL/1983%20-%20M490L%20-%20490-04-024%20-%20TOR%20THE%20INEI%20CONTROI%20RIO%20IDES%20CONT%20NUOUS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1DR7sv19TsvtBcacb5ppInNZxagDrSHwJ/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1DR7sv19TsvtBcacb5ppInNZxagDrSHwJ" width="240" alt="19xx - M490L - DOC - 490-04-024 - OGRAM CHANNCIS BUI-IN.jpg"></a><br><sub>19xx - M490L - DOC - 490-04-024 - OGRAM CHANNCIS BUI-IN · <a href="MECHANICAL/19xx%20-%20M490L%20-%20DOC%20-%20490-04-024%20-%20OGRAM%20CHANNCIS%20BUI-IN%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M490L.stl`](MECHANICAL/M490L.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M490L)

- **Size:** 41 × 360 mm panel, 165 mm deep, 3.2 mm plate (TECHNICAL DATA: wide 14.15" high (41 Mm 360 mm 165 Mm) deep)
- **From the drawing:** 11 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M490L - front panel.svg`)
- Made by `tools/module_models.py` (→ `MECHANICAL/M490L.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd0FPUUc1b2ZEUE0/view?resourcekey=0-7q8vIuLUpESYVoMkhK5UzA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd0FPUUc1b2ZEUE0&resourcekey=0-7q8vIuLUpESYVoMkhK5UzA" width="240" alt="1983 - M490L - 12-02-002 - CONTROL CIB RJI LOOP.jpg"></a><br><sub>1983|16 · 12-02-002 - CONTROL CIB RJI LOOP · <a href="SCHEMATICS/1983%20-%20M490L%20-%2012-02-002%20-%20CONTROL%20CIB%20RJI%20LOOP%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMTMtSE5EQWsyam8/view?resourcekey=0-sKBNIzOvbfyFooTbobi8JA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMTMtSE5EQWsyam8&resourcekey=0-sKBNIzOvbfyFooTbobi8JA" width="240" alt="1983 - M490L - 490-01-012 - ENG SCRTLBERT STEREO INPUT MODULE.jpg"></a><br><sub>1983|16 · 490-01-012 - ENG SCRTLBERT STEREO INPUT MODULE · <a href="SCHEMATICS/1983%20-%20M490L%20-%20490-01-012%20-%20ENG%20SCRTLBERT%20STEREO%20INPUT%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNFdWbkxhZHBpbFE/view?resourcekey=0-Y2p8GIeC0xt8zbzHusHXfg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNFdWbkxhZHBpbFE&resourcekey=0-Y2p8GIeC0xt8zbzHusHXfg" width="240" alt="1983 - M490L - 490-01-012 - TIMER RESET OFF TALLY OFFISTOP FADER.jpg"></a><br><sub>1983|16 · 490-01-012 - TIMER RESET OFF TALLY OFFISTOP FADER · <a href="SCHEMATICS/1983%20-%20M490L%20-%20490-01-012%20-%20TIMER%20RESET%20OFF%20TALLY%20OFFISTOP%20FADER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY0tRSjFoMmZxWjQ/view?resourcekey=0-nIRxYyhLdOMyWMdR6wlQ4g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY0tRSjFoMmZxWjQ&resourcekey=0-nIRxYyhLdOMyWMdR6wlQ4g" width="240" alt="1983 - M490L - 490-02-010 - EXT RIOO RIOZ.jpg"></a><br><sub>1983|16 · 490-02-010 - EXT RIOO RIOZ · <a href="SCHEMATICS/1983%20-%20M490L%20-%20490-02-010%20-%20EXT%20RIOO%20RIOZ%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb3N4YVFocTVlZDA/view?resourcekey=0-zwpSuzGE2PlFU_RTosxGOA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb3N4YVFocTVlZDA&resourcekey=0-zwpSuzGE2PlFU_RTosxGOA" width="240" alt="1983 - M490L - 490-02-010 - MIXIEA BUSES RIGHT CMANNIL.jpg"></a><br><sub>1983|16 · 490-02-010 - MIXIEA BUSES RIGHT CMANNIL · <a href="SCHEMATICS/1983%20-%20M490L%20-%20490-02-010%20-%20MIXIEA%20BUSES%20RIGHT%20CMANNIL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSDhvZ09nbFZ6d0U/view?resourcekey=0-1AfiToP2AOU27YVOIa-iLA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSDhvZ09nbFZ6d0U&resourcekey=0-1AfiToP2AOU27YVOIa-iLA" width="240" alt="1983 - M490L - 490-06-020.jpg"></a><br><sub>1983|16 · 490-06-020 · <a href="SCHEMATICS/1983%20-%20M490L%20-%20490-06-020%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMThqRGNjeUQ3N2M/view?resourcekey=0-Z7arOC6xG23n4xu1dgmU3g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMThqRGNjeUQ3N2M&resourcekey=0-Z7arOC6xG23n4xu1dgmU3g" width="240" alt="1983 - M490L - 7-112-02-002 - AND ALL CAPACITORS.jpg"></a><br><sub>1983|16 · 7-112-02-002 - AND ALL CAPACITORS · <a href="SCHEMATICS/1983%20-%20M490L%20-%207-112-02-002%20-%20AND%20ALL%20CAPACITORS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcnUxU1ZFYWtUWmc/view?resourcekey=0-dRs4Md8jGJVG4f5TTj9hVw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcnUxU1ZFYWtUWmc&resourcekey=0-dRs4Md8jGJVG4f5TTj9hVw" width="240" alt="1983 - M490L - 7-112-06-002 - COMPONENT SIDE NQIE COMPONENTS.jpg"></a><br><sub>1983|16 · 7-112-06-002 - COMPONENT SIDE NQIE COMPONENTS · <a href="SCHEMATICS/1983%20-%20M490L%20-%207-112-06-002%20-%20COMPONENT%20SIDE%20NQIE%20COMPONENTS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYUphNzBaMjM1ZTA/view?resourcekey=0-nAuyvMu5CcBu5cDk_l8_9Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYUphNzBaMjM1ZTA&resourcekey=0-nAuyvMu5CcBu5cDk_l8_9Q" width="240" alt="1983 - M490L - 7-112-06-002 - ENT SIDE ISSU.jpg"></a><br><sub>1983|16 · 7-112-06-002 - ENT SIDE ISSU · <a href="SCHEMATICS/1983%20-%20M490L%20-%207-112-06-002%20-%20ENT%20SIDE%20ISSU%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUXhBN25qTXFSdkE/view?resourcekey=0-nkkY_X92LEbgULC0KiuYJA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUXhBN25qTXFSdkE&resourcekey=0-nkkY_X92LEbgULC0KiuYJA" width="240" alt="1983 - M490L - 90-06-020 - STEREO INIPUT MODULE COMPONENT LAYOUT.jpg"></a><br><sub>1983|16 · 90-06-020 - STEREO INIPUT MODULE COMPONENT LAYOUT · <a href="SCHEMATICS/1983%20-%20M490L%20-%2090-06-020%20-%20STEREO%20INIPUT%20MODULE%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

## RTO-144 pinout

20 contacts (P1), 22 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | LEFT PGRM 1 | audio | A3 + | high |
| 1 | MIC IN A | in | A1 + | high |
| 2 | LEFT PGRM 1 | audio | A3 - | high |
| 3 | RIGHT PGRM 1 | audio | A4 + | high |
| 3 | MIC IN B | in | A2 + | high |
| 4 | RIGHT PGRM 1 | audio | A4 - | high |
| 4 |  | unread |  | low |
| 6 | INSERT SEND | out | B1 + | high |
| 7 | INSERT RETURN | in | B2 + | high |
| 10 |  | unread |  | low |
| 17 |  | unread |  | low |
| 19 | -25 V | power |  | high |
| 20 | POST DIRECT OUTPUT | out |  | low |
| 20 | COMMON | ground |  | high |
| 21 | +25 V | power |  | high |
| 22 | 2 CTL | control |  | low |
| A | MIC IN A | in | A1 - | high |
| C | MIC IN B | in | A2 - | high |
| F | INSERT SEND | out | B1 - | high |
| H | INSERT RETURN | in | B2 - | high |
| L |  | unread |  | low |
| M |  | unread |  | low |
| R |  | unread |  | low |
| V |  | unread |  | low |

**Straps:** Insert: JMP.6.7 · Insert: JMP.F.H

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZE8xRTVNT0c1TjA/view?resourcekey=0-nrH7um5SjVLUiSDS5-IewA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZE8xRTVNT0c1TjA&resourcekey=0-nrH7um5SjVLUiSDS5-IewA" width="240" alt="1983 - M490L - P001 - Title Page.jpg"></a><br><sub>1983|16 · P001 - Title Page</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWDk1XzF2MDJJLWs/view?resourcekey=0-ef2VPwFepfqwojFAWk8o4A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWDk1XzF2MDJJLWs&resourcekey=0-ef2VPwFepfqwojFAWk8o4A" width="240" alt="1983 - M490L - P002.jpg"></a><br><sub>1983|16 · P002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLTNmajJmVnUxek0/view?resourcekey=0-epZMoM0gpuKXlTeclcbtQw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLTNmajJmVnUxek0&resourcekey=0-epZMoM0gpuKXlTeclcbtQw" width="240" alt="1983 - M490L - P003 - 1-1.jpg"></a><br><sub>1983|16 · P003 - 1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdjYxRGFWTTlLemM/view?resourcekey=0-Xfj38m0AyborljK-aGFIjg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdjYxRGFWTTlLemM&resourcekey=0-Xfj38m0AyborljK-aGFIjg" width="240" alt="1983 - M490L - P004 - 1-2.jpg"></a><br><sub>1983|16 · P004 - 1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUklBZ1ZtUGhKNGs/view?resourcekey=0-kQLUBnaoUoQ56AvSK1ztIA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUklBZ1ZtUGhKNGs&resourcekey=0-kQLUBnaoUoQ56AvSK1ztIA" width="240" alt="1983 - M490L - P005 - 2-1.jpg"></a><br><sub>1983|16 · P005 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdWZUNFZ1ek1wVVk/view?resourcekey=0-KUCg6y3Dk3Vo7nENgRQInQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdWZUNFZ1ek1wVVk&resourcekey=0-KUCg6y3Dk3Vo7nENgRQInQ" width="240" alt="1983 - M490L - P006 - 2-2.jpg"></a><br><sub>1983|16 · P006 - 2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMDhKWEhjRnpneEk/view?resourcekey=0-HxTUFI3IW3R2XUq4Xyg2jg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMDhKWEhjRnpneEk&resourcekey=0-HxTUFI3IW3R2XUq4Xyg2jg" width="240" alt="1983 - M490L - P007 - 2-3.jpg"></a><br><sub>1983|16 · P007 - 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKejByZXFPSlA5NG8/view?resourcekey=0-o-vpa-zKjuGEyK7s5BBvnQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKejByZXFPSlA5NG8&resourcekey=0-o-vpa-zKjuGEyK7s5BBvnQ" width="240" alt="1983 - M490L - P008 - 2-4.jpg"></a><br><sub>1983|16 · P008 - 2-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOVphZ19NX29OUWc/view?resourcekey=0-IdEuEI8Bbx6Zgj4tw6zcHw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOVphZ19NX29OUWc&resourcekey=0-IdEuEI8Bbx6Zgj4tw6zcHw" width="240" alt="1983 - M490L - P009 - 2-5.jpg"></a><br><sub>1983|16 · P009 - 2-5</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR3o0ZFJGMFdEU0k/view?resourcekey=0-ZnGutD62ri1UtlJkG7NHJQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR3o0ZFJGMFdEU0k&resourcekey=0-ZnGutD62ri1UtlJkG7NHJQ" width="240" alt="1983 - M490L - P010 - 2-6.jpg"></a><br><sub>1983|16 · P010 - 2-6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdEtEU3Q5cGlnX1E/view?resourcekey=0-4qq67fedJ62xp0dE_fRWxg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdEtEU3Q5cGlnX1E&resourcekey=0-4qq67fedJ62xp0dE_fRWxg" width="240" alt="1983 - M490L - P011 - 3-1.jpg"></a><br><sub>1983|16 · P011 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKclNhazZXZ2hSUms/view?resourcekey=0-cw0uIm-q8PYtaALjYJJf3A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKclNhazZXZ2hSUms&resourcekey=0-cw0uIm-q8PYtaALjYJJf3A" width="240" alt="1983 - M490L - P012 - 3-2.jpg"></a><br><sub>1983|16 · P012 - 3-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc0lFekJoa0hEblk/view?resourcekey=0-4EWaAWNj1NcFbruKcL9c_g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc0lFekJoa0hEblk&resourcekey=0-4EWaAWNj1NcFbruKcL9c_g" width="240" alt="1983 - M490L - P013 - 3-3.jpg"></a><br><sub>1983|16 · P013 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLUUycGlRMzBOQmM/view?resourcekey=0-Ec92meidg9bI4pdeQ4ShTQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLUUycGlRMzBOQmM&resourcekey=0-Ec92meidg9bI4pdeQ4ShTQ" width="240" alt="1983 - M490L - P014 - 3-4.jpg"></a><br><sub>1983|16 · P014 - 3-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZnFqaDk2QWhnUHc/view?resourcekey=0-F1SVTbiuDmMG7e25DWAQQQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZnFqaDk2QWhnUHc&resourcekey=0-F1SVTbiuDmMG7e25DWAQQQ" width="240" alt="1983 - M490L - P015 - 3-5.jpg"></a><br><sub>1983|16 · P015 - 3-5</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVll1R0VCZXZyejQ/view?resourcekey=0-9oSv5fZ-E47XShxHC_0_cg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVll1R0VCZXZyejQ&resourcekey=0-9oSv5fZ-E47XShxHC_0_cg" width="240" alt="1983 - M490L - P016 - 3-6.jpg"></a><br><sub>1983|16 · P016 - 3-6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMTd2YVczamFoQWM/view?resourcekey=0-y3uR4aBBurBsczoeOGBlJg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMTd2YVczamFoQWM&resourcekey=0-y3uR4aBBurBsczoeOGBlJg" width="240" alt="1983 - M490L - P017 - 3-7.jpg"></a><br><sub>1983|16 · P017 - 3-7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbnc4eWdnUDlCOXc/view?resourcekey=0-Yy7L0bICPh7gbSuI-xIA2g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbnc4eWdnUDlCOXc&resourcekey=0-Yy7L0bICPh7gbSuI-xIA2g" width="240" alt="1983 - M490L - P018 - 3-8.jpg"></a><br><sub>1983|16 · P018 - 3-8</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSVdQR0xqMzhqQW8/view?resourcekey=0-Y02pbP0ZcnkfkYqLrIphQw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSVdQR0xqMzhqQW8&resourcekey=0-Y02pbP0ZcnkfkYqLrIphQw" width="240" alt="1983 - M490L - P019 - 3-9.jpg"></a><br><sub>1983|16 · P019 - 3-9</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM2Z1aUhYdzBuenc/view?resourcekey=0--uI9ay6bfzgWrEHKIMaP4g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM2Z1aUhYdzBuenc&resourcekey=0--uI9ay6bfzgWrEHKIMaP4g" width="240" alt="1983 - M490L - P020 - 4-1.jpg"></a><br><sub>1983|16 · P020 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX0FpWWR1NEl2Qlk/view?resourcekey=0-u1rFkcgdfn30WFzx0a6nLw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX0FpWWR1NEl2Qlk&resourcekey=0-u1rFkcgdfn30WFzx0a6nLw" width="240" alt="1983 - M490L - P021 - 4-2.jpg"></a><br><sub>1983|16 · P021 - 4-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd0F0WXkwYXk4REE/view?resourcekey=0-JVSYK4Y_JF2LhQvjxOAs5g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd0F0WXkwYXk4REE&resourcekey=0-JVSYK4Y_JF2LhQvjxOAs5g" width="240" alt="1983 - M490L - P022 - CD4016.jpg"></a><br><sub>1983|16 · P022 - CD4016</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc2xtemRnNGdWVFk/view?resourcekey=0-6_FAhExcbRSEW8ysscGMYQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc2xtemRnNGdWVFk&resourcekey=0-6_FAhExcbRSEW8ysscGMYQ" width="240" alt="1983 - M490L - P023 - 74C76.jpg"></a><br><sub>1983|16 · P023 - 74C76</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbi1aZTF1TUdOY0E/view?resourcekey=0-kRjVCzauA_CQ0FkoHkDfyA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbi1aZTF1TUdOY0E&resourcekey=0-kRjVCzauA_CQ0FkoHkDfyA" width="240" alt="1983 - M490L - P024 - 74C221.jpg"></a><br><sub>1983|16 · P024 - 74C221</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaEw2ZFpuYlV1RGM/view?resourcekey=0-qa5tRDn9AQQMFS6XtiVeRg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaEw2ZFpuYlV1RGM&resourcekey=0-qa5tRDn9AQQMFS6XtiVeRg" width="240" alt="1983 - M490L - P025 - 7-112.jpg"></a><br><sub>1983|16 · P025 - 7-112</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX2FIdnQ2WlE5M1U/view?resourcekey=0-C-5qd2NI744LAcheOL9NHQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX2FIdnQ2WlE5M1U&resourcekey=0-C-5qd2NI744LAcheOL9NHQ" width="240" alt="1983 - M490L - P026 - 7-112 - 1-1.jpg"></a><br><sub>1983|16 · P026 - 7-112 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYU5FNG9UNzVjS0U/view?resourcekey=0-JQ4LGP5Q0ovfUNR5NLYNqA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYU5FNG9UNzVjS0U&resourcekey=0-JQ4LGP5Q0ovfUNR5NLYNqA" width="240" alt="1983 - M490L - P027 - 7-112 - 1-2.jpg"></a><br><sub>1983|16 · P027 - 7-112 - 1-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd3lYcXNmNHJGcTQ/view?resourcekey=0-RGXZUj4h-btqNu2Kf1a96Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd3lYcXNmNHJGcTQ&resourcekey=0-RGXZUj4h-btqNu2Kf1a96Q" width="240" alt="1983 - M490L - P028 - 7-112 - 1-3.jpg"></a><br><sub>1983|16 · P028 - 7-112 - 1-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVGYzakxzSmoxRmM/view?resourcekey=0-4zICCSHweyXfp4mu2RaA7Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVGYzakxzSmoxRmM&resourcekey=0-4zICCSHweyXfp4mu2RaA7Q" width="240" alt="1983 - M490L - P029 - 7-112 - 1-4.jpg"></a><br><sub>1983|16 · P029 - 7-112 - 1-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTVZWUHVFUmlSd0k/view?resourcekey=0-sAObe_AnRWnBqikTYy3oMA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTVZWUHVFUmlSd0k&resourcekey=0-sAObe_AnRWnBqikTYy3oMA" width="240" alt="1983 - M490L - Stereo Input Module (2).pdf"></a><br><sub>1983|16 · Stereo Input Module (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdXVEa1BmTWtoQjA/view?resourcekey=0-fknmpzDDNiHRjbg0JFQjwQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdXVEa1BmTWtoQjA&resourcekey=0-fknmpzDDNiHRjbg0JFQjwQ" width="240" alt="1983 - M490L - Stereo Input Module.pdf"></a><br><sub>1983|16 · Stereo Input Module</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1983 - 7-112-02-002 - 7-112A CHANNEL AMPLIFIER SCHEMATIC - DRN TR - ENG TR - ISS 1.kicad_sch](KICAD/1983%20-%207-112-02-002%20-%207-112A%20CHANNEL%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20TR%20-%20ENG%20TR%20-%20ISS%201.kicad_sch)
- [1983 - M490L - 12-02-002 - CONTROL CIB RJI LOOP.kicad_sch](KICAD/1983%20-%20M490L%20-%2012-02-002%20-%20CONTROL%20CIB%20RJI%20LOOP.kicad_sch)
- [1983 - M490L - 490-01-012 - ENG SCRTLBERT STEREO INPUT MODULE.kicad_sch](KICAD/1983%20-%20M490L%20-%20490-01-012%20-%20ENG%20SCRTLBERT%20STEREO%20INPUT%20MODULE.kicad_sch)
- [1983 - M490L - 490-01-012 - TIMER RESET OFF TALLY OFFISTOP FADER.kicad_sch](KICAD/1983%20-%20M490L%20-%20490-01-012%20-%20TIMER%20RESET%20OFF%20TALLY%20OFFISTOP%20FADER.kicad_sch)
- [1983 - M490L - 490-02-010 - EXT RIOO RIOZ.kicad_sch](KICAD/1983%20-%20M490L%20-%20490-02-010%20-%20EXT%20RIOO%20RIOZ.kicad_sch)
- [1983 - M490L - 490-02-010 - MIXIEA BUSES RIGHT CMANNIL.kicad_sch](KICAD/1983%20-%20M490L%20-%20490-02-010%20-%20MIXIEA%20BUSES%20RIGHT%20CMANNIL.kicad_sch)
- [1983 - M490L - 7-112-02-002 - AND ALL CAPACITORS.kicad_sch](KICAD/1983%20-%20M490L%20-%207-112-02-002%20-%20AND%20ALL%20CAPACITORS.kicad_sch)
- [M490L.kicad_sym](KICAD/M490L.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
