<script lang="ts">
    import { Image } from '@smui/image-list';
    
    export let src: string;
</script>

<div class="txt_image_container">
    <Image src={src} alt=""/>
    <div class="label">
        <slot/>
    </div>
</div>