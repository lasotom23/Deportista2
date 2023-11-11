# superclase-persona
public class Herencia { 
 
    public static void main(String arg[]) { 
        // Asignatura 1 heredada desde la super clase Persona. 
 
        System.out.println("-> Persona 1"); 
 
        // Instancia de la persona 1 Zonia. 
 
        Zonia m = new Zonia(); 
 
        // Imprimir la información de la persona 1. 
 
        m.imprimirInformacion(); 
         // Instancia del Estudiante.

        Estudiante es = new Estudiante();

        // Imprimir la información del estudiante.

        es.imprimirInformacion();
 
    }


    

    public static class Persona{

        // Nombre de la persona.

        private String nombre;

        // edad de la persona.

        private int edad;

        // carrera del estudiante.

        private String carrera;

        // sexo de la persona.

        private String campus;

        // Constructor predeterminado de la clase.

        public Persona() {
        }

        /*
        Constructor con sobrecarga para la
        inicializacion de la persona.
        */

        public Persona(String nombre,
                          int edad,
                          String carrera,
                          String campus) {
            this.nombre = nombre;

            this.edad = edad;

            this.carrera = carrera;

            this.campus = campus;
        }


        /*
        Declaracion de los getters y setters
        de cada variable miembro de la clase.
        */

        public String getNombre() {
            return this.nombre;
        }

        public void setNombre(String nombre) {
            this.nombre = nombre;
        }


        public int getEdad() {
            return this.edad;
        }

        public void setEdad(int edad) {
            this.edad = edad;
        }


        public String getCarrera() {
            return this.carrera;
        }

        public void setCarrera(String carrera) {
            this.carrera = carrera;
        }


        public String getCampus() {
            return this.campus;
        }

        public void setCampus(String campus) {
            this.campus = campus;
        }

        /*
        Metodo para imprimir la informacion
        de la persona.
        */

        public void imprimirInformacion() {
            System.out.println("");

            System.out.println("Nombre: " + nombre);

            System.out.println("Edad: " + edad);

            System.out.println("Carrera: " + carrera);

            System.out.println("Campus: " + campus);
            
        }

    }

    
    
    public static class Estudiante extends Persona {

        public Estudiante() {
            /*
            Inicializacion de la subclase Estudiante mediante
            los setters definidos en la superclase Persona, con
            los valores de la persona: Maynor.
            */

            super("Merlin",19,"Ingieneria Industrial","Puerto Cortes");
        }
    }
    
   
        }
        Clase abstracta  pública Persona { 
    // Propiedades
     Cuerda privada nombre;
     int int privado ;
     identidad de cuerdas privada ;
     Cuerda privada sexo;
    
    // Constructor de la clase
     Persona pública () {
        
    }
    
    // Establecer y obtener.
    public  void  setNombre ( String  nombre ) {
        esta . nombre = nombre;
    }
     Cadena  pública getNombre () {
        volver nombre;

public class abstracta extends Persona
{
    Cuerda privada nombredeportista;
     int int privado ;
     deporte de cuerdas privada ;
     Cuerda privada sexo;
    {
        public  void  setNombre ( String  nombre ) {
        esta . nombredeportista = nombredeportista;
    }
     Cadena  pública getNombre () {
        volver nombredeportista;
    }
    
    El  vacío  público setEdad ( int  edad ) {
        esta . edad = edad;
    }
    public  int  getEdad () {
        volver edad;
    }
    
     Setdeporte de vacío  público ( String deporte ) { 
        esta . deporte = deporte;
    }
     Cadena  pública getIentidad () {
        volver identidad;
    }
    
    public  void  setSexo ( String  sexo ) {
        esta . sexo = sexo;
    }
     Cadena  pública getSexo () {
        volver sexo
    }
    
     informacion vacia  abstracta deportista();
    
}
