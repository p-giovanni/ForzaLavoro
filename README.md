# ForzaLavoro
This is a [Jupyter](https://jupyter.org/) project that I used to explore a dataset about the Italian work force.

I wanted to satisfy some curiosity I had about the composition the Italian work force, here some:

- nationality composition;
- gender;
- education level;
- contract type;
- occupational status;

The result are some chart that you can find in the [images](./images/) directory (sorry not translated in English).

## Project status
```diff
+ Completed
```
## Disclaimer
I do know very well Pandas, Matplotlib and I had a fairly good education in statistics but, as all the programmers, I do bugs.
So beware, I have checked the results as carefully as I can but nevertheless do not take for granted my result, check by yourself my 
code and decide if it it is correct or not.

## The dataset
I downloaded the data from the [Istat](https://www.istat.it/it/) site. Istat is the main Italian statistic institute.

You won't find the dataset in this repository because I do not own it, but you can freely download the data files and all the metadata files (my program uses the tab separated file format) from the Istat site (a registration is required).

## Installation and build
Clone this repository and than:

```bash
python3 -m venv venv
source ./venv/bin/activate
pip install -r requirements.txt
```
To run **Jupyter** use this command:
```bash
jupyter notebook --notebook-dir <path to your installation>/ForzaLavoro --port=9191
```
The browser should automatically open showing a page containing the link to my notebook.

