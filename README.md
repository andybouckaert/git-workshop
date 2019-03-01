Aanmaken
Directory 
    CMD
        mkdir github
        git init
        meestal gebruikt offline via cmd 
    GUI
        gebruiken bij Internet verbinding   
        https://github.com/andybouckaert/git-workshop
        copieer link
        git clone https://github.com/andybouckaert/git-workshop
    
    Test
        git status
        //geef status van de situatie
        git status -s
        ?? -> wat doe ik ermee
        A? -> file is ge-add ? modified na gesaved
        AM -> file is ge-add en modified
     git add README.md  
     git status -s
        A  enkel -> enkel gesaved
    git add . -> alles adden
    git commit -m 'first commit'
        -m = message
    git log
Uit editor esc -> :q! verlaat je de editor
uit git log
    HEAD -> branche
    Master -> waar sta je in de history

aanpassing file
    git clone 'file'
    git commit -m 'geef tekst mee wat je veranderd'
    git log
        toont de verschillende veranderingen  
        git branche "branche"
            README is naar branche veranderd ipv master
        git checkout branche
    als aanpassing doen