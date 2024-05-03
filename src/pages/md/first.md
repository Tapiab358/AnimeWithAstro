---
title: 'detail-1'
layout: '../../layouts/Layout.astro'
---

<section transition:animate="slide"  class='flex gap-7 justify-center items-center flex-wrap text-white px-8% py-20'>
   <img class='rounded-xl' src="/images/Dragon16.jpg" alt="Dragon Ball" />
   <div class='flex flex-col gap-4'>
   <h2 class='text-transparent bg-clip-text bg-gradient-to-br from-indigo-600 from-10% via-primary via-30% to-green-600 font-semibold'>Dragon Ball</h2>
   <p class='max-w-md'>Este anime cuenta la historia de un niño con cola el cual se embarga en una gran aventura despues de la muerte de su abuelo conociendo a sin fin de personas.</p>
   </div>
</section>

<style>
   section{
      width:100%;
      min-height: calc(100vh - 52px)
   }

</style>
