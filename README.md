# Vietnamese Poets - a Web Scraping & Modelling project
This project was done as a personal project for the purpose of self-learning Web-scraping and Parameter optimization for RFC.

#### -- Project Status: Completed August 2019

## Project Intro
http://thivien.net is an open-source database for Vietnamese literature. This personal project uses Beautiful Soup to extract data from the database and apply NLP modelling techniques to solve a classification problem: **Which author is most likely to write this sentence?**

### Methodologies
* Python
* Pandas, jupyter
* Random Forest Classifier (scikit-learn)
* Web Scraping (Beautiful Soup)

## File Descriptions
* [Jupyter Notebook - Extract Author's names](https://github.com/danieltpham/vietnamese-poets/blob/master/Author%20list%20scraping.ipynb)
* [Jupter Notebook - Extract Poem for a specific Author](https://github.com/danieltpham/vietnamese-poets/blob/master/Poem%20data%20scraping.ipynb)
* [Jupter Notebook - NLP Modelling Code](https://github.com/danieltpham/vietnamese-poets/blob/master/NLP.ipynb)
* [CSV - Sample Poem Extraction 1](https://github.com/danieltpham/vietnamese-poets/blob/master/XuanDieu.csv)
* [CSV - Sample Poem Extraction 2](https://github.com/danieltpham/vietnamese-poets/blob/master/HoXuanHuong.csv)
* [TXT - Additional Poem Dataset (secondary data)](https://github.com/danieltpham/vietnamese-poets/blob/master/truyen_kieu_data.txt)

## Usage Notes
* Run `Author list scraping.ipynb` to extract all Vietnamese authors' names from: https://www.thivien.net/searchauthor.php?Country=2&Page=1, and save to `authorlist.csv`
* Run `Poem data scraping.ipynb` to extract all poems from each author in `authorlist.csv`, and save to a csv file with the author's name.
* Run `NLP.ipynb` with the names of the authors to build a prediction model.

**_Please note: Web scraping will reach CAPTCHA limit! This project is built solely for self-practice purposes and should only be considered theoretical!_**
