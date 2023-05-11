## Hola! soy Eliana Cristaldo 👋

class Perfil {

  constructor(nombre, profesion, experiencia, tecnologias, habilidades, descripcion) {
  
    this.nombre = nombre;
    this.profesion = profesion;
    this.experiencia = experiencia;
    this.tecnologias = tecnologias;
    this.habilidades = habilidades;
    this.descripcion = descripcion;
  }
  
  presentar() {
    console.log(`¡Hola! Soy ${this.nombre}, una ${this.profesion} con ${this.experiencia}. Me especializo en las siguientes tecnologías: ${this.tecnologias.join(", ")}. Mis habilidades incluyen: ${this.habilidades.join(", ")}. ${this.descripcion}`);
  }
}

const perfil = new Perfil(

  "Eliana Cristaldo",
  "Programadora",
  "Sin experiencia previa",
  ["HTML", "CSS", "JavaScript", "Node.js", "MongoDB", "React.js"],
  ["Resolución de problemas", "Aprendizaje rápido", "Trabajo en equipo"],
  "Soy una programadora entusiasta y dedicada, especializada en tecnologías web como HTML, CSS, JavaScript, Node.js, MongoDB y React.js. Aunque no tengo experiencia laboral previa, poseo una sólida base de conocimientos y habilidades que me permiten enfrentar desafíos de programación. Soy apasionada por resolver problemas y aprender nuevas tecnologías."
);

perfil.presentar();
