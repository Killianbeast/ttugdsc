<template>
  <Layout>
    <main style="height: 100%">
      <section id="video-club-description">
        <div class="top-section-container">
          <div class="row mt-1-sm hero">
            <div class="col-6-sm">
              <g-img 
                id="project-image"
                src="~/assets/images/smiling.jpg"
              />
            </div>
            <div class="col-6 mt-5 mx-3">
              <h3 class="text-center">
                Texas Tech Developer Student Club Mission
              </h3>
              <h5 class="text-center">
                Lorem ipsum dolor sit amet, consec
                tetur adipiscing elit. Nam condimentum tempus diam, ultricies
                sollicitudin erat facilisis eget. Vestibulum rhoncus dui vel eros
                laoreet consectetur. Vivamus eget elementum
              </h5>
              <a
                class="btn-lg mt-1 mx-3 btn-centered-md"
                href="https://gdsc.community.dev/texas-tech-university/"
                target="_blank"
              >
                Become a Member!
              </a>
            </div>
          </div>
        </div>
      </section>
    </main>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Projects'
  }
}
</script>