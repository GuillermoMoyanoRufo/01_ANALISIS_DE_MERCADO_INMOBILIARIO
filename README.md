# 🏢 DISEÑO DEL PROYECTO

Este caso simula que somos una empresa inmobiliaria que hace inversiones en grandes ciudades comprando inmuebles para posteriormente alquilarlos como apartamentos turísticos.

La dirección ha tomado la decisión de invertir en **Madrid**, y nos ha encargado analizar los datos que el líder del sector **Airbnb** hace públicos para intentar encontrar los tipos de inmuebles que tienen mayor potencial comercial para alquiler turístico.

**Entregable principal:** Tipología (o tipologías) de inmuebles que el equipo de valoraciones debe buscar entre las oportunidades existentes en la ciudad y los principales barrios o zonas geográficas en las que focalizarse.

Para cumplir con el objetivo aplicaremos la metodología de **Discovery** y las técnicas de **BA** aprendidas.

Aunque este caso concreto esté centrado en el alquiler turístico el mismo tipo de aproximación se puede usar en casos que tengan un alto componente de **"ubicación"**:
* Apertura y cierre de tiendas.
* Reducción de capacidad instalada.
* Expansión de franquicias, etc.

---

## 🎯 OBJETIVO
Localizar el perfil (o perfiles) de inmuebles que maximizan el potencial comercial en el mercado del alquiler turístico y las principales zonas donde buscarlos.

---

## ⚙️ PALANCAS
Tras hablar con el equipo de valoraciones nos dicen que las palancas que tienen más impacto en la rentabilidad de este tipo de inversiones son:

1. **Precio alquiler:** Cuanto más se pueda cobrar por noche mayor es la rentabilidad.
2. **Ocupación:** En general cuantos más días al año se pueda alquilar un inmueble mayor es su rentabilidad.
3. **Precio inmueble:** Cuanto más barato se pueda adquirir la propiedad mayor es la rentabilidad.

---

## 📊 KPIs
En este ejemplo los KPIs son bastante directos:

* **Ocupación:** Mediremos la ocupación como el número de días anuales que el inmueble se pueda alquilar.
* **Precio del alquiler:** Mediremos el precio del alquiler como el precio por noche en euros según Airbnb.
* **Precio de un inmueble:** Mediremos el precio de un inmueble como la multiplicación entre el número de metros cuadrados y el precio medio del m2 en su zona, aplicando un **25% de descuento** sobre el precio oficial por la fuerza de negociación de nuestro equipo de compras.

---

## 🗂️ ENTIDADES Y DATOS
Las entidades relevantes para nuestro objetivo y de las que podemos disponer de datos son:
* **Inmuebles**
* **Propietarios**
* **Distritos**

*Los datos concretos en cada uno de ellos los revisaremos en el siguiente módulo.*

---

## ❓ PREGUNTAS SEMILLA

### 💰 Sobre el precio del alquiler:
* ¿Cuál es el precio medio? ¿Y el rango de precios? ¿Y por distritos? ¿Y por barrios?
* ¿Cuál es el ranking de distritos y barrios por precio medio de alquiler?
* ¿Qué factores (a parte de la localización) determinan el precio del alquiler?
* ¿Cuál es la relación entre el tamaño del inmueble y el precio por el que se puede alquilar?
* ¿Cómo influye la competencia (num inmuebles disponibles por barrio) sobre el precio del alquiler?
* ¿Cómo varían los precios por tipo de alquiler (todo el piso, habitación privada, habitación compartida)?

### 📈 Sobre la ocupación:
* ¿Cuál es la ocupación media? ¿Y por distritos? ¿Y por barrios?
* ¿Cómo de probable es cada nivel de ocupación en cada distrito?
* ¿Cuál es el ranking de distritos y barrios por ocupación?
* ¿Qué factores (a parte de la localización) determinan la ocupación?
* ¿Cuál es la relación entre el tamaño del inmueble y su grado de ocupación?
* ¿Cómo influye la competencia (num inmuebles disponibles por barrio) sobre la ocupación?

### 📉 Sobre el precio de compra:
* ¿Cuál es el ranking de precio por m2 por distrito?
* ¿Cuál es el ranking de precio del inmueble (m2 * tamaño medio) por distrito?
* ¿Cuál es la relación entre el precio del inmueble y el precio del alquiler por distrito?
* ¿Cuál es la relación entre el precio del inmueble y la ocupación por distrito?
