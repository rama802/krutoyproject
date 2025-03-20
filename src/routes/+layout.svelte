<script lang="ts">
	import Heder from '$lib/components/Heder.svelte';
import {Container,Stules} from '@svelte'
const {children} = $props();
</script>
<Stules>
    <Container>
        </Heder>
            {@render children()}
       
    </Container>


