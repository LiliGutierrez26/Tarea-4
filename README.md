# Tarea-4

(defclass Cliente
   (is-a USER)
   (slot id (type INTEGER))
   (slot nombre (type STRING))
   (slot correo (type STRING))
   (slot cel (type STRING)))

(defclass Producto
   (is-a ITEM)
   (slot marca (type SYMBOL))
   (slot modelo (type SYMBOL))
   (slot memoria (type INTEGER))
   (slot precio (type FLOAT))
   (slot existencia (type INTEGER)))

(defclass SmartWatch
   (is-a Producto))

(defclass Smartphone
   (is-a Producto))

(defclass Tablet
   (is-a Producto))

(defclass TarjetaCredito
   (is-a ITEM)
   (slot nombre (type SYMBOL)))

(defclass Banamex
   (is-a TarjetaCredito))

(defclass BBVA
   (is-a TarjetaCredito))

(defclass AmericanExpress
   (is-a TarjetaCredito))
