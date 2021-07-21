## Functional programming presentation

There are two files. 

`index.html` is the slides for the presentation and is hosted on [Github pages](https://mancuniansam.github.io/fp-presentation/index.html)

`fp-with-cats.ipynb` is a jupyter notebook which was used to generate the slides.

You can run the jupyter notebook locally.

```shell
wget https://raw.githubusercontent.com/MancunianSam/fp-presentation/main/fp-with-cats.ipynb
docker run -itd --name jupyter -p 8888:8888 almondsh/almond:latest
docker cp fp-with-cats.ipynb jupyter:/home/jovyan/work/fp-with-cats.ipynb
```

You can then go to http://localhost:8888/ and follow the instructions to log into the notebook.

