[EN]
# Traffic Sign Recognition - Metehan Ayhan

### Project Description:

This project aims to build a deep learning model that can recognize and classify German traffic signs. The model is trained on the German Traffic Sign Dataset, which contains various traffic sign images. The project allows users to upload an image of a traffic sign and predicts the class of the sign. The model is deployed as a Streamlit web application and has been published on Hugging Face Spaces.

### Live Demo:

You can access the live version of the traffic sign recognition app on Hugging Face via the following link:
[German Traffic Sign Recognition on Hugging Face](https://huggingface.co/spaces/metehanayhan/TrafficSignRecognition)

![1](https://github.com/user-attachments/assets/1379b3c2-3ef7-4f92-a93f-e97b14fde18d)
![2](https://github.com/user-attachments/assets/2c26b574-6f6b-4e8c-9513-8dbeab8ec657)


### Project Structure:

- **app.py**: The Streamlit application for traffic sign recognition.
- **model.h5**: The pre-trained model used for classifying traffic signs.
- **Train.csv / Test.csv**: The dataset used for training and testing the model (not included in the repo, refer to Kaggle for the dataset).

### Instructions:

1. Clone the repository:
    
    ```bash
    git clone https://github.com/metehanayhan/Traffic-Sign-Recognition-Model.git
    ```
    
2. Install the necessary dependencies:
    
    ```bash
    pip install -r requirements.txt
    ```
    
3. Run the Streamlit application:
    
    ```bash
    streamlit run app.py
    ```
    
4. Upload a traffic sign image (JPEG, PNG) in the application and receive a classification prediction.

### Model Training:

The model was trained using Convolutional Neural Networks (CNN) with the following architecture:

- Multiple Conv2D layers with ReLU activation
- MaxPooling layers for dimensionality reduction
- BatchNormalization for stabilizing the training
- Dense layers for final classification using softmax activation

The dataset used is publicly available from the **German Traffic Sign Dataset** on Kaggle. After preprocessing and normalization of the images, the model was trained to classify 43 different traffic signs. The dataset includes classes such as speed limits, stop signs, and other cautionary road signs.

### Deployment:

The Streamlit web application is integrated with Hugging Face Spaces for easy access. You can use the provided Hugging Face link to test the traffic sign classifier directly in your browser without needing to run the code locally.

### Example Use Case:

After running the application, upload an image of a traffic sign (e.g., a speed limit sign) to the app. The model will process the image and display the predicted class such as "Speed limit (50km/h)" or "Stop". This project demonstrates the power of deep learning in real-world applications such as autonomous driving, where recognizing traffic signs is crucial for navigation.

### License:

This project is licensed under the MIT License - see the LICENSE file for details.

---

[TR]

# Traffic Sign Recognition - Metehan Ayhan

## Proje Açıklaması:

Bu proje, Alman trafik işaretlerini tanıyan ve sınıflandıran bir derin öğrenme modeli geliştirmeyi hedeflemektedir. Model, çeşitli trafik işareti görüntülerini içeren **German Traffic Sign Dataset** kullanılarak eğitilmiştir. Proje, kullanıcıların bir trafik işareti görüntüsü yüklemesine olanak tanır ve bu işaretin sınıfını tahmin eder. Model, bir **Streamlit** web uygulaması olarak dağıtılmış ve Hugging Face Spaces üzerinden yayınlanmıştır.

---

## Canlı Demo:

Trafik işareti tanıma uygulamasına aşağıdaki bağlantıdan erişebilirsiniz:
[German Traffic Sign Recognition on Hugging Face](https://huggingface.co/spaces/metehanayhan/TrafficSignRecognition)

![1](https://github.com/user-attachments/assets/1379b3c2-3ef7-4f92-a93f-e97b14fde18d)
![2](https://github.com/user-attachments/assets/2c26b574-6f6b-4e8c-9513-8dbeab8ec657)

---

## Proje Yapısı:

- **app.py**: Trafik işareti tanıma için Streamlit uygulaması.
- **model.h5**: Trafik işaretlerini sınıflandırmak için kullanılan önceden eğitilmiş model.
- **Train.csv / Test.csv**: Modelin eğitimi ve testi için kullanılan veri seti (depo içinde yer almıyor, Kaggle üzerinden erişebilirsiniz).

---

## Kullanım Talimatları:

1. Depoyu klonlayın:
    
    ```bash
    git clone https://github.com/metehanayhan/Traffic-Sign-Recognition-Model.git
    ```
    
2. Gerekli bağımlılıkları yükleyin:
    
    ```bash
    pip install -r requirements.txt
    ```
    
3. Streamlit uygulamasını başlatın:
    
    ```bash
    streamlit run app.py
    ```
    
4. Uygulamaya bir trafik işareti görüntüsü (JPEG, PNG) yükleyin ve sınıflandırma tahminini alın.

---

## Model Eğitimi:

Model, aşağıdaki mimariye sahip Convolutional Neural Networks (CNN) kullanılarak eğitilmiştir:

- ReLU aktivasyonlu birden fazla **Conv2D** katmanı
- Boyut azaltma için **MaxPooling** katmanları
- Eğitim sürecini stabilize etmek için **BatchNormalization**
- Son sınıflandırma için **softmax** aktivasyonlu **Dense** katmanları

Model, Kaggle üzerindeki **German Traffic Sign Dataset** kullanılarak eğitilmiştir. Veri seti, hız limitleri, dur işaretleri ve diğer uyarı işaretleri gibi toplam 43 farklı trafik işareti sınıfını içermektedir. Görseller, ön işleme ve normalizasyon işlemleri yapıldıktan sonra modele verilmiştir.

---

## Dağıtım:

Bu proje, Streamlit web uygulaması ile Hugging Face Spaces üzerinde dağıtılmıştır. Hugging Face bağlantısı sayesinde, kodu yerel olarak çalıştırmaya gerek kalmadan trafik işareti sınıflandırıcısını doğrudan tarayıcınızda test edebilirsiniz.

---

## Örnek Kullanım:

Uygulamayı çalıştırdıktan sonra, bir trafik işareti görüntüsü (örneğin, bir hız limiti işareti) yükleyin. Model, görüntüyü işleyerek sınıf tahminini gösterecektir. Örneğin: "Hız Limiti (50km/s)" veya "Dur". Bu proje, trafik işaretlerini tanımanın kritik olduğu otonom sürüş gibi gerçek dünya uygulamaları için derin öğrenmenin gücünü göstermektedir.

---

## Lisans:

Bu proje, MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasına bakabilirsiniz.
