<script lang="ts">
    import { Card, CardBody, CardHeader, CardImg, CardText, Col, Container, Form, FormGroup, FormText, Image, Row, Input, Button } from "@sveltestrap/sveltestrap";
</script>

<svelte:head>
    <title>Главная</title>
</svelte:head>

<Container class="shadow-ld p-2">
<h1 class="text-center">Добро пожаловать на страницу О нас</h1>
<p>Мы бизнесмены по производству говна </p>
<p>Тема:VAZ</p>

<Row>
    <Col>
        <Card>
            <CardHeader></CardHeader>
            <CardBody>
                <CardImg src="https://a.d-cd.net/NecmtOfuI0hWl6jVC1BUyhUi7lc-960.jpg"/>
                <CardText></CardText>
            </CardBody>
        </Card>
    </Col>
    <Col>
        <Card>
            <CardHeader>VAZ</CardHeader>
            <CardBody>
                <CardImg src="https://cdnstatic.rg.ru/uploads/images/2024/04/11/miro2902_442_48d.jpg"/>
                <CardText></CardText>
            </CardBody>
        </Card>
    </Col>
    <Col>
    <Card>
        <CardHeader>VAZ</CardHeader>
        <CardBody>
            <CardImg src="https://avatars.mds.yandex.net/get-autoru-vos/1552469/40f15c0ccea7d4bf1b00d9a4e9f89cec/1200x900n"/>
            <CardText> </CardText>
        </CardBody>
    </Card>
</Col>
</Row>
<Form>
    <h1>Оставить заявку на покупку</h1>
    <FormGroup>
        <FormText>Ваш email</FormText>
        <Input type="email"/>
    </FormGroup>
    <Button color="success" class="w-100">Оставить заявку на покупку</Button>
</Form>
</Container>
