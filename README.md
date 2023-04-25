# Twitch Emote Prediction
**Author: Yasmine Hejazi**

    .           
    ├── src                     
    │   ├── notebooks             # Model code
    │   ├── scrapers              # Data scrapers
    ├── README.md   
    └── research_study_paper.pdf  # Full report


## Abstract
The rise of live-streaming platforms like Twitch.tv has revolutionized how users communicate in the form of plain text and ideogram emojis. Despite extensive research on emoji use in a social media setting, emote research in the context of live-streaming platforms has received little attention from the standpoint of Natural Language Processing. In this paper, I investigate the relation between words and Twitch emotes by predicting which Twitch emotes are evoked by text-based Twitch chat messages. I train three models based on Long Short-Term Memory networks (LSTMs) and transformer models (fine-tuned BERT) to compare previous research to the
latest up-and-coming technologies. The experimental results show that the fine-tuned BERT model outperforms a majority-class predictor baseline and the two LSTM models, suggesting that transformers are able to better capture emote prediction in a setting of noisy, user-generated text.
