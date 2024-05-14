The following libraries were used:

import matplotlib.pyplot as plt
import matplotlib.image as mpimg
import cv2
import numpy as np
from skimage.feature import hog
import os
import random
import pickle
import scipy as sp

import torch
import torchvision
import torchvision.transforms as transforms

import torch.nn as nn
import torch.nn.functional as F

import torch.optim as optim

import pandas as pd
from sklearn import datasets
from sklearn.metrics import classification_report
from tqdm import tqdm
from time import time
from keras.datasets import mnist

Google Drive Mount:
from google.colab import drive

All versions of each library are the default versions loaded through Google Colab.