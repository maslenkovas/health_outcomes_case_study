# Analysis of health conditions across US counties and health outcomes forecasting 📈

In this project we analyzed data from US Census, CDC, and other sources, and build a machine learning model to predict health outcomes across US counties.

The project consists of three main parts, which are:

1. Data collection, preprocessing
2. Exploratory Data Analysis (EDA)
3. Machine learning model building 

▪️ *Case_Study.ipynb* contains jupyter notebook file with the project itself.

▪️ *sunshine_data_scraper.py* contains python code for scraping average annual sunshine data by state (across US).

▪️ *Health_outomes_slides.pdf* is a document with the presentation slides for this project.


To reproduce the same working enviroment, please follow these steps:
1. Clone the repository to desired location on your machine 

```sh

git clone link-to-the-repo

```

2. Create conda enviroment with the correct python version and activate it

```sh

conda create --name myenv python=3.9
conda activate myenv

```
3. Install ipykernel package and enable your enviroment to show up in the list of available kernels in jupyter notebook
```sh

conda install ipykernel
python -m ipykernel install --user --name myenv --display-name "myenv"

```

4. Install required packages

```sh

conda install pandas==1.3.5

conda install openpyxl==3.0.10

conda install nbformat==5.7.0

conda install seaborn==0.12.2

conda install scipy==1.10.0

conda install scikit-learn==1.2.2

conda install yellowbrick==1.5

```

5. Install PLotly from the sourse 
```sh

conda install -c https://conda.anaconda.org/plotly plotly

```
6. Open jupyter notebook from the same directory

```sh

jupyter notebook

```
7. Change the Kernel to "myenv" using Menu bar.

Now you can run the notebook cells.



⚠️ Some visualizations may not be displayed properly when you open the notebook in Jupyter. If that is the case, I reccommend you to open it in Google Colab via following link:

Link to Google Colab notebook: [Health outcomes analysis in USA notebook](https://drive.google.com/file/d/1xf551s9jTIdktcEZglQmPvGWeRMbV4Hz/view?usp=sharing) 

Link to presentation slides: [Canva Slides](https://www.canva.com/design/DAFekOQcO8o/FJ4ngQXh_ip6pfsFX1nj1Q/view?utm_content=DAFekOQcO8o&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink)

