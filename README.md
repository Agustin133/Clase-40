# Clase N° 40 - Mejorar la arquitectura de nuestra Api

Para este desafio integré una función factory que me permite cambiar de persistecia de datos (File, Memory o MySql), utilizando tambien el patron de diseño Singleton.
Para encender la api uilizar: npm run start (Memory,File,Mysql). Por defecto arranca en memory.
Mi proyecto contiene los siguientes endpoints: Un GET,GET by Id, PUT, DELETE y POST.
Mandar el id para el Get by id, delete y put por parametro.
Como boyd para el post y el put:
{
  "title": "pantalon",
   "price": "100",
   "stock": "12",
   "code": "ASSD1234JASD",
   "thumbnail": "fotofrepantalon.png",
   "description": "Es un pantalon"
}
