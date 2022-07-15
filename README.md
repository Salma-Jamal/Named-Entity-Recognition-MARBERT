# Named Entity Recognition using MARBERT
1) Prepare Your Arabic Dataset for NER Using BIO Tags, Tag a phrase using B (Begin), I (Interior), and E (End). For example, you want to tag "United States of America" as the name of a country. You will tag it like this: <br/>
   * United   => B_Country 
   * States   => I_Country 
   * of       => I_Country
   * America  => E_Country 

2) Apply the pipeline Using: <br>
   * MARBERT: A pre-trained BERT-base Arabic masked language model.
   * The dataset is gathered from an Arabic chatbot.
