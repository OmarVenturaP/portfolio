<template>
<section class="page-section" id="contact">
            <div class="container">
                <div class="text-center">
                    <h2 class="section-heading text-uppercase">Contactanos</h2>
                    <h3 class="section-subheading text-muted">Envianos un mensaje y te contactaremos lo más pronto posible.</h3>
                </div>
                <form id="contactForm" action="https://formsubmit.co/8c0a8baf5ab5e90d60e3300940c2f98b" method="POST">
                    <div class="row align-items-stretch mb-5">
                        <div class="col-md-6">
                            <div class="form-group card">
                                <!-- Name input-->
                                <input class="form-control" name="name" id="name" type="text" placeholder="Nombre *" required />
                            </div>
                            <div class="form-group card">
                                <!-- Email address input-->
                                <input class="form-control" name="email" id="email" type="email" placeholder="Email *" required/>
                            </div>
                            <div class="form-group mb-md-0 card">
                                <!-- Phone number input-->
                                <input class="form-control" name="phone" id="phone" type="number" placeholder="Telefono *" required />
                            </div>
                        </div>
                        <div class="col-md-6">
                            <div class="form-group form-group-textarea mb-md-0 card">
                                <!-- Message input-->
                                <textarea class="form-control" name="message" id="message" placeholder="Mensaje *" required></textarea>
                            </div>
                        </div>
                    </div>
                    <!-- Submit Button-->
                    <div class="text-center"><button class="btn btn-primary btn-xl text-uppercase" id="submitButton" type="submit">Enviar mensaje</button></div>
                    <!-- Config add -->
                    <input type="hidden" name="_autoresponse" value="Gracias por contactarnos, nos comunicaremos contigo a la brevedad">
                    <input type="hidden" name="_next" value="http://127.0.0.7:5500/">
                    <input type="hidden" name="_captcha" value="false">
            </form>
            </div>
        </section>
</template>

<script>
export default {
    name: 'ContactForm',
}
</script>

<style>

</style>