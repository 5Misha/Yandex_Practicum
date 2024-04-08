# Анализ сервиса аренды самокатов GoFast
https://github.com/5Misha/My-Skills/blob/main/Аренда_самокатов/Аренда_самокатов.ipynb

# Задача проекта
У нас есть данные популярного сервиса аренды самокатов GoFast о некоторых пользователях из разных городов, а также об их поездках. Нужно проанализировать данные и проверить некоторые гипотезы, которые могут помочь бизнесу вырасти. Узнать, есть ли отличия между информацией от людей, которые купили подписку, и тех, кто этого не сделал.

# Используемые библиотеки
import os  
import pandas as pd  
import numpy as np   
import scipy.stats as st # эта и ниже библиотеки понадобятся нам ближе к концу
from scipy.stats import binom, poisson
from matplotlib import pyplot as plt
from math import sqrt
from scipy import stats as st

