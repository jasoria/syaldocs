# Módulos de diseño

El software SYAL es un simulador de pozos petroleros con levantamiento artificifial hidráulico tipo jet.

Al crear un nuevo pozo o al abrir un pozo existente se desplegará la interfaz para la configuración del modelo del pozo. En el panel de la izquierda están los íconos de acceso a los diferentes módulos que componen el software SYAL. 

* Well
* PVT
* Completion
* IPR
* Flow
* Jet Pump
  
Los módulos están ordenados de forma secuencial. Para que un módulo se habilite deberá ingresar la información requerida por un módulo previo. Por ejemplo, para habilitar el módulo IPR deberá ingresar la información del módulo PVT.

# Módulo Well

![Icono well](assets/images/icono-well-flow.png)

## General information

En este panel ingresamos la información para identificar el pozo. Los campos obligatorios que no han sido completados muestran la etiqueta "Required field". En el panel **General information** son obligatorios los campos:

**Developer for:** Nombre de la persona para la que se realiza el cálculo.
**Company:** Nombre de la compañía operadora del pozo.
**Well name:** Nombre del pozo.
**Formation:** Formación/arena de la cual producirá el pozo.

## Well and flow settings

### Well settings

#### Well type

* Producer: Pozo productor
  
#### Artificial lift system

* Hydraulic jet pump: Cálculo de pozo productor con levantamiento artificial con jet pump de fondo
* Surface ejector: Cálculo de bomba jet de superficie. Al seleccionar esta el software no usa la información del completamiento del pozo




