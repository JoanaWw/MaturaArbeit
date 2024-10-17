<script>
    import TxtImage from "$lib/txt_image.svelte";
import Card, {Content} from "@smui/card";
</script>


<Card>
    <Content>
        <h1>Gewässer</h1>
    </Content>
    <div class="divider"/>
    <Content class="main_txt">
        Der Themenkomplex Gewässer ist sehr vielschichtig und weist Überschneidungen mit anderen Kapiteln auf. 
        Trotzdem soll hier ein kurzer Überblick über die Situation in der Schweiz gegeben werden.
        Das Bundesamt für Umwelt (BAFU) hat im Jahr 2021 eine Analyse zu den Chemikalien im Grundwasser und in Oberflächengewässern in der Schweiz durchgeführt.  
        Im Folgenden wird ein kurzer Überblick über diese beiden Gewässer gegeben.

        <h3>Grundwasser</h3>
        Für den Kanton Zürich ergibt sich folgendes Bild:
        Es wurden insgesamt 70 Grundwasserproben auf 26 verschiedene PFAS, darunter PFOS, untersucht.  
        Leider wurden die detaillierten Ergebnisse nicht veröffentlicht und für PFOS allein liegen im Kanton Zürich leider auch keine Messwerte vor. 
        Es kann jedoch festgehalten werden, dass gesamtschweizerisch 13 PFAS im Grundwasser gefunden wurden und das die Konzentration von PFOS am höchsten war.  
        Eine detaillierte graphische Übersicht und weitere Erklärungen für den Kanton Zürich finden sich in der folgenden Abbildung.

        <TxtImage src="groundwater.png">
            Die Abbildung zeigt die PFAS Belastung im Grundwasser im Kanton Zürich.  
            Es wurde einmal eine Belastung &gt0,1 µg/l gemessen (hellgrünes Quadrat). 
            Diese höchste Belastung ist an der Glatt in der Nähe vom Flughafen und einem grossen Militärstützpunkt der Schweizer Armee gemessen worden. 
            Der Wert betrug hier 0,37 µg/l.
        </TxtImage>

        Insgesamt bleibt festzuhalten, dass die gesetzlich vorgeschriebenen Grenzwerte für PFOS, PFOA und PFHxS für Trinkwasser an allen untersuchten Grundwasser-Messstellen im Kanton Zürich eingehalten wurden.  
        Die Werte für die Summe aller gemessenen PFAS bewegten sich zwischen &lt0,001 µg/l und 0,37 µg/l.  
        Der gesetzlich vorgeschriebene Grenzwert für die drei oben genannten PFAS beträgt in der Schweiz 0,3 µg/l je einzelne Chemikalie.
         
        <h3>Oberflächengewässer</h3> 
        Um einen ersten Überblick über die PFAS-Konzentrationen im Kanton Zürich zu erhalten, wurden im Jahr 2021 in zwei Messkampagnen Wasserproben aus 50 grösseren und mittleren Fliessgewässern entnommen.  
        Insgesamt wurden 20 PFAS, darunter auch PFOS, untersucht, wobei die Summe der analysierten PFAS zwischen 0,0005 µg/l und 0,038 µg/l lag.  
        Damit sind die Konzentrationen in Oberflächengewässern generell niedriger als im Grundwasser. 
        Leider gibt es bisher keine wissenschaftlichen Untersuchungen

        <TxtImage src="surfacewater.png">
            Die Abbildung zeigt die PFAS Belastung im Kanton Zürich in Oberflächengewässern.  
            Die gemessenen Werte bewegen sich meist zwischen 0,001 µg/l und 0,1 µg/l. 
            Damit liegen diese Werte über der EU-Wasserrahmenrichtlinie von 0,00065 µg/l. 
        </TxtImage>


        Leider liegen für die Untersuchung im Kanton Zürich keine Daten für PFOS allein vor. 
        Daher wird im Folgenden eine detaillierte Untersuchung im Kanton St. Gallen näher erläutert. 
        <br/><br/>
        Der Kanton St. Gallen hat eine Untersuchung zu PFOS in seinen Fliessgewässern durchgeführt. 
        Im Jahr 2021 wurden 39 Fliessgewässer mit insgesamt 45 Messstellen detailliert untersucht.   
        An jeder Messstelle wurde zweimal gemessen, so dass insgesamt 90 Messdaten zur Verfügung standen.  
        Bei 30% aller Messungen wurde PFOS nachgewiesen.<br/><br/> 

        Die folgende Abbildung zeigt die Probenahme von PFOS in der Gemeinde Eggersriet.
        <TxtImage src="surfacewater2.png">
            Probeentnahme für PFOS im Boden, Fliessgewässer und Grundwasser in Eggersriet.
            Die Konzentrationswerte im Fliessgewässer und Grundwasser sind in ng/l angegeben. 
            Aus Datenschutzgründen sind die Konzentrationen in den Bodenproben nicht angegeben. 
        </TxtImage>

        Im Folgenden wird die oben abgebildete Karte der PFOS-Belastung in der Gemeinde Eggersriet näher beschrieben. 
        Insbesondere wurden die gemessenen PFOS-Belastungen im Grundwasser und in den Fliessgewässern analysiert. 
        Dazu wurde folgende Abbildung und Tabelle erstellt.<br/><br/>

        <TxtImage src="surfacewater3.png">
            Eigene Darstellung der Anzahl der Wasserproben für Grund- und Fliessgewässer in der Gemeinde Eggersriet. 
            Insgesamt wurden 11 Wasserproben aus dem Grundwasser und 22 Wasserproben aus den Fliessgewässern entnommen. 
            In der Abbildung sind die Wasserproben nach ihrer PFOS-Konzentration geordnet. 
            Grundwasserprobe 1 hat eine PFOS-Konzentration von 1371 ng/l, Fliessgewässerprobe 1 hat eine PFOS-Konzentration von 689 ng/l usw.
        </TxtImage>

        Diese gemessenen PFOS-Konzentrationen bilden die Grundlage für weitere Berechnungen in untensthenden Tabelle. 
        Insbesondere wurden die Anzahl Wasserproben über dem Grenzwert für Schweizer Trinkwasser sowie der arithmetische Mittelwert berechnet.
        
        <TxtImage src="surfacewater4.png" before={false}>
            Insgesamt wurden 11 Grundwasserproben entnommen, von denen 64% (7 Wasserproben) eine PFOS-Konzentration über dem in der Schweiz geltenden Grenzwert für Trinkwasser von 300 ng/l aufweisen. 
            Der arithmetische Mittelwert beträgt 652 ng/l. Die Werte für Fliessgewässer sind analog zu lesen. 
            Auch bei den Fliessgewässern wurde der gesetzliche Grenzwert für Trinkwasser zum Vergleich herangezogen, da der Wert der EU-Wasserrahmenrichtlinie in allen Wasserproben überschritten wurde.
        </TxtImage>

    Insgesamt ist die Anzahl der Wasserproben sehr gering. Es ist sehr schwierig, auf dieser Datenbasis allgemeingültige Aussagen zu machen. 
    Festzuhalten ist jedoch, dass in Eggersriet im Kanton St. Gallen eine nicht unerhebliche PFOS-Konzentration vorliegt. 
    Weitere Abklärungen im Kanton St. Gallen sind im Gange.
    Ein Vergleich mit Ronneby ist schwierig, da dort die PFOS-Konzentration im Trinkwasser und im Blut gemessen wurde und nicht im Grundwasser und in den Fliessgewässer. 
    Daher ist ein direkter Vergleich etwas schwierig. 
    Dennoch kann die PFOS-Konzentration im Trinkwasser von Brantafors von 8000 ng/l mit den beiden arithmetischen Mittelwerten von 652 ng/l und 268 ng/l verglichen werden. 
    Die PFOS-Konzentration in Ronneby war um ein Vielfaches höher.
    Eine detailliertere Übersicht über den PFOS-Gehalt in den Fliessgewässern ist im Kapitel Fisch dargestellt. 
    Es bleibt festzuhalten, dass auch nach Jahren der starken Einschränkung von PFOS die Chemikalie in Grund- und Fliessgewässern nachgewiesen werden kann.

    </Content>
</Card>