# Text Generator using LSTM and Keras
Text Generator is basically to use Deep Learning to develop a language model to generate new pieces of text by training on a corpus of data 
and let the model emit new word sequences given a seed word.
We will make using LSTM and Keras to train this text generator and the training set was William Shakespeare's Sonnets that can downloaded
from [project gutenberg](http://www.gutenberg.org/ebooks/1041?msg=welcome_stranger). The entire model was trained on a GPU Machine on Google
Cloud Platform.

After training for 3 epochs, it predicted the below text. Model started with some really good predictions but then it started repeating
the words.

    Seed:
    hee shall stay.
    when thou reviewest this, thou dost review
    the very part was consecrate to thee: 

    then io the wore the tore the sore to thee,
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee     
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      
    then the woue the tore the tore to thee      th
    
After increasing the number of epochs, the model observed more patterns in the data and interestingly it was able to add 
punctuation marks but then in the end it started repeating the sentences. Below is the result obtained after training for
20 epochs.
```
  Seed:
  " stopped are.
    mark how with my neglect i do dispense:
      you are so strongly in my purpose bred,
  "
 the hard the beauty of your srue inace,
  and there bur shou, that i am sometime thee,
  and there bur shou, that words the lovnne oray.
  and there bur srieer than thou dost stain,
  and there thou thalt wour should mote be to done.

  lxxxiii

  when i have seen the world should would have seen to come,
  since what is hn the surength of all the sime,
  and seamo summer's fear will be thy faces,
  and see that love with thee i see surange;
  the some will better that thou dost sece stre,
  and therefore lake the wirhow will of youth,
  and therefore lake the wirhow will of youth,
  and therefore lake the wirhow will of youth,
  and therefore lake the wirhow will of youth,
  and therefore lake the wirhow will of youth,
  and therefore lake the wirhow will of youth,
  and therefore lake the wirhow will of youth,
  and therefore lake the wirhow will of youth,
  and therefore lake the wirhow will of youth,
  and therefore lake the wirhow will of youth,
  and therefore lake the
  ```

