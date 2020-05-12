# fashion_mnist_vae

This is a minimal example of a jupyter notebook which expects:
1. train_file
2. test_file
3. ckpt_file
4. parameter.json 
 
and produce outputs in the output directory

To make this code run you need to create symbolic links:
> cd ./fashion_mnist_vae \
> ln -s ./NECESSARY_INPUT_FILES/ckpt.pkl ./ \
> ln -s ./NECESSARY_INPUT_FILES/fashionmnist_test.pkl ./ \
> ln -s ./NECESSARY_INPUT_FILES/fashionmnist_train.pkl ./ \
> ln -s ./NECESSARY_INPUT_FILES/parameters.json ./  \

This code can be run using "cromwell_for_ML" (https://github.com/dalessioluca/cromwell_for_ML.git)
which localizes the required files from a google bucket to the execution directory where the 
juopyter notebook is located


