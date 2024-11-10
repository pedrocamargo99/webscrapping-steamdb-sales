 **Webscrapping SteamDB Sales** 🤖

Esse repositório consiste em um projeto de Engenharia de Dados em que foi realizado a extração de dados do site https://steamdb.info/sales/ e carregado para o Google BigQuery.

### 🎯 Bibliotecas Utilizadas:

from pandas_gbq import to_gbq
from google.oauth2 import service_account
from bs4 import BeautifulSoup
from selenium import webdriver
from selenium.webdriver.common.by import By
from selenium.webdriver.support import expected_conditions as EC
from selenium.webdriver.support.ui import WebDriverWait
from selenium.webdriver.common.keys import Keys
from selenium.webdriver.common.action_chains import ActionChains
import pandas as pd
import logging
from dotenv import load_dotenv
import os

### ✅ Resultados Alcançados:
Criação de um código que navega todas as páginas do site e extrai todas as informações de promoções de cada jogo. Logo após a extração, carrega o código para o GBQ de acordo com as credenciais fornecidas pelo .env.

### ⚠️ Nota

O arquivo .env_sample do repositório é um exemplo do que deve-se colocar das credenciais da sua conta do Google BigQuery para ocorrer a carga de dados.

