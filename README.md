# Aplicación de Reconocimiento de Texto y Detección de Rostros con ML Kit  

## Descripción  
¡Una app Android que utiliza **Google ML Kit** para extraer texto de imágenes y detectar rostros! Perfecta para explorar visión por computadora o integrar IA en proyectos móviles.  

---

## Funcionalidades  

1. **OCR (Reconocimiento Óptico de Caracteres)**  
   - Extrae texto de imágenes capturadas con la cámara o seleccionadas desde la galería.  
   - Muestra el texto detectado en un cuadro de resultados.  

2. **Detección de Rostros**  
   - Identifica rostros en imágenes y dibuja rectángulos rojos alrededor de ellos.  
   - Muestra la cantidad de rostros detectados.  

3. **Integración con Cámara y Galería**  
   - Permite elegir entre tomar una foto nueva o seleccionar una existente.  

4. **Interfaz Intuitiva**  
   - Botones dedicados para cada función (`OCR`, `Rostros`, `Cámara`, `Galería`).  
   - Área visual para previsualizar imágenes y resultados.  

---

## Capturas de Pantalla y Explicación  

### 1. Funcionamiento del OCR  
![OCR](https://github.com/user-attachments/assets/1204cad3-6d2a-4ed4-bffa-bb245cde97fe)

- **Descripción:** Muestra el texto extraído de una imagen (ejemplo: "Google ML Kit" detectado en una foto).  
- **Detalles:** El texto reconocido se muestra en el cuadro `Resultados` debajo de la imagen.  

### 2. Detección de Rostros  
![Rostros](https://github.com/user-attachments/assets/9f41026c-a8f3-4f0d-9551-5798313803a6)

- **Descripción:** Rostros detectados marcados con rectángulos rojos.  
- **Detalles:** El número de rostros se indica en el cuadro de resultados (ejemplo: "Hay 2 rostro(s)").  

---

## Cómo Funciona  

1. **Flujo de Uso**  
   - Selecciona una imagen usando `Galería` o `Cámara`.  
   - Presiona `OCR` para extraer texto o `Rostros` para detectar caras.  
   - Los resultados se actualizan automáticamente.  

2. **Tecnologías Clave**  
   - **Google ML Kit:** Procesa imágenes para OCR (`TextRecognition`) y detección facial (`FaceDetection`).  
   - **Canvas y Paint:** Dibuja rectángulos sobre los rostros detectados.  
   - **Intents de Android:** Integración con la cámara y galería del dispositivo.  
