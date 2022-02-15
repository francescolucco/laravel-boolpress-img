<template>
    <main class="container">
        <video>
            <source
                src="{{asset('public/images/video2.mp4')}}"
                type="video/mp4">
        </video>
        <h1>ABOUT</h1>

        <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nobis,
            nam. Eos deserunt non, est magnam, corporis deleniti sapiente
            tenetur quo id enim odit earum officia aspernatur dicta, quos in
            alias.
        </p>
    </main>
</template>

<script>
export default {
    name: "About",
};
</script>

<style lang="scss" scoped>
main {
    padding-top: 180px;
    video {
      //   position: fixed;
      //   left: 0;
      //   top: 0;
        min-width: 100%;
        min-height: 100%;
        width: auto;
        height: auto;
        z-index: -100;
        visibility: visible;
        border: 10px solid black;
    }
}
</style>

//                 :src="asset('/public/images/video2.mp4')"
