<script>
    import TxtImage from "$lib/txt_image.svelte";
import Card, {Content} from "@smui/card";
</script>


<Card>
    <Content>
        <h1>Böden</h1>
    </Content>
    <div class="divider"/>
    <Content>
        Im Auftrag des Bundesamtes für Umwelt und der Nationalen Bodenbeobachtung hat die Zürcher Hochschule für Angewandte Wissenschaften (ZHAW) im Jahr 2021 erstmals systematisch die PFAS-Verbindungen in Schweizer Böden untersucht und bewertet.  
        Dazu wurden insgesamt 146 Oberbodenproben aus drei verschiedenen Messkampagnen zusammengeführt.  
        Die untersuchten Bodenproben verteilen sich über die ganze Schweiz und es wurde keine Fokussierung auf potenziell belastete Standorte wie z.B. Feuerwehrübungsplätze vorgenommen.  
        Die Auswahl repräsentiert verschiedene Regionen, Nutzungsarten und Klimazonen.  Nutzungsarten sind z.B. Garten, Urban, Grasland/ Wald, Ackerbau oder alpiner Standort.  
        Die folgende Abbildung zeigt die Verteilung der PFAS-32-Konzentration in Schweizer Böden. 
        Die PFAS-32-Konzentration ist die Summe von 32 verschiedenen PFAS, einschliesslich PFOS.   

        <TxtImage src="ground1.png">
            Die Abbildung zeigt die Verteilung der 146 Bodenproben in der Schweiz. 
            Untersucht wurde die Summe von 32 verschiedenen PFAS-Substanzen, darunter PFOS.  
            Die Bestimmungsgrenze (BG) für die Summe der 32 PFAS lag bei 0,02 µg/kg Trockensubstanz.  
            Die Bodenproben wurden bei 40 Grad getrocknet und anschliessend gesiebt.  
            Dies ergab die untersuchte Trockensubstanz. Die BG wurde von der Projektgruppe festgelegt. 
            Gemessene Konzentrationen über der BG wurden in die Graphik aufgenommen. 
            Dunkelgrün markiert sind demnach Standorte mit einer Summenkonzentration zwischen 0,02 µg/kg und 0,96 µg/kg Boden-Trockensubstanz. 
            Für Böden gibt es bisher keine (gesetzlichen) Grenzwerte. 
            Daher wird in der Graphik einfach die gemessene Konzentration aufgeführt. 
            Leider liegen keine separaten Daten für Zürich vor.
        </TxtImage>

        Ein wesentliches Ergebnis dieser Untersuchung ist, dass PFOS in allen 146 Bodenproben gefunden wurde.  
        Häufig dominierte PFOS die Summe der 32 PFAS.  
        Somit sind auch alpine und abgelegene Regionen mit PFOS belastet und es muss davon ausgegangen werden, dass PFOS in den Böden der ganzen Schweiz verbreitet ist.
        Dies wird durch eine Untersuchung im Kanton St. Gallen bestätigt. 
        Im Kanton St. Gallen wurden PFOS-Chemikalien im Fleisch von Kühen nachgewiesen, die auf PFOS-belasteten Weiden grasten.  
        Leider sind keine detaillierten Werte oder Details zur Konzentration im Boden an den untersuchten Standorten veröffentlicht. 
        Das Fleisch der Kühe weist aber eine 40-mal so hohe Konzentration auf als gesetzlich zugelassen.  
        Der gesetzliche Grenzwert für Rindfleisch liegt bei 0,3 µg/kg Frischgewicht. 
        Es wird vermutet, dass die PFAS-Belastung aus Klärschlamm stammt, der bis 2006 als Dünger verwendet werden durfte.  
        Es ist eine wichtige Erkenntnis, dass Böden mit PFOS belastet sind. Böden spielen sicherlich eine wichtige Rolle bei der Verbreitung von PFOS. 
        Aus den Böden gelangen die Stoffe in die Gewässer und ins Grundwasser. 
        Es wird vermutet, dass Tiere und Pflanzen, die auf dem Boden weiden und wachsen, PFOS aufnehmen können. 
        Diese Vermutung wird an der ZHAW in einem laufenden Projekt untersucht. 
        Das Projekt trägt den Titel „Untersuchung des Transfers von Per- und Polyfluoralkylverbindungen (PFAS) aus dem Boden in Nahrungs- und Futterpflanzen und tierische Lebensmittel».  
        Ergebnisse liegen noch nicht vor und werden für 2025 erwartet. 
        Am Ende der Nahrungskette könnte dann der Mensch die Chemikalie PFOS über das Trinkwasser und die Nahrung aufnehmen. 
        Im nächsten Schritt wird daher in dieser Arbeit untersucht, ob auch die menschliche Nahrung und das Trinkwasser mit PFOS belastet sind.

    </Content>
</Card>
