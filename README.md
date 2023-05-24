# FLGen
We adopt the code files from the Personalized Federated Learning Platform (https://github.com/TsingZ0/PFL-Non-IID) and make some changes. 

The main change is in the file dataset/utils/dataset_utils.py, where we add another type of data distributions called “niidrate”. One can generate different levels of heterogeneity of local datasets by specifying the niidrate. Here is an example of the command line to run it.
python generate_mnist.py noniid - niidrate 0.5

There are also some minor changes. By replacing the corresponding files in the platform, one can simulate similar results as in the paper.
