# aplicacion-de-consola

public class VisitanteEdificio {
    public static void main(String[] args) {

        // Tipos primitivos numéricos
        byte pisoVisita = 3;                 // Piso al que va el visitante
        short numeroDepartamento = 205;      // Número de departamento
        int cedula = 897654321;              // Cédula o identificación del visitante
        long telefono = 6699887766L;         // Teléfono (requiere L al final)

        float temperaturaCorporal = 36.5f;   // Temperatura corporal al ingresar (requiere f)
        double latitudUbicacion = 8.987654;  // Latitud de la ubicación del edificio

        // Tipos primitivos no numéricos
        char genero = 'M';                   // Género del visitante: M o F
        boolean tieneCita = true;            // Si tiene cita previa o no

        // Salida de la información del visitante
        System.out.println("----- Información del Visitante -----");
        System.out.println("Cédula: " + cedula);
        System.out.println("Teléfono: " + telefono);
        System.out.println("Género: " + genero);
        System.out.println("Temperatura corporal: " + temperaturaCorporal + "°C");
        System.out.println("Tiene cita previa: " + tieneCita);
        System.out.println("Departamento a visitar: " + numeroDepartamento);
        System.out.println("Piso: " + pisoVisita);
        System.out.println("Latitud del edificio: " + latitudUbicacion);
    }
}
