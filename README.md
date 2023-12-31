# Web-Scraping-a-Books-Site-to-CSV-using-BeautifulSoup
Software:
1. [Github Account](https://github.com)
2. [Jupyter Notebook](https://jupyter.org/install)
3. [Website Scraped: Books To Scrape](https://books.toscrape.com/catalogue/page-2.html)


Libraries used:
1. BeautifulSoup
2. requests
3. pandas

### Clone the repository created to the local and Navigate to the local folder address in the local
git clone url_of_the_clone_local_from_website

### Copy the model ipynb code file in local.


### Create a new environment for the project. Go to the location of the project folder.
...
conda create -p venv python==3.7 -y
conda activate venv/
...

### In the folder, create a requirements file with libraries you needed to run the code. and then, In the environment
pip install -r requirements.txt

### Setting up configurations. Adding github logins to git CLI
git config --global user.name "name"
git config --global user.name "PujaAnkithaIvaturi"
git config --global user.email "email"

### Adding a file
git add requirements.txt
git status


### Knowledge on git status
![About git file upload working](image.png)

### Commiting files. Sending files from stageing area to local repository.
#### !!!! Important!!!! Always use -m message option in commit command to note what are the changes you are commiting or the files you are adding.
git commit -m "This commit includes requirement.txt and readme file."


### Final stage: Pushing files from local to remote repository
git push <remote> <branch>
git push origin main