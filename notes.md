   29  git init testi
   36  git status
   37  git status
   38  git add .
   39  git status
   40  git commit -m "initial commit with new file"
   41  git status
   42  git log
   43  git status
   44  git diff
   45  git diff testi
   46  git diff --testi
   48  git add testi
   49  git add .
   50  git add .
   51  git status
   52  git commit -m "adding text to mallitiedosto"
   53  git push
   54  git push mallitiedosto
   55  git push
   56  git status
   57  git log
   58  git reflog
   62  git remote help
   67  git log
   72  git log
   73  git branch -M main
   74  git remote --help
   75  git remote -help
   76  git remote add origin https://github.com/eemiljka/gitti-testi.git
   77  git remote -v
   78  git push -u origin main
   79  git branch dev
   80  git branch
   81  git checkout dev
   82  git status
   84  git status
   85  git add .
   86  git commit -m "added another file"
   87  git status
   88  git checkout main
   89  git merge dev
   90  git diff dev
   91  git checkout -b dev-ville
   92  git status
   93  git add .
   94  git commit -m "removing mallitiedosto and update 'toinen tiedosto'"
   95  git status
   96  git checkout main
   97  git status
   98  git status
   99  git add .
  100  git commit -m "updated mallitiedosto with text"
  101  git add .
  102  git commit -m "adding text to toinen tiedosto"
  103  git status
  104  git merge dev-ville
  105  git status
  107  git status
  108  git add toinen-tiedosto 
  109  git add mallitiedosto 
  110  git status
  111  git commit -m "merged dev-ville to main"
  112  git status
  113  git log
  114  git reflog
  115  git push origin dev
  116  git push origin --o
  117  git push origin -o
  118  git push
  120  git pull origin main
  122  git checkout dev
  124  git checkout main
  125  git status
  126  git checkout dev
  127  git status'
  128  git status
  170  git clone https://github.com/mattpe/git-intro.git
  171  git remote help
  174  git remote -v
  175  git remote set-url origin https://github.com/eemiljka/git-intro.git
  176  git remote -v
  177  git add .
  178  git commit -m "first commit"
  179  git push
  183  history | grep "git " > notes.md
