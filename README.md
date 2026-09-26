git and github  assessment  
 git init
  502  git config user.name moinuddin
  503  git config user.email deedadmoinuddin7@gmail.com
  504  git branch -M master main
  505  touch a.txt
  506  git add .
  507  git status
  508  git commit -m "added empty a.txt " a.txt
  509  git log --oneline
  510  touch login.py home.py logout.py
  511  git add login.py
  512  git status
  513  git add home.py
  514  git add logout.py
  515  git status
  516  git commit -m "added empty login.py " login.py
  517  git commit -m "added empty home.py " home.py
  518  git commit -m " added empty logout.py " logout.py
  519  git switch -c wishlist
  520  git log --oneline
  521  nano login.py
  522  cat login.py
  523  git add .
  524  git status
  525  git commit -m "added  content in login.py " login.py
  526  nano home.py
  527  git add .
  528  git commit -m "added content in home.py " home.py
  529  nano logout.py
  530  git add .
  531  git commit -m "added content in logout.py " logout.py
  532  git log --oneline
  533  nano home.py
  534  git add.
  535  git switch main
  536  git stash push
  537  git stash list
  538  git switch main
  539  cat home.py
  540  nano home.py
  541  nano login.py
  542  git status
  543  git status login.py
  544  git add login.py
  545  git commit -m "added content in login.py " login.py
  546  git log --oneline
  547  git merge wishlist
  548  git merge whislist
  549  git merge  main wishlist
  550  git  status
  551  git stash push
  552  git merge main wishlist
  553  nano login.py
  554  git status
  555  git add login.py
  556  git commit -m " fixed the conflict " login.py
  557  git merge main whislist
  558  git abort --merge
  559  git merge --abort
  560  git status
  561  git merge maoin wishlist
  562  git merge main wishlist
  563  nano login.py
  564  git status
  565  git  commit
  566  git commit merge
  567  git add login.py
  568  git commit
  569  git log --oneline
  570  nano logout.py
  571  git checkout logout.py
  572  git remote add origin
  573  Updated 1 path from the index
  574  git remote add origin  https://github.com/deedad13/git-mock-repository.git
  575  git remote -v
  576  git log --oneline
  577  git push origin main
  578  git switch -c checkout
  579  touch checkout.py
  580  git add .
  581  git commit -m "added empty checkout.py " checkout.py
  582  git log --oneline
  583  git switch main
  584  git merge main  checkout
  585  git log --oneline
  586  git revert 1c740c4
  587  git log --oneline
  588  git switch checkout
  589  nano checkout.py
  590  git add .
  591  git commit -m " added content in checkout.py " checkout.py
  592  git push origin checkout
  593  git log --oneline
  594  git revert 3b9fda5
  595  git log --oneline
  596  git push
  597  git push origin checkout
  598  history
