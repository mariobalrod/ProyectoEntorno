# Diagrama de Casos de Uso



1. Diagrama de Casos de Uso:

![CasosDeUso1](./CasosDeUso1.png)



2. Ficha Técnica del Caso de Uso Comentar:

<table style="width: 100%; text-align: center;">
  <tr>
    <td style="width: 30%;">Nombre</td>
    <td style="width: 70%;">Comentar</td>
  </tr>
  <tr>
    <td style="width: 30%;">Autor</td>
    <td style="width: 70%;">Mario Ballestero</td>
  </tr>
  <tr>
    <td style="width: 30%;">Fecha</td>
    <td style="width: 70%;">17/05/2020</td>
  </tr>
  <tr>
    <td style="width: 30%;">Descripción</td>
    <td style="width: 70%;">
        Permite crear un comentario/mensaje (hilo) sobre una oferta o un local en el foro que proporcionan.
    </td>
  </tr>
  <tr>
    <td style="width: 30%;">Actores</td>
    <td style="width: 70%;">Empresa o Cliente</td>
  </tr>
  <tr>
    <td style="width: 30%;">Precondiciones</td>
    <td style="width: 70%;">
        El usuario que desee realizar un comentario deberá estar autenticado en el sistema además de no presentar ningún tipo de baneo temporal.
    </td>
  </tr>
  <tr>
    <td style="width: 30%;">Flujo Normal</td>
    <td style="width: 70%;">
        1.- El actor pulsa en el botón para redactar comentario.
        <br/>
        2.- El sistema muestra un formulario para redactar dicho comentario. Este formulario está formado por un input para un título y otro input para el cuerpo del comentario.
        <br/>
        3.- El actor introduce el título y el cuerpo del comentario.
        <br/>
        4.- El sistema valida los datos introducidos.
        <br/>
        5.- El sistema publica dicho comentario tras evaluar su validez.
        <br/>
    </td>
  </tr>
  <tr>
    <td style="width: 30%;">Flujo Alternativo</td>
    <td style="width: 70%;">
        4.A.- El sistema tras comprobar la validez de los datos introducidos, si no son correctos, se avisa al actor sobre ello y se le permite hacer modificaciones hasta que seán válidos.
    </td>
  </tr>
  <tr>
    <td style="width: 30%;">Poscondiciones</td>
    <td style="width: 70%;">
        El mensaje se ha publicado en su respectivo foro y se ha almacenado en el sistema.
    </td>
  </tr>
</table>