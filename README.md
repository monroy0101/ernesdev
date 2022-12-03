<style>
  * {
  box-sizing: border-box;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
}

h1 {
  margin-bottom: 15px;
  text-align: center;
  font-size: 2em;
}

/* Desktop */

@media (min-width: 992px) {
  .col-lg-4 {
    width: 30%;
    position: relative;
    float: left;
    border: 2px solid black;
    background-color: #bccce1;
    margin: 1%;
  }
}

/* Tablet */

@media (min-width: 768px) and (max-width: 991px) {
  .col-md-6,
  .col-md-12 {
    position: relative;
    float: left;
    border: 1px solid black;
    background-color: #8c9cb8;
    margin: 1%;
  }

  .col-md-6 {
    width: 45%;
  }

  .col-md-12 {
    width: 92%;
  }
}

/* Mobile */

@media (max-width: 767px) {
  .col-sm-12 {
    position: relative;
    float: left;
    border: 1px solid black;
    background-color: #8c9cb8;
    margin: 1%;
  }
  .col-sm-12 {
    width: 90%;
  }
}

.row {
  width: 100%;
  align-items: center;
  margin-left: 2%;
  margin-right: 2%;
}

#p1 {
  position: absolute;
  top: 0px;
  right: 0px;
  font-size: 1.5em;
  font-weight: bold;
  text-align: center;
  border: 1px solid black;
  width: 40%;
  margin: 0;
}

#p2 {
  font-size: 1em;
  padding: 20px;
  text-align: justify
}
  </style>
  <body>
    <h1>Our Menu</h1>

    <div class="row">
      <div class="col-lg-4 col-md-6 col-sm-12">
        <p id="p1" style="background-color: orange">Chicken</p>
        <p id="p2">
          KFC (Kentucky Fried Chicken) fue fundado por el Coronel Harland
          Sanders, un emprendedor que comenzó a vender pollo frito en su
          restaurante al borde de la carretera en Corbin, durante la Gran
          Depresión. Sanders identificó el potencial de hacer franquicias del
          restaurante, y la primera franquicia de "Kentucky Fried Chicken" abrió
          en Salt Lake City, Utah en 1952. KFC popularizó al pollo en la
          industria de la comida rápida, diversificando el mercado desafiando el
          domino establecido de la hamburguesa.
        </p>
      </div>

      <div class="col-lg-4 col-md-6 col-sm-12">
        <p id="p1" style="background-color: maroon; color: #ffffff">Beef</p>
        <p id="p2">
          Uno de los platos más elegantes de la gastronomía universal es el Beef
          Wellington. También es uno de los más elaborados, discutidos y
          costosos, si se tiene en cuenta que entre sus ingredientes se incluye
          lomo de res de alta calidad, el foie gras en algunas de las recetas y
          trozos de jamón curado. Al mismo tiempo se ha creído que esta
          preparación fue bautizada así en honor a Sir Arthur Wellesley,
          estadista y militar irlandés. Fue exprimer ministro del Reino Unido y
          conductor de la derrota de Napoleón.
        </p>
      </div>

      <div class="col-lg-4 col-md-12 col-sm-12">
        <p id="p1" style="background-color: lightskyblue">Sushi</p>
        <p id="p2">
          El pescado es un alimento perecedero, por esta razón siempre en la
          antigüedad se empleaban diversos métodos sencillos para conservarlo,
          como el ahumado o la salazón. El proceso que se empleaba en China era
          muy innovador : se dejaba enmohecer el arroz con aspergillus oryzae
          que tiene un aspecto de polvo verde y se metían los pescados enteros
          en ánforas bien selladas. El moho se dedica a consumir los hidratos de
          carbono existentes en el arroz debido a la acción de los enzimas,
          éstos poseen la capacidad.
        </p>
      </div>
    </div>
  </body>
</html>
