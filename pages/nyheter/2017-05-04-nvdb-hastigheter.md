Date: 2017-05-04
Categories: nyheter, tiles
Author: Joakim Fors
Description: NVDB hastigheter och cykelvägar som tiles
Summary: NVDB hastigheter och cykelvägar som tiles
Flags: front


# NVDB CC0 data

Nu finns vägar från NVDB tillgängliga som tiles som kan användas i vid redigering. Vägarna är färgade efter hastighet enligt tabellen nedan.

<table>
      <tr>
        <th>Färg</th><th>Hastighet</th>
      </tr>
      <tr>
        <td style="background: rgb(170,253,126);"></td><td>5/gångfartsområde</td>
      </tr>
      <tr>
        <td style="background: rgb(71,252,29);"></td><td>20</td>
      </tr>
      <tr>
        <td style="background: rgb(156,233,255);"></td><td>30</td>
      </tr>
      <tr>
        <td style="background: rgb(38,163,253);"></td><td>40</td>
      </tr>
      <tr>
        <td style="background: rgb(191,176,253);"></td><td>50</td>
      </tr>
      <tr>
        <td style="background: rgb(78,51,252);"></td><td>60</td>
      </tr>
      <tr>
        <td style="background: rgb(255,253,140);"></td><td>70</td>
      </tr>
      <tr>
        <td style="background: rgb(255,253,51);"></td><td>80</td>
      </tr>
      <tr>
        <td style="background: rgb(250,177,111);"></td><td>90</td>
      </tr>
      <tr>
        <td style="background: rgb(248,105,17);"></td><td>100</td>
      </tr>
      <tr>
        <td style="background: rgb(249,131,178);"></td><td>110</td>
      </tr>
      <tr>
        <td style="background: rgb(217,0,39);"></td><td>120</td>
      </tr>
</table>

Alternativ färgsättning

<table>
      <tr>
        <th>Färg</th><th>Hastighet</th>
      </tr>
      <tr>
        <td style="background: rgb(153,0,255);"></td><td>5/gångfartsområde</td>
      </tr>
      <tr>
        <td style="background: rgb(255,255,204);"></td><td>20</td>
      </tr>
      <tr>
        <td style="background: rgb(0,170,0);"></td><td>30</td>
      </tr>
      <tr>
        <td style="background: rgb(238,226,21);"></td><td>40</td>
      </tr>
      <tr>
        <td style="background: rgb(173,218,255);"></td><td>50</td>
      </tr>
      <tr>
        <td style="background: rgb(255,153,0);"></td><td>60</td>
      </tr>
      <tr>
        <td style="background: rgb(102,255,255);"></td><td>70</td>
      </tr>
      <tr>
        <td style="background: rgb(255,0,0);"></td><td>80</td>
      </tr>
      <tr>
        <td style="background: rgb(0,204,204);"></td><td>90</td>
      </tr>
      <tr>
        <td style="background: rgb(153,0,0);"></td><td>100</td>
      </tr>
      <tr>
        <td style="background: rgb(0,102,102);"></td><td>110</td>
      </tr>
      <tr>
        <td style="background: rgb(102,51,0);"></td><td>120</td>
      </tr>
</table>

Även cykelvägar och vissa rutter renderas som blåa streckade linjer.

Aktuell data är från 2017-04-25. Uppdateringar släpps ungefär en gång i månaden. Märkväl att NVDB data inte nödvändigtvis behöver vara korrekt så man ska inte blint lita på uppgifterna.

Adresserna till tilesen är `http://mapproxy.openstreetmap.se/tiles/1.0.0/nvdb_speeds/EPSG3857/{z}/{x}/{y}.png` och `http://mapproxy.openstreetmap.se/tms/1.0.0/nvdb_speeds/EPSG3857/{zoom}/{x}/{-y}.png` för t.ex. JOSM. Kartlagret finns även som overlay på [kartsidan](//maps.openstreetmap.se).

För den alternativa färgsättningen är adresserna `http://mapproxy.openstreetmap.se/tiles/1.0.0/nvdb_speeds_alt/EPSG3857/{z}/{x}/{y}.png` och `http://mapproxy.openstreetmap.se/tms/1.0.0/nvdb_speeds_alt/EPSG3857/{zoom}/{x}/{-y}.png`

