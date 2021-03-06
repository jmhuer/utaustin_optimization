# utaustin_optimization2

homework, notes, and other relevant content used during online learning and optimization course.

benefits of this procedure
1. avoid having to download datasets (assuming they live in gdrive or aws)
2. directly push notebook from colab
3. quickly load previosuly used solutions or tools
4. optimization_tools live locally, but this repo never touches your computer 

## new homework
To open a new homework:
- 1. open new colab notebook 
- 2. save changes of colab to this repo e.i: homework43/homework43.ipynb

## edit existing file
- 1. find file in git
- 2. open in colab using google extension "open in colab"
- 3. save changes of colab to this repo e.i: homework43/homework43.ipynb

# tools

To import tools to google colab run the following:

for example, lets import function from utils
```python
#! git clone https://github.com/jmhuer/optimization_tools
from optimization_tools.utils import download_gdrive
```

lets use the tool to download google drive files

```python
# we pass the ID between two slashes '/{ID}/'  
a = '/1YDmMRdgRRJSKaWGR7c0g6mzj73Bzf9MU/'
b ='/1ZdnrCU7YotTAU0duRHTvUUF-k23lG7Wd/'
x = '/1c4YLkNr7Us61nD6OIdniDI3wac_-UQXS/'
y = '/1HYFUuBzHQoePElmLy1JOiB8ZmpxVpYPv/'

download_gdrive(a, "A.npy")
download_gdrive(b, "b.npy")
download_gdrive(x, "X.npy")
download_gdrive(y, "y.npy")
```



