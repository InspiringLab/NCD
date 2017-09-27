# NCD
Nepali Characters Dataset

### Using the Character Dataset

#### Use below Python import statement
from nepali_chracters import split

x_train,y_train,x_test,y_test,valid_set_x,valid_set_y = split(training_per=0.8,test_per=0.1,validation_per=0.1)
