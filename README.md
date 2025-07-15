# 詞嵌入與古代漢語
這個倉庫包含兩個內容，一個是古漢語分時期語料庫；一個是詞嵌入模型，包含 Word2Vec、GloVe、BERT-Chinese 以及 Chinese-RoBERTa。

該語料庫是經過分詞處理的語料庫。此古代漢語語料庫是依據上古、中古、近古三階段，先秦、兩漢、魏晉南北朝、隋唐、宋元、明清六時期建立的。材料選取旨在模擬古代漢語真實演變，注重文言文材料與白話材料在時代演變中的比例。古代漢語語料具有跨領域、跨時間、跨文體等複雜因素，傳統分詞工具在古漢語的表現上薄弱，而該語料庫的語料分詞由 LLM 分詞，取得良好效果。

詞嵌入模型是基於以上語料庫訓練的，分為兩種類型：靜態詞嵌入和上下文詞嵌入。靜態詞嵌入的模型是 Word2Vec 和 GloVe；上下文詞嵌入的模型是 BERT-Chinese 和 Chinese-RoBERTa。

# Word Embeddings and Ancient Chinese
This repository contains two main components: a diachronic ancient Chinese corpus and a set of word embedding models, including Word2Vec, GloVe, BERT-Chinese, and Chinese-RoBERTa.

The corpus is pre-segmented and organized by historical periods.
It is structured according to three major stages—Old Chinese, Middle Chinese, and Early Modern Chinese—and six periods: Pre-Qin, Two-Han, Wei-Jin and Northern and Southern Dynasties, Sui-Tang, Song-Yuan, and Ming-Qing.
The materials were selected to simulate the authentic evolution of ancient Chinese, focusing on the proportion of literary (wenyan) and vernacular materials over time. 
Given the corpus’s cross-domain, cross-temporal, and cross-genre complexity, traditional word segmentation tools perform poorly on ancient Chinese. Therefore, segmentation was performed by LLMs, yielding good results.

The word embedding models are trained on this corpus and are of two types: static embeddings (Word2Vec, GloVe) and contextual embeddings (BERT-Chinese, Chinese-RoBERTa).
