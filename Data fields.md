<b>LimesLimits sites.txt</b>
<table>
<tr>
  <td><i>LimesLimits_ID</i></td>
  <td>unique site identifier</td>
  <td>LONG INTEGER</td>
</tr>
<tr>
  <td><i>obsolete</i></td>
  <td>obsolete site number, kept for purposes of comparison</td>
  <td>BOOLEAN</td>
</tr>
<tr>
  <td><i>X_coordinate</i></td>
  <td>x-coordinate in meters RD New (EPSG:28922)</td>
  <td>LONG INTEGER</td>
</tr>
<tr>
  <td><i>Y_coordinate</i></td>
  <td>Y-coordinate in meters RD New (EPSG:28922)</td>
  <td>LONG INTEGER</td>
</tr>
<tr>
  <td><i>Place</i></td>
  <td>placename</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>Toponym</i></td>
  <td>toponym</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>Site_type</i></td>
  <td>site type; multiple types separated by ";"</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>Uncertain</i></td>
  <td>site of uncertain dating / type / location</td>
  <td>BOOLEAN</td>
</tr>
<tr>
  <td><i>Start_period</i></td>
  <td>estimated starting period (ARCHIS2 code)</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>End_period</i></td>
  <td>estimated end period (ARCHIS2 code)</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>Size</i></td>
  <td>estimated size</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>Conservation</i></td>
  <td>state of conservation</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>Notes</i></td>
  <td>notes</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>checked</i></td>
  <td>site checked and approved</td>
  <td>BOOLEAN</td>
</tr>
<tr>
  <td><i>location_note</i></td>
  <td>note on location</td>
  <td>TEXT</td>
</tr>
</table>

<b>LimesLimits finds.txt</b>

<table>
<tr>
  <td><i>CORRECTION</i></td>
  <td>observation was modified compared to ARCHIS2</td>
  <td>BOOLEAN</td>
</tr>
<tr>
  <td><i>LimesLimits_ID</i></td>
  <td>unique site identifier in text format</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>LimesLimits_ID_NR</i></td>
  <td>unique site identifier in number format</td>
  <td>LONG INTEGER</td>
</tr>
<tr>
  <td><i>WNG_NR</i></td>
  <td>ARCHI2 observation number</td>
  <td>LONG INTEGER</td>
</tr>
<tr>
  <td><i>WNG_NR_TXT</i></td>
  <td>ARCHI2 observation number in text format</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>VONDST_ID</i></td>
  <td>ARCHIS2 find number</td>
  <td>INTEGER</td>
</tr>
<tr>
  <td><i>COMPLEX</i></td>
  <td>ARCHIS2 site type code</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>CULTUUR</i></td>
  <td>ARCHIS2 culture code</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>DIEPTE</i></td>
  <td>depth below ground in cm</td>
  <td>INTEGER</td>
</tr>
<tr>
  <td><i>AANTAL</i></td>
  <td>number of finds (9999 = unknown)</td>
  <td>LONG INTEGER</td>
</tr>
<tr>
  <td><i>TOESTAND</i></td>
  <td>ARCHIS2 state of conservation code</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>MATERIAAL</i></td>
  <td>ARCHIS2 material code</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>ALG_CODE</i></td>
  <td>ARCHIS2 general typology code</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>SPEC_CODE</i></td>
  <td>ARCHIS2 specific typology code</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>BEGIN_PER</i></td>
  <td>ARCHIS2 starting period code</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>EIND_PER</i></td>
  <td>ARCHIS2 end period code</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>TOELICHT</i></td>
  <td>ARCHIS2 supplementary note</td>
  <td>TEXT</td>
</tr>
<tr>
  <td><i>AANTAL-AANGEPAST</i></td>
  <td>modified number of finds (9999 converted to 1)</td>
  <td>LONG INTEGER</td>
</tr>
</table>
