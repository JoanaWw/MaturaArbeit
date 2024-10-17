<script lang="ts">
    import { Image } from '@smui/image-list';
    
    export let src: string;
    export let before = true;
</script>

<div class="txt_image_container">
    {#if before}    
        <Image src={src} alt=""/>
    {/if}
    <div class="label">
        <slot/>
    </div>
    {#if !before}    
        <Image src={src} alt=""/>
    {/if}
</div>