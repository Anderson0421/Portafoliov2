---
layout: ../../layouts/LayoutsProject.astro
title: Sistema de Gestion de Personal
author: AnderDev
date: 10/09/23  -  18/10/23
description: "Desarrollé un sistema de gestión de personal basado en Django, MySQL, Tailwind y Azure para los archivos multimedia, diseñado para la 
administración integral de empleados y el control de asistencia en tiempo real con WebSockets."
image:
  url: "https://i.ibb.co/ZRjfjX2/Plataforma.png"
  alt: "Sistema de control de personal"
tecnologias : 
  tec1 : "../icons/django-svgrepo-com.png"
  tec2 : "../icons/mysql-logo-svgrepo-com.png"
  tec3 : "../icons/Microsoft_Azure.svg"
---


<p class="mb-5 text-sm text-gray-400">Desarollado desde 25/01/24 hasta el 15/03/24 </p>
<h2 class="text-4xl mb-5 font-bold  text-gray-200">
    Sistema administrativo de personal
</h2>



<div class="pr-5 text-gray-50">

<p class="mt-3 text-gray-200">
Desarrollé un completo sistema de gestión de recursos humanos utilizando tecnologías avanzadas como Django, MySQL, Tailwind y Azure.
Este sistema ofrece un control de asistencia en tiempo real, generación automática de informes en Excel, seguimiento del rendimiento de los
empleados con gráficos detallados, y un módulo de inventario para gestionar entradas y salidas de productos. Con una interfaz moderna y
amigable, este sistema optimiza los procesos internos y mejora la experiencia del usuario, representando una solución integral para las
necesidades empresariales actuales.

</p>
<div class="flex gap-5">
<a  href="../" class=" mt-5 flex w-max gap-2 bg-violet-500 px-5 py-2 rounded-xl">
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
      <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 12h-15m0 0l6.75 6.75M4.5 12l6.75-6.75" />
    </svg>
Volver 
</a>
</div>
</div>
  <div class="flex flex-col justify-center mb-20 text-gray-100">
        <h1 class="text-2xl font-bold py-2 mt-5 text-blue-300" id="content">
          Algunas imagenes representativas del sistema.
        </h1>
          <div>
            <p class="mb-10 w-3/4">
              Reporte de empleados, productos, asistencias y más en Excel, Actualización en tiempo real con WebSockets, Graficos con datos reales, etc. <span class="font-thin text-sm"> ( Por tema de privacidad se mostraran solo algunas imagenes )</span>
          </p>
          </div>
         <div class="max-2xl:w-full max-2xl:pr-5 flex flex-col gap-5">
          <img src="../innovasolar/empleados.webp" alt="img1" class="rounded-lg">
          <img src="../innovasolar/asistencia1.webp" alt="img1" class="rounded-lg">
          <img src="../innovasolar/informes.webp" alt="img1" class="rounded-lg">
          <img src="../innovasolar/graficos.webp" alt="img1" class="rounded-lg">
           <h1>
              En la sección de rendimiento, los usuarios pueden ver su calificación, que oscila entre 0 y 20, correspondiente a las actividades que llevaron a cabo cada día de la semana. Esta calificación se calcula automáticamente en Python. Al ingresar la asistencia, los usuarios registran sus responsabilidades, actividades de valor y metas, cada una con una puntuación diferente. Luego, se calcula un promedio basado en estas puntuaciones para determinar la calificación general del usuario.
          </h1>
          <img src="../innovasolar/rendimiento.webp" alt="img1" class="rounded-lg">
          <h1>
            La seccion de inventario incluye diversas funcionalidades como filtrar inventario por Local, Registro de entrada y salida y historial de este mismo.
            Descargar en excel automatizado de productos por Local, Proceso CRUD completo.
          </h1>
          <img src="../innovasolar/inventario.webp" alt="img1" class="rounded-lg">
        </div>
    </div>
<a href="#home" class="btn btn-outline btn-primary mt-10 flex w-max mb-10 ml-auto mr-10 animate-bounce">
  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
    <path stroke-linecap="round" stroke-linejoin="round" d="M4.5 15.75l7.5-7.5 7.5 7.5" />
  </svg>
</a>
