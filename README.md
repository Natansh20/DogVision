# DogVision

This project aimed to develop a deep learning model for accurate dog breed identification in images. Leveraging a pre-trained ImagenetV2 model and a diverse dataset of 120 unique dog breeds, the model achieved an impressive 90.18% accuracy on the Kaggle platform. To ensure a robust training process, a meticulous preprocessing pipeline was implemented, incorporating data augmentation techniques and efficient batch generation for seamless data handling. Moreover, the pre-trained model was fine-tuned by customizing its input and output layers to better match the specific task of dog breed classification. To prevent overfitting and effectively monitor training progress, custom callbacks were created: Tensorboard for real-time visualization of metrics and EarlyStopping to intervene and halt training before it memorizes specific details instead of learning generalizable features. The trained model was then rigorously evaluated on both validation and test sets, demonstrating its effectiveness in generalizing to unseen data. This project showcases the effectiveness of deep learning and transfer learning for achieving high accuracy in complex image classification tasks, highlighting its potential for various real-world applications in dog breed identification and related domains.
