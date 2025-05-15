<script lang="ts">
	import { Container, ListGroup, ListGroupItem,Image } from "@sveltestrap/sveltestrap";

</script>

<svelte:head>
    <title>Наши контакты</title>
</svelte:head>

<Container>
<h1>Наши контакты</h1>
<Image class="w-100" src="https://sharing.vedomosti.ru/1534711911/vedomosti.ru/auto/articles/2018/08/17/778475-avtovaz.jpg"/>
<ListGroup>
    <ListGroupItem>Тел: 999 999 99-99</ListGroupItem>
    <ListGroupItem>Улица:VAZ STREET</ListGroupItem>
</ListGroup>
</Container>
