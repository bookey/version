doc version control



1. create a new folder
2. Create a new file
3. init git lib

    pushd ~/Desktop
    
    git init





1st commit

    # pack
    git add h1.py
    
    # deliver to library
    git commit -m"first commit nothing in there"



update after 1st commit

update source code h1.py

    # before



    # after
    print('new content!')



status review

    git status



check update (diff between before and after)

    git diff



2nd commit

    # pack
    git add h1.py
    
    # deliver to library
    git commit -m"2nd commit add 1 one code"





version review

    git log





version select

    # view version number
    git log



version list below:

    commit 27ba205a124cbb5ee2b305da4620f3926f3b746d (HEAD -> master, origin/master)
    Author: bookey <47687241+bookey@users.noreply.github.com>
    Date:   Sat Feb 16 19:28:17 2019 +0800
    
        Update readme.md
    
    commit 82d2ff75a3a25eccd3ef0c7be8db798a5b27d7af
    Author: bookey <47687241+bookey@users.noreply.github.com>
    Date:   Sat Feb 16 19:26:35 2019 +0800
    
        Create readme.md
    
    commit 17b4fb3b2e753a09551269e24742ff3a456bc45f
    Author: bookey <47687241+bookey@users.noreply.github.com>
    Date:   Sat Feb 16 19:24:26 2019 +0800
    
        Create new_code.py



select a version

    # select a version
    git checkout 17b4fb3b2e753a09551269e24742ff3a456bc45f







code updated!

    git pull


