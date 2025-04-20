# Applied Machine Learning: Algorithms
This is the repository for the LinkedIn Learning course `Applied Machine Learning: Algorithms`. The full course is available from [LinkedIn Learning][lil-course-url].

![lil-thumbnail-url]

<p>With the growing importance of machine learning in almost every sector, professionals need a deeper understanding and practical approach to implementing ML algorithms effectively.
 </p><p>
This course covers commonly used machine learning algorithms. Instructor Matt Harrison focuses on non-deep learning algorithms, covering PCA, clustering, linear and logistic regression, decision trees, random forests, and gradient boosting.
 </p><p>
Join Matt in this course to understand common ML algorithms, learn their pros and cons, and develop hands-on skills to leverage them by following along with challenges and solutions in GitHub Codespaces.

### Instructor

Matt Harrison

Python and Data Science Corporate Trainer, Author, Speaker, Consultant                   

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/matt-harrison?u=104).



[0]: # (Replace these placeholder URLs with actual course URLs)

[lil-course-url]: https://www.linkedin.com/learning/applied-machine-learning-algorithms-23750732
[lil-thumbnail-url]: https://media.licdn.com/dms/image/D560DAQG8-Uu_NXvIPQ/learning-public-crop_675_1200/0/1712273059536?e=2147483647&v=beta&t=MsAmeJayaZcGlo45adY21zt_BlzTqqZdqmC9t1b7XPc

===

### Install Miniconda

Follow the guide below to install Miniconda:  
https://www.anaconda.com/docs/getting-started/miniconda/install#quickstart-install-instructions

For example, copy and paste the following command to CMD in Windows to install it:  
```
curl https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe -o .\miniconda.exe
start /wait "" .\miniconda.exe /S
del .\miniconda.exe
```

Verify your install  
Search for "Anaconda Prompt" and select it to run.  
Run command such as `conda list` for installed packages or `conda --version` for conda version.  

## Using Jupyter Notebook
1. Create a new conda env: `conda create -n amla python=3.12`  
2. Activate the new env: `conda activate amla`  
3. Install Jupyter Notebook: `conda install jupyter`
4. Launch Jupyter Notebook: `jupyter notebook`

## K-means
Install packages used in this section:  
`conda install scikit-learn matplotlib yellowbrick datasets pandas plotly`  

## Problems
* UMAP package does not support Python 3.12 at present 