<template>
    <div class="portfolio-modal modal fade" id="portfolioModal4" tabindex="-1" role="dialog" aria-hidden="true">
        <div class="container">
            <div class="modal-dialog card cb1">
                <div class="modal-content">
                    <div class="close-modal" data-bs-dismiss="modal"><img src="../../assets/img/close-icon.svg" alt="Close modal" /></div>
                    <div class="container">
                        <div class="row justify-content-center">
                            <div class="col-lg-8">
                                <div class="modal-body">
                                    <!-- Project details-->
                                    <h2 class="text-uppercase">FizzBuzz | Bot Telegram</h2>
                                    <p class="item-intro text-muted">Creando respuestas automáticas en Telegram.</p>
                                    <img class="img-fluid d-block mx-auto" src="../../assets/img/portfolio/4.gif" alt="..." />
                                    <p>Interfaz deBackend donde a través de Endpoints invocamos métodos para mostrar a través de un BOT de telegram una respuesta dependiendo las condicionales de FizzBuzz</p>
                                    <ul class="list-inline">
                                        <li>
                                            <strong>Cliente:</strong>
                                            Practica Backend (LaunchX - Innovaccion Virtual)
                                        </li>
                                        <li>
                                            <strong>Categoria:</strong>
                                            HTTP | API | Backend | Server | NodeJS | ExpressJs | PostgreSQL | Telegram
                                        </li>
                                    </ul>
                                    <a href="https://github.com/OmarVenturaP/fizzbuzz" target="_blank"><button type="button" class="btn btn-outline-light">Repositorio</button></a><br><br>
                                    <button class="btn btn-primary btn-xl text-uppercase" data-bs-dismiss="modal" type="button">
                                        <i class="fas fa-xmark me-1"></i>
                                        Cerrar
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'PortfolioModal4',
}
</script>

<style>

</style>