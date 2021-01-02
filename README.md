## Infinite Scrolling Using Flask/Javascript
This is a demonstration of a news feed that implements infinite scrolling using lazy loading. The idea is to provide better user experience and performance by loading smaller packets of data one at a time, going to the next packet when the user has scrolled far enough and asks for new data.

## Dependencies
Flask

## How To Run In a Windows Environment

From the terminal, clone the repo, then navigate into the repo.  
```
git clone https://github.com/wilfredogaldamez/flask-lazy-loading-feed-example.git
cd flask-lazy-loading-feed-example
```
Create a virtual environment, then activate the environment. Finally, install Flask using PIP.
```
python -m venv env
.\env\Scripts\activate
pip install Flask
```
Run the development server with
```
flask run
```
Use a browser to navigate to localhost:5000

## Author
[Article](https://pythonise.com/categories/javascript/infinite-lazy-loading) written by [Julian Nash](https://github.com/Julian-Nash).
