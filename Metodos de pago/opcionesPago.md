## Metodos de pago con integracion con api, sdk, link de pago o cobros por correo

1. transbank:
  - usa api y sdk para recibir pagos
  - url developers: https://www.transbankdevelopers.cl/
  - es posible realizar el desarrollo de integracion y despues contratar los servicios ya que la documentacion es publica

2. stripe:
  - usa api y sdk para recibir y enviar pagos
  - es mas completo que transbank pero mas completo, da opciones para no desarrolladores 
  - url developers: https://stripe.com/docs/libraries

3. Paypal
  - usa link de pago, este link se solicita en la web de paypal y se inserta en el frontend, al presionar el boton que tiene el link de pago se debe capturar la respuesta.
  - url developers: https://developer.paypal.com/docs/checkout/standard/integrate/

4. FLOW
  - usa link de pago y cobros por correo
  - url developers: https://www.flow.cl/cobra-email.php

5. virtualPost
  - usa api y link de pago
  - interesante opciones, al implementarlo y redireccionar al cliente a la web de virtualpost da opciones de pago de webpayplus, onepay, match y muchas mas.
  - url developers: https://app.swaggerhub.com/apis-docs/AndesTecnologia/VirtualPOS/3.0.0

6. mercado pago
  - usa api y link de pago
  - url developers: https://www.mercadopago.cl/developers/es/docs/checkout-api/landing