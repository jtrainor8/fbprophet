# fbprophet

Facebook Profet - Inductory use

-download latest version of anaconda (https://www.anaconda.com/products/individual#linux)

-install anaconda (python 3.7) 
	bash ~/PATH_TO_DOWNLOAD/Anaconda3-2020.02-Linux-x86_64.sh
-restart terminal after install
-verify installation
	conda list
	anaconda-navigator 	->(opens navigator if successful install) 
-create enviornment
	conda create --name <name_of_env> python=3.6
	conda activate <naame_of_env>
-intall fbpropher using pip and conda-forge
	conda install -c conda-forge fbprophet

optional:
-install plotly for interractive plots
	conda install -c plotly plotly=4.8.1
-if using it on the jupyter notebook
	conda install "notebook>=5.3" "ipywidgets>=7.2"

*special note*
-if using a juypter notebook with a conda enviornment you need to include the env, look up pathing it.
	conda install -c anaconda ipykernel
	python -m ipykernel install --user --name=nameOfEnv



