# proyecto-
para la creacion de las clases del codigo 


public class Animal {
    private String nombre;
    private String tipo; // terrestre, aéreo, acuático
    private String genero; // masculino, femenino

    public Animal(String nombre, String tipo, String genero) {
        this.nombre = nombre;
        this.tipo = tipo;
        this.genero = genero;
    }

    // Getters y Setters
    public String getNombre() { return nombre; }
    public void setNombre(String nombre) { this.nombre = nombre; }

    public String getTipo() { return tipo; }
    public void setTipo(String tipo) { this.tipo = tipo; }

    public String getGenero() { return genero; }
    public void setGenero(String genero) { this.genero = genero; }
}
