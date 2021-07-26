<img src="images/alelo_logo.png" width="200"></a>

# Machine Learning Challenge

The project contains the code and analysis to machine learning challenge from Alelo.

## Getting Started

There are two ways to run the test:
- Google Colab (preferable)
- Docker

### Prerequisites
 
- [Google Colab](http://colab.research.google.com/) or
- [Docker](https://www.docker.com)


### Installing

- Google Colab

There is no need to install anything, you can access the links at the .ipynb in the nootbooks folder.

- Docker

Follow the instructions at [link](https://docs.docker.com/engine/install/).

Then

    docker pull fernandofsilva

## Running

Follow the instructions to run the codes:

### Google Colab

The links are available in the notebooks. 

<table class="tfo-notebook-buttons" align="left">
  <td>
    <img src="images/colab_logo.png" />Run in Google Colab</a>
  </td>
</table>


### Docker

After pull the image run the following command:

    docker run -it --rm -p 8888:8888 alelo start.sh jupyter lab

The terminal will show the link to the jupyter server, as below:

    Jupyter Notebook 6.4.0 is running at:
    http://b9a1f81723e5:8888/?token=635e85a06482cad5553d3adedcd104f08aaebc06650a464c
     or http://127.0.0.1:8888/?token=635e85a06482cad5553d3adedcd104f08aaebc06650a464c

You just need to click in the link, and it will open in browser.

## Built With

  - [Sklearn](https://scikit-learn.org) - Machine Learning in Python.
  - [pandas](https://pandas.pydata.org) - Data analysis and manipulation.


## Versioning

1.0 First Version

## Authors

  - **Fernando Silva** - *First Version*

## License

This project is licensed under the [MIT License](LICENSE.md)
Creative Commons License - see the [LICENSE.md](LICENSE.md) file for
details.
