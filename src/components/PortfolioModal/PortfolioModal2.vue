<template>
    <div class="portfolio-modal modal fade" id="portfolioModal2" tabindex="-1" role="dialog" aria-hidden="true">
        <div class="container">
            <div class="modal-dialog card cb1">
                <div class="modal-content">
                    <div class="close-modal" data-bs-dismiss="modal"><img src="../../assets/img/close-icon.svg" alt="Close modal" /></div>
                    <div class="container">
                        <div class="row justify-content-center">
                            <div class="col-lg-8">
                                <div class="modal-body">
                                    <!-- Project details-->
                                    <h2 class="text-uppercase">Vaccination</h2>
                                    <p class="item-intro text-muted">Clon de una Landing Page.</p>
                                    <img class="img-fluid d-block mx-auto" src="../../assets/img/portfolio/2.png" alt="..." />
                                    <p>Práctica para el Bootcamp de Innovacción Virtual, la cual se trataba de crear un clon de una página, con sus diferentes diseños y secciones. Aunque había posibilidad de usar librerias como Bootstrap o Tailwind, opté por usar solo código nativo, para familiarme mas con la sintaxis de CSS, de esa forma sería más sencillo poder adaptarme al uso de librerías</p>
                                    <ul class="list-inline">
                                        <li>
                                            <strong>Cliente:</strong>
                                            Practica FrontEnd (LaunchX - Innovaccion Virtual)
                                        </li>
                                        <li>
                                            <strong>Categoria:</strong>
                                            Diseño Web | CSS
                                        </li>
                                    </ul>
                                    <a href="https://github.com/OmarVenturaP/Practica-Frontend-Sem3-CSS" target="_blank"><button type="button" class="btn btn-outline-light">Repositorio</button></a>
                                    <a href="https://omarventurap.github.io/Practica-Frontend-Sem3-CSS/" target="_blank"><button type="button" class="btn btn-outline-light">Página Web</button></a><br><br>
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
    name: 'PortfolioModal2',
}
</script>

<style>

</style>