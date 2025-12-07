# mis583-group14 for Deep Learning class

A Comparative Study of CNN and Transformer on Calligraphy Style Recognition with Explainability Analysis

本次期末專案報告旨在深入探討並比較 CNN 與 Transformer 兩種截然不同的架構在書法辨識上的表現。目標是應用遷移學習，將預訓練的手寫辨識模型，透過Fine-Tuning讓其能夠判讀辨識異於一般手寫字的書法字體。同時比較CNN和Transformer兩模型對於書法風格辨識的performance。但我們不僅關心模型「預測了什麼」，而是需要知道模型是「基於什麼理由」做出判斷，因此在辨識書法的基礎上再加上Grad-CAM熱力圖分析，藉此分析比較對於不同模型間在判斷書法風格時關注的地方、認知的邏輯。
