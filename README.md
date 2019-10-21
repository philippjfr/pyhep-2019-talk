# PyHEP 2019 Workshop Talk on the PyViz and HoloViz ecosystem

This talk builds on some of the latest features in the underlying
libraries and therefore requires a custom environment. To get set up
go through the following steps:

1. Clone the repo with:

    git clone https://github.com/philippjfr/pyhep-2019-talk.git

2. Set up the environment with:

    conda env create -f environment.yml
	
3. Activate the environment:

    conda activate pyhep-holoviz
	
4. Download the NYC Taxi dataset and update the reference to it in the notebook:

    https://s3.amazonaws.com/datashader-data/nyc_taxi_wide.parq
