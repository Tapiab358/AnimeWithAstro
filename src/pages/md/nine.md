---
title: 'detail-1'
layout: '../../layouts/Layout.astro'
---

<section transition:animate="slide"  class='flex gap-7 justify-center items-center flex-wrap text-white px-8% py-20'>
   <img class='rounded-xl' src="/images/MZ.jpg" alt="Mazinger Z" />
   <div class='flex flex-col gap-4'>
   <h2 class='text-transparent bg-clip-text bg-gradient-to-br from-indigo-600 from-10% via-primary via-30% to-green-600 font-semibold'>Mazinger Z</h2>
   <p class='max-w-md'>Este anime cuenta la historia de dos arqueólogos que encontraron los restos de una civilización antigua que era capaz de construir robots gigantes, uno de los arqueólogos cree que construyendo robots como esos podría gobernar al mundo.</p>
   </div>
</section>

<style>
   section{
      width:100%;
      min-height: calc(100vh - 52px)
   }
</style>
