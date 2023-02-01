<template> 

    <div class="h-full lg:mx-48">
        <div class="text-left h-full mx-4">
            <div class="mt-8 rounded text-xl flex flex-col gap-2 ">
                <h2 class="text-4xl font-['South'] text-white">hei.. minu nimi on</h2>
                <h1 class="text-6xl md:text-center text-white mt-2 font-['South']">MARKUS</h1>
                <h3 class="font-['Start'] text-white">Mulle meeldib kood,</h3> <h3 class="text-white  text-4xl font-['Bangers']">disain.. ja</h3> <h3 class="text-white">muusika</h3>  <h3 class="font-['Start'] text-white">Need kolm asja on omavahel seotud</h3>
                <p class="text-white lg:text-2xl font-semibold mt-4">Olen 17-aastane noorem tarkvaraarendaja ja õpin Kuressaare Ametikoolis. <br> Peamiselt olen tegelenud Vue JS / Tailwindiga. <br class=""> Olen õppinud veel Pythonit, Javascripti, MySQLI, Linuxi Terminali, PHP-d.
                <br> Olen iseloomult sõbralik ja õpihimuline. Meeldib meeskonda juhtida ja erinevaid probleeme lahendada. <br>
                    Vabal ajal tegelen muusika loomisega ehk räppimise ja instrumentaalide tegemisega. Kasutan enda muusikaga tegemiseks FL Studiot ja mu loovusega saab tutvuda alloleval lingil.</p>
                    <a class="text-lime-300 text-2xl font-semibold italic" href="https://www.lebra.ee/">www.lebra.ee</a>
                    <div class="flex gap-2">
                        <router-link to="/ceevee">
                            <div class="flex">
                                <button class="text-white bg-black bg-opacity-50 w-8 h-8 rounded-full">CV</button>
                            </div>
                        </router-link>
                            <div class="flex">
                                <a href="https://github.com/lebra2"><button class="text-white bg-white w-8 h-8 rounded-full"><img src="../assets/Pictures/github-logo(1).png" alt=""></button></a>
                            </div>
                    </div>

            </div>
            
        </div>

    </div>
</template>