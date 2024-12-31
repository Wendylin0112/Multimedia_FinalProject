# SoundScape
我們的專案旨在為音訊檔案生成相對應的影片檔，幫助人們視覺化一段美妙的音訊。 目前可以識別雨聲、溪流聲、海浪聲、火車、寫作、蟲鳴鳥叫的聲音，並由ai模型生成一段短影片。 我們希望未來可以實現將夢幻音樂聲生成看得見的場景，增加娛樂新體驗。

``# 安裝必要的程式庫（如果未安裝）\n
!pip install librosa tensorflow tensorflow_hub pandas tensorflow_io \n
!pip install diffusers transformers accelerate \n
!pip install imageio[ffmpeg] moviepy \n``

## Links
雲端資料夾的連結：https://drive.google.com/drive/folders/1NyNLC0d-jGjErz8paM7BtNICcG6FhqSs
Demo的影片連結：https://youtu.be/mTuAVx2YuI8

## Details
從一開始透過丟入要測試的音檔到已連結colab的雲端檔案中，接著透過一系列的操作去進行

1. 讀入雲端中的音檔並進行分類標籤
2. 根據每類標籤成生成的文本
2-5. 根據分類結果連結對應的文本
3. 先透過文本生成圖片，再透過圖片生成3秒鐘的影片
4. 將音檔與生成的影片結合

完成上述步驟即為我們最終的成果。
