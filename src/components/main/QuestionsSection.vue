<template>
    <section id="faq" class="faq section-bg">
        <div class="container" data-aos="fade-up">

            <div class="section-title">
                <h2>Preguntas Frecuentes</h2>
                <p>Respondemos algunas de las principales dudas</p>
            </div>

            <div class="faq-list">
                <ul>
                    <li data-aos="fade-up" data-aos-delay="100">
                        <i class="bx bx-help-circle icon-help"></i> <a data-bs-toggle="collapse" class="collapse"
                            data-bs-target="#faq-list-1">¿Cuáles son las tecnologías que usamos? <i
                                class="bx bx-chevron-down icon-show"></i><i class="bx bx-chevron-up icon-close"></i></a>
                        <div id="faq-list-1" class="collapse show" data-bs-parent=".faq-list">
                            <p>
                              Manejamos un amplio stack tecnologico: SolidJS, VueJS, ReactJS, Flutter, NodeJS, .NET Core, TailwindCSS, etc.
                            </p>
                        </div>
                    </li>

                    <li data-aos="fade-up" data-aos-delay="200">
                        <i class="bx bx-help-circle icon-help"></i> <a data-bs-toggle="collapse"
                            data-bs-target="#faq-list-2" class="collapsed">¿Cómo realizamos el presupuesto?
                            <i class="bx bx-chevron-down icon-show"></i><i class="bx bx-chevron-up icon-close"></i></a>
                        <div id="faq-list-2" class="collapse" data-bs-parent=".faq-list">
                            <p>
                              Realizamos un relevamiento de los datos, de acuerdo a ello evaluamos la mejor tecnología para
                              llevar a cabo el desarrollo, teniendo en cuenta la escalabilidad del proyecto en cuestión.
                            </p>
                        </div>
                    </li>

                    <li data-aos="fade-up" data-aos-delay="300">
                        <i class="bx bx-help-circle icon-help"></i> <a data-bs-toggle="collapse"
                            data-bs-target="#faq-list-3" class="collapsed">¿Cuál es nuestra metodología de trabajo?
                            <i class="bx bx-chevron-down icon-show"></i><i class="bx bx-chevron-up icon-close"></i></a>
                        <div id="faq-list-3" class="collapse" data-bs-parent=".faq-list">
                            <p>
                              Planteamos al cliente una metodología de entregables por etapas.
                              La primera etapa consiste en un MVP (Minimum Viable Product, o en castellano el Producto Mínimo Viable). Posteriormente avanzamos con las demás etapas.
                            </p>
                        </div>
                    </li>

                </ul>
            </div>

        </div>
    </section>
</template>
<script setup lang="ts"></script>
<style>
</style>