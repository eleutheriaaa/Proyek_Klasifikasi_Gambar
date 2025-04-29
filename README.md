# Proyek_Klasifikasi_Gambar
# Food11 Model


## Struktur Folder
- food11_saved_model/  
Model dalam format SavedModel untuk penggunaan di TensorFlow Python.

- tfjs_model/  
Model dalam format TensorFlow.js untuk penggunaan di web browser.

- tflite/  
Model dalam format TensorFlow Lite (.tflite) dan file label.txt untuk penggunaan di mobile app atau edge devices.

## Cara Penggunaan
- TensorFlow (Python):  
Load model dengan tf.keras.models.load_model('food11_saved_model').

- TensorFlow.js:  
Load model di browser dengan tf.loadLayersModel('path/to/model.json').

- TensorFlow Lite:  
Deploy model .tflite ke Android, iOS, atau perangkat edge menggunakan TensorFlow Lite interpreter.
