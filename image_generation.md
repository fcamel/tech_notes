# Image Generation

"【生成式AI】Stable Diffusion、DALL-E、Imagen 背後共同的套路"讀後筆記 
https://www.youtube.com/watch?v=JbfcAaBT66U

## 三個步驟
![](https://i.imgur.com/pc0xIpF.jpg)
1. text encoder
2. generation model
3. decoder

## text encoder 影響 >> decoder
![](https://i.imgur.com/LpxjALa.jpg)


## text encoder 可用 GPT 實作, 將文字描述轉作 latent representation

## generation model 和 diffussion model 類似, 差別是對 latent representation 加雜訊, 而非對 image space 加雜訊
![](https://i.imgur.com/xCQDG6h.jpg)

## 生圖就是去雜訊
![](https://i.imgur.com/qIjtjss.jpg)
