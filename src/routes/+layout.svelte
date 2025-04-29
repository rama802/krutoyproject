<script lang="ts">
	import Heder from '$lib/components/Heder.svelte';
import {Container,Styles} from '@sveltestrap/sveltestrap'
const {children} = $props();
</script>
<Styles/>
    <Container>
        <Heder/>
            {@render children()}
       
    </Container>


