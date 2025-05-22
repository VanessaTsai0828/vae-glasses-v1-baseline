# 🕶️ VAE Glasses Removal – Basic Version
Remove eyeglasses from face images using a simple Variational Autoencoder (VAE).


> 📚 系列作品｜Project Series:
> - [Part 1: Baseline VAE](https://github.com/VanessaTsai0828/vae-glasses-v1-baseline)
> - [Part 2: Grayscale VAE](https://github.com/VanessaTsai0828/vae-glasses-v2-grayinput)
> - [Part 3: VAE with VGG Loss](https://github.com/VanessaTsai0828/vae-glasses-v3-vggloss)
> - [Part 4: VAE with GAN](https://github.com/VanessaTsai0828/vae-glasses-v4-gan)

---

## 🧠 專案內容 | What’s Inside

- 基於 CNN 的變分自編碼器
- 訓練資料為 160x160 的臉部圖像（有眼鏡 / 無眼鏡）
- 模型輸出為「無眼鏡版」臉部
- 損失函數：重建誤差 + KL 散度  
- A simple, clean baseline model – perfect to expand later

- A CNN-based Variational Autoencoder (VAE)
- Trained on 160x160 facial images with and without glasses
- Outputs a glasses-free version of the face
- Loss function: reconstruction error + KL divergence
- A simple, clean baseline model – perfect to expand later

---

## 📸 範例結果 | Sample Result
![image](https://github.com/user-attachments/assets/629869a8-d2a5-4747-9fc1-7757c39161a0)

---

## 📌 備註 | Notes
- 此為基礎版本，無 perceptual loss / GAN 模組
- 適合作為後續進階版本的基礎
- 潛在空間可視化與特徵插值未來可加入

- This is the basic version, without perceptual loss or GAN modules
- Designed as a solid foundation for future enhancements
- Latent space visualization and feature interpolation can be added later


