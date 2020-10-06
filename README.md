# News-Title-Classifier

This is my interview project, i also deployed it in local & website using pythonanywhere.com.
This model makes good prediction on unseen dataset.

I also make comment spam classifier in this project (actually 2 project but different notebook)

Because this project didn't have a huge dataset, GRU / LSTM is preferred than transformer model, why?
- Transformer model use big memory for deployment
- No complex prediction (only 4 classes)

But Transformer model only took 3 minutes to train (using TPU) compared with GRU / LSTM which took 2 hours to train
