# This is my second end to end project

### First init the git
...
open git bash and type : git init
...

### Adding the file 
...
git add abc.txt (For adding one file)

git add . (for adding all files)
...

### Commit the File 
...
git commit -m "This is my first commit"
...

IMP STEPS : 
1. add the file from source Control (Situated on Left side of your VS code)
2. Click on + to add 
3. Type any msg eg: This is my first Commit
4. Click on Commit
5. click on publish Branch and then click to public repo
NOTE : Do not create the repo before , it automatically created!
and if u r doing first time then it will give the signin option

...
Now create the abc.txt file, and then commit it (it is for just understanding that how to commit the file)
...

...
Step in Repo : 
1. click on add file ---> create a new file ---> name your file : .gitignore
2. Then select the template as Python (if you develop in Python language)
3. then click on commit changes and the file is added to your git Repo
...

...
### Licence File
1. click on add file ---> create a new file ---> name your file : LICENCE
2. choose a template ---> ok ---> MIT LICENCE ---> Review and Submit ---> Commit Changes
...

...
### git pull
type in git bash : git pull 
it can fetch all the changes from the Repo
and then push the changes (See from IMP steps)
...

...
create : init_setup.sh  (also called as shell script)

NOTE : This is only for Mac aur Linux not for windows

it can automatically do the steps like creating enviroment,installing packages etc.

then type bash init_setup.sh to create the env (Ensure that your python interpretor is Conda(base))

first it will show error in requirements bcz we cannot add any requirements 

NOTE : sometimes , it will not create the env in windows only 
so u have to create enviroment manually!

u have to also activate the env
bash :- source activate ./env
cmd :- conda activate (env_path)
...

...
template.py ---> all setup 
...

...
then make test.py and make a directory code in it for jupyter nb
...

...
### Requirements 
give some requirements in requirements.txt
and run the init_setup.sh (delete the env then run it)

then type pip list to show all available requirements
and in this we doesnt see the src(DiamondPricePrediction) in it so for adding it...
...

...
run the setup.py file :- python setup.py install (in gitbash)
...

...
-e . is basically used to automatically download the DiamondPricePrediction, when 
we write the pip install -r requirement.txt
...
