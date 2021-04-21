# HackMx
Repositorio para el reto liverpool del HackMx 2021 del equipo #48 Bolt Ahead

## Integrantes
1. * Lorenzo Jácome 
2. * Dimas Maximiliano Delgado 
3. * Paola Barona Flores
4. * Vanessa Farango Aguirre

## Descripción 
Usar la tecnología del código QR para comunicar las promociones y
descuentos que se tienen en toda la tienda, así como identificar a nuestros tarjetahabientes
Liverpool y ofrecer promociones exclusivas

## Definir el problema:
Generar un nuevo canal para acercarnos a los tarjetahabientes de forma voluntaria y al mismo tiempo promocionar el uso de nuestras tarjetas Liverpool.

## Solución:
Desarrollar un servicio que produzca codigos QR y permita visualizar promociones para cuentahabientes mediante un servicio web. Así mismo, invitar a personas no afiliadas a generar una nueva linea de credito, y ofrecer servicios PIF.
* Se genera un código QR para llevar al usuario a promociones del departamento, área, evento, etc.
* Al escanaear el código QR, este te lleva a una página donde invita al usuario a ingresar número de celular y correo electrónico.
* Preguntar al usuario si cuenta con tarjeta de crédito liverpool.
* En caso de no contar con tarjeta, mostrar todas las promociones de la tienda (descuentos y meses sin intereses en sus respectivos departamentos) y mostrar beneficios de tener una tarjeta con un link para tramitarla.
* En caso de sí contar con tarjeta mostrar todas las promociones de la tienda (descuentos y meses sin intereses en sus respectivos departamentos), un espacio que te invite a conocer más de las promociones exclusivas con las que cuentas y finalmente realizar link con App Liverpool Pocket en la sección de mi credito para que pueda contratar planes de pago o su PIF.

## Roadmap
- [x] Definir solución
### Diseño
- [ ] Encontrar paleta de colores Liverpool
- [ ] Buscar como implementar a Bolo en nuestras paginas. 
- [ ] Diseño de landing page
- [ ] Diseño página para no tarjetahabientes
- [ ] Diseño para tarjetahabientes
### Funcional
- [ ] Generación de codigos QR que te lleven a Landing Page con la info de la promoción escaneada. 
- [ ] Crear landing page
- [ ] Crear página para mostrar todas las promociones
  - [ ] SIN TARJETA: Mostrar beneficios de tarjeta y pop up para tramitar tarjeta.
  - [ ] CON TARJETA: Pop up para invitarlo a ver promociones exclusivas y link que te mande a Liverpool app a la sección de "Mi crédito".
