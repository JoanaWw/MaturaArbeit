<script>
    import TopBar from './TopBar.svelte';
    import Card, { Content } from '@smui/card';
    
    import './app.css';
</script>
<style>
#human-button {
    top: 52%;
    left: 44%;
}

#producer-button {
    top: 68%;
    left: 53%;
}

#consumer-goods-button {
    top: 52%;
    left: 55%;
}

#fish-button {
    top: 80%;
    left: 20%;
}

#sewage-button {
    top: 70%;
    left: 81%;
}

#processors-button {
    top: 64%;
    left: 45%;
}

#drinking-water-button {
    top: 80%;
    left: 45%;
}


#groundwater-button {
    top: 80%;
    left: 75%;
}
</style>

<TopBar/>
<main>
    <Card>
    <Content>
        <h1>Joanas matur </h1>
    </Content>
    <Content>
    <div class="container">
        <img src="model.svg" alt="Snow" style="width:100%">
        <a class="btn" id="human-button" href="human">Mensch</a>
        <a class="btn" id="producer-button" href="producer">Hersteller</a>
        <a class="btn" id="consumer-goods-button" href="consumer-goods">Konsumgüter</a>
        <a class="btn" id="fish-button" href="fish">Fisch</a>
        <a class="btn" id="sewage-button" href="sewage-treatment-plant">Kläranlage</a>
        <a class="btn" id="processors-button" href="processors">Verarbeiter</a>
        <a class="btn" id="drinking-water-button" href="drinking-water">Trinkwasser</a>
        <span class="btn" id="groundwater-button">Grundwasser</span>
      </div>
    </Content>
</Card>
</main>
