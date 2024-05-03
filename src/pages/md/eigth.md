---
title: 'detail-5'
layout: '../../layouts/Layout.astro'
---

<section transition:animate="slide"  class='flex gap-7 justify-center items-center flex-wrap text-white px-8% py-20'>
   <img class='rounded-xl' src="/images/SM.jpg" alt="Sailor Moon" />
   <div class='flex flex-col gap-4'>
   <h2 class='text-transparent bg-clip-text bg-gradient-to-br from-indigo-600 from-10% via-primary via-30% to-green-600 font-semibold'>Sailor Moon</h2>
   <h4>Lorem ipsum dolor sit amet consectetur</h4>
   <p class='max-w-md'>La historia se centra en las aventuras de una adolescente llamada Usagi Tsukino, quien se transforma en una poderosa guerrera conocida como Sailor Moon y lucha contra aquellos que buscan destruir el Sistema Solar.</p>
   <button class='w-20 h-7 border-gray-50 border-2 rounded-md flex justify-center items-center hover:bg-blue-900 transition'>Buy</button>
   </div>
</section>

<style>
   section{
      width:100%;
      min-height: calc(100vh - 52px)
   }
</style>
