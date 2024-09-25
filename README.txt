This repository is for data exploration and analysis of the Cenozoic foraminifera dataset (data/foram_database_unstructured.xlsx)

#first you will need to use the Git large file system (Git-LFS)

**Step 1**: Download and Install Git-lfs ( *Git Large File Storage* ) from [**here**](https://git-lfs.github.com/).

**Step 2:** Setup Git lfs for your user account **git lfs install**.

**Step 3:** **If you have already tried to commit large files** and got the error then you must first undo the commit, use **git reset — soft HEAD~1** otherwise ignore this step.

**Step 4:** Select the file types that you want Git-lfs to manage using the command **git lfs track “*.csv”** , this creates a *.gitattributes* file.

**Step 5:** Add the *.gitattributes* file along with other files which need to be committed and push the changes.

#make_foram_database.py
Running the make_foram_database.py script produces a single dataframe that can then be used with other scripts.
This is saved to data/foram_database_'timestamp'.csv



#foram_BCa.py



