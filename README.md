# Image-Inpainting
## Project Overview

This project implements **Image Inpainting using Generative Adversarial Networks (GANs)**. It fills missing or corrupted parts of images in a realistic and seamless way. The **generator** predicts the missing regions, while the **discriminator** ensures the inpainted areas look natural.  

By leveraging deep learning techniques such as **contextual attention** and **perceptual loss**, the model preserves textures, structures, and semantics, making the completed images almost indistinguishable from the original.  

**Applications:** Photo restoration, object removal, and advanced image editing.
## Project Overflow
<img width="698" height="519" alt="image" src="https://github.com/user-attachments/assets/d4df8e63-e5b1-497f-9815-19e48c928030" />

The following ppt describesw how the image impainting is done
[Image-impainting-using-GAN-ppt.pdf](https://github.com/user-attachments/files/23955775/Image-impainting-using-GAN-ppt.pdf)


The following image shows the performance of the GAN-based image inpainting model after training for 150 epochs.  
It includes the **original image**, the **masked image**, the **mask**, and the final **inpainted result**.
![WhatsApp Image 2025-12-05 at 13 09 29_5ca16eda](https://github.com/user-attachments/assets/1ddaba94-a428-4561-b196-a16e4298f154)
![Epoch150 Output]![WhatsApp Image 2025-12-05 at 13 10 45_ebbb9fb8](https://github.com/user-attachments/assets/f1fa8477-209d-411a-8dc7-c22548bcae30)

## 📉 Generator & Discriminator Loss Curves

The following graphs show how the Generator (G) and Discriminator (D) losses evolved during training.  
These plots help verify that the GAN is stable and learning properly.
### 🔹 Loss Graph – During Epoch 150
![Loss Graph 1]![WhatsApp Image 2025-12-05 at 13 11 12_cd9443bc](https://github.com/user-attachments/assets/ec1dda02-1acd-43f2-b238-95778574d15f)
### 🔹 Final Loss Graph (After Training Completion)
![Loss Graph 2]![WhatsApp Image 2025-12-05 at 13 11 33_abc59c42](https://github.com/user-attachments/assets/eb987d5a-5d6b-4c59-9d07-8deda986534e)



