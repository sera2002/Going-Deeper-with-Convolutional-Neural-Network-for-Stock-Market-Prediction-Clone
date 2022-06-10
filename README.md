# Going-Deeper-with-Convolutional-Neural-Network-for-Stock-Market-Prediction-Clone

## Reference of this repository
#### rosdyana/Going-Deeper-with-Convolutional-Neural-Network-for-Stock-Market-Prediction
#### https://github.com/rosdyana/Going-Deeper-with-Convolutional-Neural-Network-for-Stock-Market-Prediction

#### To run generate dataset, enter the commands below.
`python run_binary_preprocessing.py 2880.TW 20 50`   
`pip install -U -r requirements.txt`   
`python generatedata.py dataset 20_50/2880.TW dataset_2880TW_20_50`

#### After executing the above commands, you should remove alpha channel but the below command does not work.
`cd /dataset/dataset_2880TW_20_50`   
`find . -name "*.png" -exec convert "{}" -alpha off "{}" \;`
