<script lang="ts">
    import { Card, CardBody, CardHeader, CardImg, CardText, Col, Container, Image, Row } from "@sveltestrap/sveltestrap";
</script>

<svelte:head>
    <title>Главная</title>
</svelte:head>

<Container class="shadow-ld p-2">
<h1 class="text-center">Добро пожаловать на главную страницу!</h1>
<p>Работу представляет:Ашрапов Рамазан Ленарович</p>
<p>Тема:lada vesta</p>

<Row>
    <Col>
        <Card>
            <CardHeader>lada vesta</CardHeader>
            <CardBody>
                <CardImg src="https://a.d-cd.net/kzc-qpUTZyiGgYTABZ9ravB1kPg-1920.jpg"/>
                <CardText>106л.с</CardText>
            </CardBody>
        </Card>
    </Col>
    <Col>
        <Card>
            <CardHeader>lada vesta</CardHeader>
            <CardBody>
                <CardImg src="https://avatars.mds.yandex.net/i?id=4cb5e5c7d7eff7658f3ba2cec61ad7d4_l-11741862-images-thumbs&n=13"/>
                <CardText>Рядный, 4-цилиндровый бензиновый двигатель объёмом 1,6 литра</CardText>
            </CardBody>
        </Card>
    </Col>
    <Col>
    <Card>
        <CardHeader>lada vesta</CardHeader>
        <CardBody>
            <CardImg src="https://avatars.mds.yandex.net/i?id=1505a1ce1b7a7b84461dd2a9d1e8652a_l-5167445-images-thumbs&n=13"/>
            <CardText>Производство LADA Vesta началось 25 сентября 2015 года на </CardText>
        </CardBody>
    </Card>
</Col>
</Row>
</Container>
