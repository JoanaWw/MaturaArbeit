<script lang="ts">
    import Tab, { Label } from '@smui/tab';
    import TabBar from '@smui/tab-bar';
    import TopBar from './TopBar.svelte';
    import Card, { Content } from '@smui/card';

    import ConsumerGoods from '$lib/tabs/military_firedepartment.svelte';
    import DrinkingWater from '$lib/tabs/drinking-water.svelte';
    import Fish from '$lib/tabs/fish.svelte';
    import Human from '$lib/tabs/human.svelte';
    import Processors from '$lib/tabs/processors.svelte';
    import SewageTreatmentPlant from '$lib/tabs/sewage-treatment-plant.svelte';
    
    import './app.css';
    let tabs = [
        "Feuerwehr und Militär",
        "Trinkwasser",
        "Fisch",
        "Mensch",
        "Verarbeiter",
        "Kläranlagen"
    ]
    let active = tabs[0];

    const water_to_human = () => active = tabs[3];
    const forest_to_human = () => active = tabs[3];
    const processor_to_water = () => active = tabs[4];
    const human = () => active = tabs[3];
    const processor = () => active = tabs[4]
    const fish = () => active = tabs[2];
    const military_and_firedepartment = () => active = tabs[0];
    const sewage_treatment_plant = () => active = tabs[5];
</script>


<TopBar prev={false}/>
<main>
    <Card>
    <Content>
        <h1>Joanas matur 2024 </h1>
    </Content>
    <Content>
    </Content>
    <Content>
        <!-- svelte-ignore a11y-missing-attribute -->
        <img src="model.svg"/>
        <svg class="overlay" viewBox="300 0 1244 863">
            <!-- svelte-ignore a11y-click-events-have-key-events -->
            <!-- svelte-ignore a11y-no-static-element-interactions -->
            <path
                style="fill:none;fill-opacity:0;stroke:#ff0000;stroke-width:20;stroke-dasharray:none;stroke-opacity:0;marker-end:url(#marker134044)"
                d="m 420.46123,564.67862 c -0.14061,-45.54169 -0.28122,-91.08438 67.87622,-115.81814 68.15744,-24.73376 204.60649,-28.6574 341.05731,-32.58109"
                class="clickable"
                id="water_to_human"
                on:click={water_to_human}
                on:touchstart={water_to_human}
            />
            <!-- svelte-ignore a11y-click-events-have-key-events -->
            <!-- svelte-ignore a11y-no-static-element-interactions -->
            <path
                style="fill:none;fill-opacity:0;stroke:#ff0000;stroke-width:10;stroke-dasharray:none;stroke-opacity:0;marker-end:url(#marker134044)"
                d="m 886.82248,681.22985 c -49.36205,-47.03146 -98.72415,-94.06297 -117.34197,-135.70039 -18.61783,-41.63742 -6.48867,-77.87717 8.19271,-96.90754 14.68137,-19.03037 31.91328,-20.85009 49.14526,-22.66981"
                class="clickable"
                id="forest_to_human"
                on:click={forest_to_human}
                on:touchstart={forest_to_human}
            />
            <!-- svelte-ignore a11y-click-events-have-key-events -->
            <!-- svelte-ignore a11y-no-static-element-interactions -->
            <path
                style="fill:none;fill-opacity:0;stroke:#ff0000;stroke-width:10;stroke-dasharray:none;stroke-opacity:0;marker-end:url(#marker130371)"
                d="m 826.63978,529.13354 c -76.61595,7.6783 -153.23279,15.3567 -229.85053,23.03518"
                class="clickable"
                id="processor_to_water"
                on:click={processor_to_water}
                on:touchstart={processor_to_water}
            />

            <!-- svelte-ignore a11y-click-events-have-key-events -->
            <!-- svelte-ignore a11y-no-static-element-interactions -->
            <rect
                style="fill:#00000000;stroke:#00000000;stroke-width:15.1181"
                id="human"
                class="clickable"
                on:click={human}
                on:touchstart={human}
                width="32.204346"
                height="78.099731"
                x="838.36597"
                y="370.29102" 
            />
            <!-- svelte-ignore a11y-click-events-have-key-events -->
            <!-- svelte-ignore a11y-no-static-element-interactions -->
            <path
                style="fill:#00000000"
                d="m 824.84202,525.56465 35.71979,20.95472 5.79898,-3.6355 5.92786,3.39499 6.31007,-3.31706 0.11104,-28.01584 -3.35104,-29.46639 -4.91685,0.029 -0.12383,16.64688 c 0,0 -26.53265,-14.5447 -26.92692,-14.45631 -0.39426,0.0884 -18.72737,10.49787 -18.72737,10.49787 z"
                id="processor"
                class="clickable"
                on:click={processor}
                on:touchstart={processor}
            />
            <!-- svelte-ignore a11y-click-events-have-key-events -->
            <!-- svelte-ignore a11y-no-static-element-interactions -->
            <path
                style="fill:#00000000"
                d="m 982.38225,607.59055 35.71985,20.95472 5.7989,-3.6355 5.9279,3.39499 6.3101,-3.31706 0.111,-28.01584 -3.351,-29.46639 -4.9169,0.029 -0.1238,16.64688 c 0,0 -26.5327,-14.5447 -26.9269,-14.45631 -0.3943,0.0884 -18.72742,10.49787 -18.72742,10.49787 z"
                id="processor2"
                class="clickable"
                on:click={processor}
                on:touchstart={processor}
            />
            <!-- svelte-ignore a11y-click-events-have-key-events -->
            <!-- svelte-ignore a11y-no-static-element-interactions -->
            <rect
                style="fill:#ffff0000"
                id="fish"
                class="clickable"
                on:click={fish}
                on:touchstart={fish}
                width="72.493721"
                height="33.40976"
                x="391.68744"
                y="564.15155" 
            />
            <!-- svelte-ignore a11y-click-events-have-key-events -->
            <!-- svelte-ignore a11y-no-static-element-interactions -->
            <rect
                style="fill:#00000000"
                width="123.22112"
                height="64.831062"
                x="477.75085"
                y="355.91772"
                id="militaryAndFiredepartment"
                class="clickable"
                on:click={military_and_firedepartment}
                on:touchstart={military_and_firedepartment}
            />
            <!-- svelte-ignore a11y-click-events-have-key-events -->
            <!-- svelte-ignore a11y-no-static-element-interactions -->
            <path
                style="fill:#00000000"
                d="m 1273.6195,556.78568 112.0425,65.50755 86.2868,-48.52076 -21.1576,-31.79972 -82.9153,-39.76528 -69.3095,15.1548 z"
                id="sewage_treatment_plant"
                class="clickable"
                on:click={sewage_treatment_plant}
                on:touchstart={sewage_treatment_plant}
            />
        </svg>
    </Content>
    <Content>
        <TabBar tabs={tabs} let:tab bind:active>
            <Tab {tab}>
              <Label>{tab}</Label>
            </Tab>
        </TabBar>
        {#if active === tabs[0]}
            <ConsumerGoods />
        {:else if active === tabs[1]}
            <DrinkingWater />
        {:else if active === tabs[2]}
            <Fish />
        {:else if active === tabs[3]}
            <Human />
        {:else if active === tabs[4]}
            <Processors />
        {:else if active === tabs[5]}
            <SewageTreatmentPlant />
        {/if}
    </Content>
</Card>
</main>
