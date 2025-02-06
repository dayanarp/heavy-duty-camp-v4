# MANEJADOR DE EVENTOS

## Objetivo

El objetivo de este proyecto es desarrollar un **MANEJADOR DE EVENTOS DESCENTRALIZADO** basado en la blockchain de Solana. Este programa permitirá a los usuarios:

- Crear eventos.
- Participar como colaboradores.
- Vender entradas.
- Distribuir las ganancias obtenidas al finalizar el evento.

---

## LOS EVENTOS

- Estos eventos dependerán de la colaboración de los usuarios para llevarse a cabo, ya que los fondos necesarios para su organización se obtendrán de la venta de **Tokens del Evento** que los usuarios adquieran a manera de colaboradores (**sponsors**).
- Aquellos usuarios colaboradores del evento recibirán parte de las ganancias generadas con la venta de entradas.

---

## TOKEN DEL EVENTO

- Estos tokens tendrán un valor **1:1** de una moneda específica asignada al momento de crear el evento, que actuará como **Moneda Aceptada** en todas las transacciones.
- Las ganancias obtenidas de los Tokens del Evento se depositarán en una **Bóveda del Evento**.
- El organizador podrá retirar fondos de la **Bóveda del Evento** para cubrir los gastos referentes al mismo.

---

## ENTRADAS DEL EVENTO

- Cada evento pondrá a la venta una cantidad de entradas con un valor definido al momento de crear el evento.
- Las ganancias obtenidas de la venta de las entradas se depositarán en una **Bóveda de Ganancias**.
- Estas ganancias se dividirán entre los colaboradores al finalizar el evento.

---

## EL PROGRAMA

El manejador de eventos está compuesto por **siete (7) instrucciones** que describen el flujo de trabajo de todo el sistema:

1. Crear un evento.
2. Eliminar un evento.
3. Comprar tokens del evento (**sponsor**).
4. Comprar entradas.
5. Retirar fondos del evento.
6. Finalizar un evento.
7. Retirar ganancias del evento.

---

## CREAR UN NUEVO EVENTO

- Crea una nueva cuenta que almacena los datos de un evento.
- Crea las cuentas PDA relacionadas al evento:
  - **Token del evento**
  - **Bóveda del evento**
  - **Bóveda de ganancias**
