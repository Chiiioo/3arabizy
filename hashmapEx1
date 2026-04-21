import java.util.HashMap;
import java.util.Map;

public class EjemploDiccionario {
    public static void main(String[] args) {
        // Crear un diccionario (mapa) que asocia String -> Integer
        Map<String, Integer> edades = new HashMap<>();

        // Agregar pares clave-valor
        edades.put("Ana", 25);
        edades.put("Luis", 30);
        edades.put("Carlos", 28);

        // Obtener un valor por su clave
        System.out.println("Edad de Ana: " + edades.get("Ana")); // 25

        // Verificar si existe una clave
        if (edades.containsKey("Luis")) {
            System.out.println("Luis está en el diccionario");
        }

        // Recorrer todas las entradas
        for (Map.Entry<String, Integer> entrada : edades.entrySet()) {
            System.out.println(entrada.getKey() + " -> " + entrada.getValue());
        }

        // Eliminar una entrada
        edades.remove("Carlos");
    }
}
