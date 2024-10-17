<script lang="ts">
    import TxtImage from "$lib/txt_image.svelte";
    import Card, {Content} from "@smui/card";
    import List, { Item } from '@smui/list';

    
    export let military_and_firedepartment: () => string;
    export let fish: () => string;
    export let human: () => string;
    export let water: () => string;
    export let ground: () => string;
</script>


    <Card>
        <Content>
            <h1>Niederschlag</h1>
        </Content>
        <div class="divider"/>
        <Content>
            PFOS gelangt auch über Regen und Schnee in die Umwelt. Aus diesem Grund findet man die Substanz auch in Polargebieten und alpinen Seen, 
            die weit entfernt von industriellen Produktionsstätten und menschlichen Siedlungen liegen. Besonders interessant ist in diesem Zusammenhang eine Studie über Regenwasser. 
            Diese zeigt, dass PFOS weltweit im Regenwasser nachgewiesen werden kann.

            <TxtImage src="rain_pfos1.png">
                Die Abbildung zeigt PFOS-Daten, die seit 2010 an verschiedenen Standorten weltweit im Regenwasser gesammelt wurden. 
                Die Schweiz war jedoch nicht Teil dieser Studie. Die beiden gestrichelten Linien geben den Umweltqualitätsstandard der EU 
                (EU-EQC) für PFOS von 0,65 ng/l und den Umweltqualitätsstandard der USA (US EPS Health Advisory) für PFOS von 0,02 ng/l im Oberflächengewässern an. 
                Der Grenzwert für Trinkwasser in der Schweiz liegt bei 0,3 µg/l, d.h. bei 300 ng/l, was im Verhältnis zu den Gesundheitshinweisen der EU und der USA als sehr hoch erscheint. 
                Eine weitere Aufarbeitung dieser Tatsache ist nicht Gegenstand dieser Arbeit.
            </TxtImage>
            
            Wie genau PFOS aus Industrieanlagen in die Luft und Atmosphäre gelangt, ist wissenschaftlich noch nicht im Detail untersucht und nicht Gegenstand dieser Arbeit.
            
            Im Folgenden wird der Verbreitungsweg von PFOS über die folgenden Stationen detailliert beschrieben:

            <List>
                <Item on:SMUI:action={military_and_firedepartment}>Militärstützpunkte & Feuerwehrübungsplätze</Item>
                <Item on:SMUI:action={water}>Gewässer</Item>
                <Item on:SMUI:action={ground}>Böden</Item>
                <Item on:SMUI:action={fish}>Nahrung (Fische)</Item>
                <Item on:SMUI:action={water}>Trinkwasser</Item>
                <Item on:SMUI:action={human}>Mensch</Item>
            </List>
            

        </Content>
    </Card>
