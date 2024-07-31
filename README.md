# potato-disease-classification

The potato crop is found at fourth as a major crop in the world, after rice, wheat, and maize. Nonetheless, in Ethiopia, the yield per unit area of potato is very low compared to other countries. There are a plethora of reasons, one of them is the disease. The major disease, which affects the major potato production area is Late Blight, according to researchers the disease caused 100% crop loss on the unimproved local cultivar and 67.1% on a susceptible variety.

Not to take early Late Blight disease management would destroy the whole farm within a few days. For decades many researchers have experimented on plant disease detection and classification using computer vision via different approaches and algorithms. Many researchers used traditional machine learning algorithms which require a handcrafted feature extraction to detect a given image. Besides, the data collected were under a laboratory setup which makes it less reliable while testing in real cultivation farms captured images of the potato.

Heterogeneous image datasets were collected from (Holeta, Ethiopia) potato farm with the help of two plant pathologists. The dataset correctly labeled with two classes as ‘Healthy’ and ‘Late Blight’, and the image has variety meaning some of the images captured with less noisy background image and others with a highly noisy environment. Under ‘Late Blight’ class 63 images were collected and under ‘Healthy’ class 363 images were collected. Finally, the prepared dataset could be used for different researches that aimed at plant disease detection and classification.



## Difference Between Early Blight and Late Blight of Potato
The early blight is a result of a fungal infection by Alternaria and thrives in warmer climates, while the late blight is due to an oomycete Phytophthora infection that prospers in cooler environments.

### Deploying the TF Lite on GCP
1. Create a GCP account.
2. Create a Project on GCP (Keep note of the project id).
3. Create a GCP bucket.
4. Upload the potatoes.h5 model in the bucket in the path models/potatos.h5.
5. Install Google Cloud SDK (Setup instructions).
6. Authenticate with Google Cloud SDK.
