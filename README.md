# PolarsVSPandas
A Polars vs Pandas benchmark to analyze what are the strong points of each framework

## Steps to run this Repo 
- You must have installed Docker in your computer and download compress the datasource and put the file in the directory where you cloned the repo
- Go to the directory where you cloned the repo in the terminal
- Run the following command docker run --rm -p 8889:8888 -v "$(pwd):/home/jovyan/work" quay.io/jupyter/base-notebook start-notebook.py --NotebookApp.token='my-token'
- Go to localhost:8889 and in the main page of jupyter lab write my-token
- Go to work directory and have fun :)

## References
- https://docs.docker.com/guides/jupyter/ (Jupyter lab Container)
- https://www.kaggle.com/datasets/anandshaw2001/imdb-data (Source of data)
- https://github.com/pola-rs/polars/issues/20475 (Polars slower while filtering)
- https://stackoverflow.com/questions/75530375/polars-vs-pandas-size-and-speed-difference (Polars slower while performing some actions)
- https://docs.pola.rs (Polars documentation)