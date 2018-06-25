# 101-image-classifier

### Add the dataset of labeled folders with images within then in dataset folder
### open terminal and change the directory to the project folder and run the following code

_**note**: use gpu enabled laptops or desktops for training the model or train the model over google ML based cloud system ~~we trained the model on macbook air early 2017 edition it took 12 hrs to train the model~~(not recommended)_

_**make changes in script as per your system directories**_

link for [trained mode](https://drive.google.com/open?id=1jjlNMCbIVqSuvAYYc2TPBFX5pu9DJPFw)

### To train the model use following code:
    python train.py --dataset dataset --model 101.model \
	--labelbin mlb.pickle
    
### To test the model use following code:
    python classify.py --model 101.model --labelbin mlb.pickle --image examples/pd.jpg
    

![Certificate](https://github.com/Preetam2114/101-image-classifier/blob/master/plot2.png?raw=true)
  
  
  
