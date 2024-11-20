<template>
  <div id="layoutDefault">
    <div id="layoutDefault_content">
      <main>
        <Header></Header>
        <header
          class="page-header page-header-dark bg-img-cover overlay"
          style="background-image: url(https://source.unsplash.com/SYTO3xs06fU/1500x700)"
        >
          <div class="page-header-content">
            <div class="container">
              <div class="row justify-content-center">
                <div class="col-xl-8 col-lg-10 text-center">
                  <h1 class="page-header-title">Nos apasiona la tecnología</h1>
                  <p
                    class="page-header-text mb-5"
                  >Agrupamos e impulsamos las comunidades tecnológicas mallorquinas</p>
                  <a
                    href="https://www.linkedin.com/company/techspiritmallorca/"
                    target="_blank"
                    class="btn btn-primary btn-marketing rounded-pill"
                  >Síguenos</a>
                </div>
              </div>
            </div>
          </div>
          <div class="svg-border-angled text-light">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 100 100"
              preserveAspectRatio="none"
              fill="currentColor"
            >
              <polygon points="0,100 100,0 100,100" />
            </svg>
          </div>
        </header>
        <section class="bg-light py-10">
          <div class="container">
            <div class="row justify-content-center">
              <div class="col-lg-6">
                <div class="mb-5 text-center">
                  <div class="text-xs text-uppercase-expanded text-primary mb-2">Sobre nosotros</div>
                </div>
              </div>
            </div>
            <div class="row justify-content-center">
              <div class="col-lg-12 two-columns">
                <p>Somos un grupo de personas a las que un día se les ocurrió formar una comunidad alrededor de un tema de tecnología que nos apasiona.</p>
                <p>La tecnología la entendemos en su sentido más amplio, no solo desde el punto de vista de IT o el desarrollo de software, sino desde la aplicación de la ciencia a la resolución de problemas concretos.</p>
                <p>Hasta ahora hemos operado bajo diferentes nombres y comunidades alrededor de áreas de conocimiento específicas.</p>
                <p>En 2020 vemos la oportunidad de colaborar y establecer sinergias que nos hagan aún más efectivos en nuestro empeño y que logren hacer aún más atractivo el sector tecnológico para todo tipo de público.</p>
                <p>No es fácil conseguir financiación, ni empujar una comunidad solo. Por eso buscamos una comunidad de comunidades que pueda apoyarnos y crecer más allá de nosotros mismos, con nuevos canales de comunicación, con nuevos formatos de interacción entre los miembros.</p>
              </div>
            </div>
          </div>
          <div class="svg-border-angled text-white">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 100 100"
              preserveAspectRatio="none"
              fill="currentColor"
            >
              <polygon points="0,100 100,0 100,100" />
            </svg>
          </div>
        </section>
        <section class="bg-white py-10">
          <div class="container">
            <div class="row justify-content-center">
              <div class="col-lg-6">
                <div class="mb-5 text-center">
                  <div class="text-xs text-uppercase-expanded text-primary mb-2">Comunidades</div>
                </div>
              </div>
            </div>
            <div class="row">

              <Communitie name="Mallorca JS" url="https://www.meetup.com/es-ES/MallorcaJS/" img="mallorcajs.jpeg"/>
              <Communitie name="Mallorca Software Crafters" url="https://www.meetup.com/es-ES/Mallorca-Software-Crafters/" img="mallorcasoftwarecrafters.jpeg"/>
              <Communitie name="AWS User Group Palma" url="https://www.meetup.com/es-ES/awsusergrouppalma/" img="paws.jpeg"/>
              <Communitie name="Big Data, ML & AI" url="https://www.meetup.com/es-ES/bigdata-ml-ai-mallorca/" img="logo-white.png" bg_black="ture" />
              <Communitie name="Makespace Mallorca" url="https://www.meetup.com/es-ES/makespace-mallorca/" img="makespace.jpeg"/>
              <Communitie name="Grafana & Friends Baleares" url="https://www.meetup.com/es-ES/grafana-and-friends-baleares/" img="grafana&friends.jpeg"/>
              <Communitie name="Palma BlockChain Meetup" url="https://www.meetup.com/palma-blockchain-travel-meetup-group/" img="palma_blockchain.jpg"/>
              <Communitie name="Cloud Native Mallorca" url="https://www.meetup.com/cloud-native-mallorca/" img="cloud-native-mallorca.webp"/>

            </div>
          </div>
          <div class="svg-border-angled text-light">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 100 100"
              preserveAspectRatio="none"
              fill="currentColor"
            >
              <polygon points="0,100 100,0 100,100" />
            </svg>
          </div>
        </section>

        <section class="bg-light py-10">
          <div class="container">
            <div class="row justify-content-center">
              <div class="col-lg-6">
                <div class="mb-5 text-center">
                  <div class="text-xs text-uppercase-expanded text-primary mb-2">Manifiesto</div>
                </div>
              </div>
            </div>
            <div class="row justify-content-center">
              <div class="col-lg-12">
                <ul>
                  <li>Creemos en que la diversidad de conocimiento es la mejor vía de evolución en tecnología.</li>
                  <li>Creemos en que somos más fuertes colaborando que dividiendo, que el diálogo transversal aporta más que el discurso unidireccional.</li>
                  <li>Creemos que cualquier persona con curiosidad y ganas de aprender puede ser parte de un evento de tecnología o colaborar en la creación de soluciones, sin etiquetar a “los que saben” y “los que no saben”.</li>
                  <li>Creemos que tod@s podemos aprender y tod@s podemos enseñar algo.</li>
                  <li>Queremos mantener a la comunidad técnica de la isla activa, promover el intercambio de puntos de vista y difundir el conocimiento lo más posible para beneficiar al conjunto de la sociedad, tanto local como internacional, a la que podemos llegar gracias a la tecnología.</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="svg-border-angled text-white">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 100 100"
              preserveAspectRatio="none"
              fill="currentColor"
            >
              <polygon points="0,100 100,0 100,100" />
            </svg>
          </div>
        </section>
        <section class="bg-white py-5">
          <div class="container">
            <div class="row justify-content-center">
              <div class="col-xl-6 col-lg-8 col-md-10 text-center my-5 py-5">
                <h2>¿Quieres saber más?</h2>
                <p
                  class="lead text-gray-500 mb-5"
                >Mándanos un email o síguenos en Linkedin para enterarte de nuestros próximos eventos y ven a conocernos en persona.</p>
                <a
                  class="btn btn-primary btn-marketing rounded-pill"
                  target="_blank"
                  href="https://www.linkedin.com/company/techspiritmallorca/."
                >Síguenos en LinkedIn para saber de los eventos que organizamos</a>
              </div>
            </div>
          </div>
        </section>
      </main>
    </div>
    <div id="layoutDefault_footer">
      <footer class="footer pt-5 pb-5 mt-auto bg-black footer-dark">
        <div class="container">
          <div class="row align-items-center">
            <div class="col-md-6 small">Copyright &copy; Tech Spirit Mallorca</div>
            <div class="col-md-6 text-md-right small">
              <div class="ml-auto">
                <a
                  class="btn-default btn rounded-pill px-2 social-icon"
                  target="_blank"
                  href="https://www.youtube.com/channel/UCZKdEQkM595kE23GqSxKbiA"
                >
                  <img :src="require(`~/assets/youtube.png`)" alt="YouTube TechSpirit" />
                </a>
                <a
                  class="btn-default btn rounded-pill px-2 social-icon"
                  target="_blank"
                  href="https://twitter.com/techspiritmall1"
                >
                  <img :src="require(`~/assets/twitter.png`)" alt="Twitter TechSpirit" />
                </a>
                <a href="mailto:techspiritmallorca@gmail.com">techspiritmallorca@gmail.com</a>
              </div>
            </div>
          </div>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
import Header from "~/components/Header";
import Communitie from "~/components/Communitie"
export default {
  components: {
    Header,
    Communitie,
  }
};
</script>

<style lang="scss">
.two-columns {
  columns: 2;
  column-gap: 75px;
}

.card.lift {
  height: 100%;
  display: flex;
  .img-wrapper {
    padding: 25px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex: 1 0 auto;
    .bg-black {
      border-radius: 5px;
    }
    img {
      border-radius: 5px;
      max-height: 140px;
      width: auto;
      max-width: 100%;
    }
  }
  .card-body {
    display: flex;
    align-items: flex-end;
    justify-content: center;
    flex: 0 1 auto;
  }
}

@media screen and (max-width: 992px) {
  .two-columns {
    columns: 1;
  }
}
</style>
