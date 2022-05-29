title: titulo de la pagina
h1: Titulo principal
h2: Subtitulo
ul: lista no ordenada (con viñetas)
i: elemento de la lista
a: enlaces
ol: lista orendeada importa el orden (con numeros)
p: parrafo
img: imagen
form: label, 
input: 
    type: number, password, email, checkbox, radio (seleccionar solo 1), 
    select 
    <select>
        <optgroup label = "Ingenieria">
            <option value="0"> -- <option> //Opcion por defecto
            <option value="electronica"> Electronica </option>
            <option value="teleco"> Telecomunicaciones </option>
        </optgroup>
    </select>
    file 
    para enviar el formulario se puede usar el type = subimt
name = es el nombre de la variable para proecesar la informacion. os elementos que tengan el mismo name-importante para checkbox y radio)
br: salto de linea
textadd: comentarios
audio:controls, src, type, loop 
<audio>
    <track kind="subttitles" src="./.vtt" srclan="es" label="Spanish"> //subtitulos en español
</audio>

##Etiquetas semanticas: No le cambia la estructura en la pagina

header

<form>
    <button>Log in<>
    <button> Registro 
nav
section (izq)
    article (subdividir section)
aside (Derecha): se utiliza para barras laterales, publicidad
div 
footer: Pie de pagina, esta en todas las paginas
figure: img, caption (subtitulo)
