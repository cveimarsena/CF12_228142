<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Configuración final
    .row.justify-content-center.align-items-center.bg2
      .col-lg-auto.pt-lg-0.pt-md-4
        img.img-a.img-t(src='@/assets/curso/temas/t2/1.png' alt='')
      .col.pt-lg-0.pt-md-4
        p.mb-0 La configuración final es una etapa del proceso de preparación de un equipo de cómputo antes de su entrega al usuario. Esta fase asegura que el equipo esté completamente listo para su uso, personalizado según las necesidades del usuario, y que todos los datos importantes estén respaldados y protegidos.
    Separador  
    #t_2_1.titulo-segundo.color-acento-contenido
      h2 2.1 Personalización del usuario
    p La personalización de usuario implica configurar el equipo de acuerdo con las necesidades y preferencias del usuario final. Esta etapa es adecuada para garantizar que el equipo sea funcional y eficiente desde el primer momento de uso. Para lograr un proceso exitoso, se sugiere seguir los pasos que describe la figura 1 a continuación:
    
    .titulo-sexto.color-acento-contenido.offset-0(data-aos="zoom-in")
      h5 Figura 1.
      span  Proceso para la configuración de  perfiles
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12
        figure
          img(src='@/assets/curso/temas/t2/2.svg', alt='La Figura 1 se denomina «Proceso para la configuración de perfiles» y presenta la secuencia detallada de los pasos que se deben seguir para garantizar un perfil seguro y exitosos.') 
        figcaption Fuente: OIT, 2024.

    TabsC.color-acento-contenido.mb-5
      .p-4.py-99.py-md-5(titulo="Instalación de aplicaciones personalizadas")
        .row.justify-content-center.bg3.p-4.brad
          .col-lg-5
            img.img-a.img-t(src='@/assets/curso/temas/t2/3.png' alt='')
          .col-lg-7.mb-4.mb-md-0.p-4
            h4.mb-4 Instalación de aplicaciones personalizadas
            p.mb-3 La instalación de aplicaciones y programas que el usuario necesitará para su trabajo es un paso en la personalización de estos. 
            ul.lista-ul.fa-ul.ps-4
              li 
                i.fas.fa-check-circle.color1
                span Software de productividad: Instalación de suites de oficina, herramientas de gestión de proyectos y otras aplicaciones de productividad.
              li 
                i.fas.fa-check-circle.color1
                span Herramientas de desarrollo: Instalación de entornos de desarrollo integrados (IDEs), compiladores y otras herramientas de desarrollo.
              li 
                i.fas.fa-check-circle.color1
                span Aplicaciones de diseño gráfico: Instalación de software de diseño gráfico, edición de video y otras aplicaciones creativas.

      .p-4.py-99.py-md-5(titulo="Configuración de interfaz")
        .row.justify-content-center.bg3.p-4.brad
          .col-lg-5
            img.img-a.img-t(src='@/assets/curso/temas/t2/4.png' alt='')
          .col-lg-7.mb-4.mb-md-0.p-4
            h4.mb-4 Configuración de interfaz
            ul.lista-ul.fa-ul.ps-4
              li 
                i.fas.fa-check-circle.color1
                span Temas y fondos de pantalla: Configuración de temas y fondos de pantalla según las preferencias del usuario.
              li 
                i.fas.fa-check-circle.color1
                span Barras de herramientas: Personalización de las barras de herramientas y menús para facilitar el acceso a las funciones más utilizadas.
              

      .p-4.py-99.py-md-5(titulo="Configuración de accesos directos")
        .row.justify-content-center.bg3.p-4.brad
          .col-lg-5
            img.img-a.img-t(src='@/assets/curso/temas/t2/5.png' alt='')
          .col-lg-7.mb-4.mb-md-0.p-4
            h4.mb-4 Configuración de accesos directos
            p.mb-3 Creación de accesos directos en el escritorio y en el menú de inicio para las aplicaciones más utilizadas.
            ul.lista-ul.fa-ul.ps-4
              li 
                i.fas.fa-check-circle.color1
                span Configuración de red
              li 
                i.fas.fa-check-circle.color1
                span La configuración de las conexiones de red es necesario para asegurar que el usuario pueda acceder a los recursos de red necesarios. 
              li 
                i.fas.fa-check-circle.color1
                span Configuración de #[i Wi-Fi]: Configuración de las conexiones #[i Wi-Fi] y asegurarse de que el equipo se conecte automáticamente a las redes conocidas.
              li 
                i.fas.fa-check-circle.color1
                span Configuración de VPN: Configuración de conexiones VPN para asegurar la seguridad y el acceso remoto a los recursos de la empresa.
              li 
                i.fas.fa-check-circle.color1
                span Configuración de impresoras y dispositivos periféricos: Configuración de impresoras, escáneres y otros dispositivos periféricos que el usuario necesitará.
    Separador  
    #t_2_2.titulo-segundo.color-acento-contenido
      h2 2.2	Backup y restauración
    p.mb-3 El #[i backup] y la restauración son procesos infalibles para asegurar que los datos del usuario estén protegidos y puedan ser recuperados en caso de fallo del sistema. Estos procesos garantizan la continuidad del trabajo y la seguridad de la información

    .row.justify-content-center.mb-4
     .col-lg-3.my-lg-0.my-3
        img.img-a.img-t(src='@/assets/curso/temas/t2/6.png' alt='')         
     .col-lg-9.my-lg-0.my-3
        AcordionA(tipo="a" clase-tarjeta="tarjeta bg3")
          div(titulo="Configuración de <i>backups </i>automáticos")
            p La configuración de #[i backups] automáticos es una práctica continua para asegurar que los datos del usuario estén protegidos y puedan ser recuperados en caso de fallo del sistema. Los #[i backups] automáticos eliminan la necesidad de intervención manual, reduciendo el riesgo de pérdida de datos debido a olvidos o errores humanos.
          div(titulo="Selección de la solución de <i>backup</i>") 
            ul.lista-ul.fa-ul.ps-4
              li 
                i.fas.fa-check-circle.color1
                span La elección de la solución de #[i backups] adecuada garantiza la eficacia y la seguridad del proceso de #[i backups].
              li
                i.fas.fa-check-circle.color1
                span #[i Software] de #[i backups]: Selección de #[i Software] de #[i backups] confiable y con buenas críticas, como #[i Acronis] #[i True Image], Veeam #[i backups] & #[i Replication], o #[i Carbonite].
              li
                i.fas.fa-check-circle.color1
                span Servicios en la nube: Consideración de servicios de almacenamiento en la nube como Google Drive, Dropbox, Microsoft OneDrive, o Amazon S3 para #[i backups] remotos.
              li
                i.fas.fa-check-circle.color1
                span Dispositivos de almacenamiento local: Utilización de discos duros externos, unidades de estado sólido (SSD) o servidores de almacenamiento en red (NAS) para #[i backups] locales.

    h4.mb-4 Configuración de la frecuencia de backup
    p Para garantizar que los #[i backup] tengan un éxito y aseguren la información albergada, se debe mantener la configuración de la ubicación a través del proceso que se enseña a continuación:
    
    #t_2_1.titulo-segundo.color-acento-contenido
      h2 2.1 Personalización del usuario
    p La personalización de usuario implica configurar el equipo de acuerdo con las necesidades y preferencias del usuario final. Esta etapa es adecuada para garantizar que el equipo sea funcional y eficiente desde el primer momento de uso. Para lograr un proceso exitoso, se sugiere seguir los pasos que describe la figura 1 a continuación:
    
    .titulo-sexto.color-acento-contenido.offset-0(data-aos="zoom-in")
      h5 Figura 2.
      span  Proceso configuración de la ubicación de #[i backups]
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12
        figure
          img(src='@/assets/curso/temas/t2/7.svg', alt='La Figura 2 se denomina «Proceso configuración de la ubicación de #[i backup] y presenta esta orientación a partir de cuatro acciones para prevenir daño en la información.') 
        figcaption Fuente: OIT, 2024.
    

    .row.justify-content-center.mb-4
     .col-lg-3.my-lg-0.my-3
        img.img-a.img-t(src='@/assets/curso/temas/t2/8.png' alt='')         
     .col-lg-9.my-lg-0.my-3
        AcordionA(tipo="a" clase-tarjeta="tarjeta bg3")
          div(titulo="Configuración de la restauración de  <i>backups </i>")
            p La capacidad de restaurar los datos de los #[i backups] es un paso significativo para la continuidad del trabajo y la recuperación rápida en caso de fallo del sistema
          div(titulo="Pruebas de restauración") 
            p La verificación de que los datos puedan ser restaurados correctamente en caso de fallo del sistema es considerable para garantizar la integridad de los #[i backups].
            ul.lista-ul.fa-ul.ps-4
              li 
                i.fas.fa-check-circle.color1
                span Pruebas de restauración completa: 
              li
                i.fas.fa-check-circle.color1
                span Realización de pruebas de restauración completa para asegurar que todos los datos puedan ser recuperados.
              li
                i.fas.fa-check-circle.color1
                span Servicios en la nube: Consideración de servicios de almacenamiento en la nube como Google Drive, Dropbox, Microsoft OneDrive, o Amazon S3 para #[i backups] remotos.
              li
                i.fas.fa-check-circle.color1
                span Pruebas de restauración parcial: Realización de pruebas de restauración parcial para asegurar que datos específicos puedan ser recuperados sin problemas.
          div(titulo="Pruebas de restauración en diferentes dispositivos:") 
            p Realización de pruebas de restauración en diferentes dispositivos para asegurar que los datos puedan ser recuperados en cualquier equipo.
            ul.lista-ul.fa-ul.ps-4
              li 
                i.fas.fa-check-circle.color1
                span Almacenamiento seguro  
              li 
                i.fas.fa-check-circle.color1
                span Asegurarse de que los #[i backups] se almacenen en un lugar seguro y accesible para garantizar la protección de los datos, a través de las siguientes herramientas
              li 
                i.fas.fa-check-circle.color1
                span Servicios de almacenamiento en la nube: Utilización de servicios de almacenamiento en la nube con medidas de seguridad adicionales como cifrado y autenticación de dos factores. 
              li 
                i.fas.fa-check-circle.color1
                span Discos duros externos cifrados: Utilización de discos duros externos cifrados para asegurar que los datos estén protegidos contra accesos no autorizados.
              li 
                i.fas.fa-check-circle.color1
                span Servidores locales con medidas de seguridad: Utilización de servidores locales con medidas de seguridad adicionales como firewalls y sistemas de detección de intrusos.
          div(titulo="Políticas de retención de datos") 
            p Realización de pruebas de restauración en diferentes dispositivos para asegurar que los datos puedan ser recuperados en cualquier equipo.
            ul.lista-ul.fa-ul.ps-4
              li 
                i.fas.fa-check-circle.color1
                span El establecimiento de políticas de retención de datos es importante para determinar cuánto tiempo se conservarán los #[i backups] y cuándo se eliminarán los datos antiguos.  
              li 
                i.fas.fa-check-circle.color1
                span Definición de períodos de retención: Establecimiento de períodos de retención para los #[i backups], determinando cuánto tiempo se conservarán los datos.  
              li 
                i.fas.fa-check-circle.color1
                span Eliminación de datos antiguos: Definición de procedimientos para la eliminación de datos antiguos que ya no sean necesarios. 
              li 
                i.fas.fa-check-circle.color1
                span Revisión periódica de las políticas: Realización de revisiones periódicas de las políticas de retención de datos para asegurar que sean adecuadas y estén actualizadas. 

    Separador  
    #t_2_3.titulo-segundo.color-acento-contenido
      h2 2.3	Proceso general de preparación de datos
    p.mb-3 Las actualizaciones finales aseguran que el equipo esté listo para su uso inmediato y que todos los componentes de software estén actualizados. Estas actualizaciones garantizan que el equipo funcione de manera óptima y esté protegido contra vulnerabilidades conocidas. A continuación, se detallan los principales aspectos de las actualizaciones finales:

    .row.bg5.align-items-center.mb-5
      .px-lg-5.px-4
        .bgw.brad.p-5.my-5
          SlyderA(tipo="b")
            .row.justify-content-center
              .col-lg-6.my-2
                h5.mb-4 Puntos de conexión
                p.mb-0 Asegurarse de que todas las aplicaciones instaladas estén actualizadas a sus últimas versiones es adecuado para garantizar la seguridad y el rendimiento del software. Esto incluye:
                p.mb-0 Actualizaciones de seguridad: Instalación de actualizaciones de seguridad que corrigen vulnerabilidades conocidas en las aplicaciones.
                p.mb-0 Corrección de errores: Instalación de actualizaciones que corrigen errores y problemas conocidos en las aplicaciones.
                p.mb-0 Nuevas funcionalidades: Instalación de actualizaciones que introducen nuevas funcionalidades y características que pueden mejorar la experiencia del usuario.
              
              .col-lg-5.my-2 
                img.img-a.img-t(src='@/assets/curso/temas/t2/9.png', alt='')  
            .row.justify-content-center
              .col-lg-6.my-2
                h5.mb-4 Actualización de controladores 
                p.mb-0 La instalación de los últimos controladores para todos los componentes de #[i hardware] es vital para garantizar que el #[i hardware] funcione de manera óptima.
                p.mb-0 Controladores de dispositivos: Instalación de los últimos controladores para dispositivos como la tarjeta gráfica, la tarjeta de red y otros componentes de #[i hardware].
                p.mb-0 Controladores de periféricos: Instalación de los últimos controladores para periféricos como impresoras, escáneres y otros dispositivos externos.
                p.mb-0 Controladores de firmware: Instalación de actualizaciones de firmware para componentes de #[i hardware], mejorando la seguridad y el rendimiento del #[i hardware].
              
              .col-lg-5.my-2 
                img.img-a.img-t(src='@/assets/curso/temas/t2/10.png', alt='')  
            .row.justify-content-center
              .col-lg-6.my-2
                h5.mb-4 Actualización del sistema operativo: 
                p.mb-0 Asegurarse de que el sistema operativo esté actualizado a su última versión es para garantizar la seguridad y el rendimiento del equipo. 
                p.mb-0 Asegurarse de que el sistema operativo esté actualizado a su última versión es para garantizar la seguridad y el rendimiento del equipo. 
                p.mb-0 Actualizaciones de seguridad: Instalación de actualizaciones de seguridad que corrigen vulnerabilidades conocidas y protegen el sistema contra ataques cibernéticos.
                p.mb-0 Mejoras de rendimiento: Instalación de actualizaciones que incluyen mejoras de rendimiento y optimizaciones del sistema.
                p.mb-0 Nuevas funcionalidades: Instalación de actualizaciones que introducen nuevas funcionalidades y características que pueden mejorar la experiencia del usuario.
              
              .col-lg-5.my-2 
                img.img-a.img-t(src='@/assets/curso/temas/t2/11.png', alt='')  
            .row.justify-content-center
              .col-lg-6.my-2
                h5.mb-4 Configuración de actualizaciones automáticas 
                p.mb-0 El diagnóstico de componentes implica la evaluación detallada de cada uno de los componentes críticos del equipo de cómputo 
                p.mb-0 El establecimiento de un sistema de actualizaciones automáticas para asegurar que el equipo y el software se mantengan actualizados en el futuro.
                p.mb-0 Actualizaciones automáticas del sistema operativo: Configuración de actualizaciones automáticas del sistema operativo para asegurar que el sistema esté siempre actualizado.
                p.mb-0 Actualizaciones automáticas de controladores: Configuración de actualizaciones automáticas de controladores para asegurar que el hardware funcione de manera óptima.
                p.mb-0 Actualizaciones automáticas de aplicaciones: Configuración de actualizaciones automáticas de aplicaciones para asegurar que el software esté siempre actualizado.
              
              .col-lg-5.my-2 
                img.img-a.img-t(src='@/assets/curso/temas/t2/12.png', alt='')  
            .row.justify-content-center
              .col-lg-6.my-2
                h5.mb-4 Verificación de compatibilidad 
                p.mb-0 El diagnóstico de componentes implica la evaluación detallada de cada uno de los componentes críticos del equipo de cómputo 
                p.mb-0 Asegurarse de que todas las actualizaciones sean compatibles entre sí y con el hardware del equipo es necesario para garantizar que no haya conflictos entre las actualizaciones.
                p.mb-0 Pruebas de compatibilidad: Realización de pruebas de compatibilidad para asegurar que las actualizaciones no causen conflictos con el #[i hardware] o el #[i software] del equipo
                p.mb-0 Revisión de notas de lanzamiento: Revisión de las notas de lanzamiento de las actualizaciones para identificar posibles problemas de compatibilidad.
                p.mb-0 Pruebas de rendimiento: Realización de pruebas de rendimiento para asegurar que las actualizaciones no afecten negativamente el rendimiento del equipo.
              
              .col-lg-5.my-2 
                img.img-a.img-t(src='@/assets/curso/temas/t2/13.png', alt='')    
            
              
</template>

<script>
import TabsC from '../bootstrap/TabsC'
import AcordionA from '../bootstrap/AcordionA'
import SlyderA from '../bootstrap/SlyderA'
export default {
  name: 'Tema2',
  components: { TabsC, AcordionA, SlyderA },
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
