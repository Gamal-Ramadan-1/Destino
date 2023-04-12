<template>
    <section class="header">
        <div class="container">
            <div class="grid grid-cols-1 items-center justify-center" style="height: 100%;">
                <div class="text-center relative">
                    <h3 class="absolute text-center text-white top-[35%] right-[29%] z-[1] font-[400] text-[72px]">Discover
                        new worlds

                    </h3>
                    <h1 class="uppercase text-[215px] font-[900] text-[#fdaa27] opacity-[0.34] z-[0]">discover</h1>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    name: 'Header'
}
</script>
<style scoped lang="scss">
section {
    background-image: url('../../Imgs/home.jpg.webp');
    background-size: cover;
    background-position: center center;
    height: 100vh;

    .container {
        height: 100%;
        @media screen and (max-width:1024px) {
            h1{
                font-size: 140px;
            }
            h3{
                font-size: 55px;
                font-weight: 400;
                right: 25%;
            }
        }
        @media screen and (max-width:768px) {
            h1{
                font-size: 140px;
            }
            h3{
                font-size: 48px;
                font-weight: 400;
                right: 21%;
            }
        }
        @media screen and (max-width:426px) {
            h1{
                font-size: 72px;
            }
            h3{
                font-size: 27px;
                font-weight: 400;
                right: 21%;
            }
        }
        @media screen and (max-width:320px) {
            h1{
                font-size: 62px;
            }
            h3{
                font-size: 24px;
                font-weight: 400;
                right: 15%;
                top:33%
            }
        }
    }
}
</style>