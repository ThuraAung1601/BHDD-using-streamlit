# BHDD-using-streamlit

### Burmese Handwritten Digit Dataset
- Dataset Link : https://github.com/baseresearch/BHDD
- Download data.pkl directly in order to get pkl raw file

- Train Images : 60000 with image size (28,28)

![Train Images](Image/trainimgs.png)

- Test Images : 27561 with image size (28,28)

![Test Images](Image/testimg.png)

- Classes : 10, i.e, handwritten digits 0 to 9

![Handwritten1 Images](Image/no1.png)

### Install requirements
```{r, engine='bash', count_lines}
tra@thura-pc:~$ pip install -r requirements.txt
```

### Train BHDD with Basic ConvNet Architecture with Dropout
```{r, engine='bash', count_lines}
tra@thura-pc:~$ runipy CNN_train.ipynb
```
- Learning Curves after training with ConvNet
![LearningCurves Images](Image/CnnTrain.png)

### Run and deploy using Streamlit 
```{r, engine='bash', count_lines}
tra@thura-pc:~$ streamlit run app.py
```
### Experiments 
- Epochs : 15
- GPU Execution
- Tools : Matplotlib, Numpy, Keras
- Results
![Results Images](Image/Table.png)


