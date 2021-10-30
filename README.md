# dev_settings

# Use raw preview to copy these settings

# Shell alias
-='cd -'
...=../..
....=../../..
.....=../../../..
......=../../../../..
1='cd -'
2='cd -2'
3='cd -3'
4='cd -4'
5='cd -5'
6='cd -6'
7='cd -7'
8='cd -8'
9='cd -9'
_='sudo '
afind='ack -il'
arun='react-native run-android'
dbload='python manage.py loaddata'
dbmake='python manage.py makemigrations'
dbmigrate='python manage.py migrate'
dshell='python manage.py shell'
egrep='egrep --color=auto'
emacs='emacs -nw'
fgrep='fgrep --color=auto'
g=git
ga='git add'
gaa='git add --all'
gam='git am'
gama='git am --abort'
gamc='git am --continue'
gams='git am --skip'
gamscp='git am --show-current-patch'
gap='git apply'
gapa='git add --patch'
gapt='git apply --3way'
gau='git add --update'
gav='git add --verbose'
gb='git branch'
gbD='git branch -D'
gba='git branch -a'
gbd='git branch -d'
gbda='git branch --no-color --merged | command grep -vE "^([+*]|\s*($(git_main_branch)|$(git_develop_branch))\s*$)" | command xargs git branch -d 2>/dev/null'
gbl='git blame -b -w'
gbnm='git branch --no-merged'
gbr='git branch --remote'
gbs='git bisect'
gbsb='git bisect bad'
gbsg='git bisect good'
gbsr='git bisect reset'
gbss='git bisect start'
gc='git checkout'
'gc!'='git commit -v --amend'
gca='git commit -v -a'
'gca!'='git commit -v -a --amend'
gcam='git commit -a -m'
'gcan!'='git commit -v -a --no-edit --amend'
'gcans!'='git commit -v -a -s --no-edit --amend'
gcas='git commit -a -s'
gcasm='git commit -a -s -m'
gcb='git checkout -b'
gcd='git checkout $(git_develop_branch)'
gcf='git config --list'
gcl='git clone --recurse-submodules'
gclean='git clean -id'
gclone='git clone&quot;'
gcm='git checkout $(git_main_branch)'
gcmsg='git commit -m'
'gcn!'='git commit -v --no-edit --amend'
gco='git checkout'
gcor='git checkout --recurse-submodules'
gcount='git shortlog -sn'
gcp='git cherry-pick'
gcpa='git cherry-pick --abort'
gcpc='git cherry-pick --continue'
gcs='git commit -S'
gcsm='git commit -s -m'
gcss='git commit -S -s'
gcssm='git commit -S -s -m'
gd='git diff'
gdca='git diff --cached'
gdct='git describe --tags $(git rev-list --tags --max-count=1)'
gdcw='git diff --cached --word-diff'
gds='git diff --staged'
gdt='git diff-tree --no-commit-id --name-only -r'
gdup='git diff @{upstream}'
gdw='git diff --word-diff'
gf='git fetch'
gfa='git fetch --all --prune --jobs=10'
gfg='git ls-files | grep'
gfo='git fetch origin'
gg='git gui citool'
gga='git gui citool --amend'
ggpull='git pull origin "$(git_current_branch)"'
ggpur=ggu
ggpush='git push origin "$(git_current_branch)"'
ggsup='git branch --set-upstream-to=origin/$(git_current_branch)'
ghh='git help'
gignore='git update-index --assume-unchanged'
gignored='git ls-files -v | grep "^[[:lower:]]"'
git-svn-dcommit-push='git svn dcommit && git push github $(git_main_branch):svntrunk'
gk='\gitk --all --branches &!'
gke='\gitk --all $(git log -g --pretty=%h) &!'
gl='git pull'
glg='git lg'
glgg='git log --graph'
glgga='git log --graph --decorate --all'
glgm='git log --graph --max-count=10'
glgp='git log --stat -p'
glo='git log --oneline --decorate'
globurl='noglob urlglobber '
glod='git log --graph --pretty='\''%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%ad) %C(bold blue)<%an>%Creset'\'
glods='git log --graph --pretty='\''%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%ad) %C(bold blue)<%an>%Creset'\'' --date=short'
glog='git log --oneline --decorate --graph'
gloga='git log --oneline --decorate --graph --all'
glol='git log --graph --pretty='\''%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%ar) %C(bold blue)<%an>%Creset'\'
glola='git log --graph --pretty='\''%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%ar) %C(bold blue)<%an>%Creset'\'' --all'
glols='git log --graph --pretty='\''%Cred%h%Creset -%C(auto)%d%Creset %s %Cgreen(%ar) %C(bold blue)<%an>%Creset'\'' --stat'
glp=_git_log_prettily
glum='git pull upstream $(git_main_branch)'
gm='git commit -m'
gma='git merge --abort'
gmom='git merge origin/$(git_main_branch)'
gmtl='git mergetool --no-prompt'
gmtlvim='git mergetool --no-prompt --tool=vimdiff'
gmum='git merge upstream/$(git_main_branch)'
gp='git push'
gpap='git pull origin master && git push origin master'
gpd='git push --dry-run'
gpf='git push --force-with-lease'
'gpf!'='git push --force'
gpoat='git push origin --all && git push origin --tags'
gpr='git pull --rebase'
gpristine='git reset --hard && git clean -dffx'
gpsup='git push --set-upstream origin $(git_current_branch)'
gpu='git push upstream'
gpull='git describe --contains --all HEAD|xargs git pull origin'
gpush='git describe --contains --all HEAD|xargs git push origin'
gpv='git push -v'
gr='git remote'
gra='git remote add'
grb='git rebase'
grba='git rebase --abort'
grbc='git rebase --continue'
grbd='git rebase $(git_develop_branch)'
grbi='git rebase -i'
grbm='git rebase $(git_main_branch)'
grbo='git rebase --onto'
grbs='git rebase --skip'
grep='grep --color=auto'
grev='git revert'
grh='git reset'
grhh='git reset --hard'
grm='git rm'
grmc='git rm --cached'
grmv='git remote rename'
groh='git reset origin/$(git_current_branch) --hard'
grrm='git remote remove'
grs='git restore'
grset='git remote set-url'
grss='git restore --source'
grst='git restore --staged'
grt='cd "$(git rev-parse --show-toplevel || echo .)"'
gru='git reset --'
grup='git remote update'
grv='git remote -v'
gs='git status'
gsb='git status -sb'
gsd='git svn dcommit'
gsh='git show'
gsi='git submodule init'
gsps='git show --pretty=short --show-signature'
gsr='git svn rebase'
gss='git status -s'
gst='git status'
gsta='git stash push'
gstaa='git stash apply'
gstall='git stash --all'
gstc='git stash clear'
gstd='git stash drop'
gstl='git stash list'
gstp='git stash pop'
gsts='git stash show --text'
gstu='gsta --include-untracked'
gsu='git submodule update'
gsw='git switch'
gswc='git switch -c'
gswd='git switch $(git_develop_branch)'
gswm='git switch $(git_main_branch)'
gtl='gtl(){ git tag --sort=-v:refname -n -l "${1}*" }; noglob gtl'
gts='git tag -s'
gtv='git tag | sort -V'
gunignore='git update-index --no-assume-unchanged'
gunwip='git log -n 1 | grep -q -c "\-\-wip\-\-" && git reset HEAD~1'
gup='git pull --rebase'
gupa='git pull --rebase --autostash'
gupav='git pull --rebase --autostash -v'
gupv='git pull --rebase -v'
gwch='git whatchanged -p --abbrev-commit --pretty=medium'
gwip='git add -A; git rm $(git ls-files --deleted) 2> /dev/null; git commit --no-verify --no-gpg-sign -m "--wip-- [skip ci]"'
history=omz_history
imgcat=/Users/apple/.iterm2/imgcat
imgls=/Users/apple/.iterm2/imgls
irun='react-native run-ios'
it2api=/Users/apple/.iterm2/it2api
it2attention=/Users/apple/.iterm2/it2attention
it2check=/Users/apple/.iterm2/it2check
it2copy=/Users/apple/.iterm2/it2copy
it2dl=/Users/apple/.iterm2/it2dl
it2getvar=/Users/apple/.iterm2/it2getvar
it2git=/Users/apple/.iterm2/it2git
it2setcolor=/Users/apple/.iterm2/it2setcolor
it2setkeylabel=/Users/apple/.iterm2/it2setkeylabel
it2ul=/Users/apple/.iterm2/it2ul
it2universion=/Users/apple/.iterm2/it2universion
jitu='sudo init 0'
l='ls -lah'
la='ls -lAh'
ll='ls -lh'
ls='ls -G'
lsa='ls -lah'
md='mkdir -p'
mshell='python manage.py shell'
notebook='/Users/witchkings/Library/Python/3.7/bin/jupyter notebook'
npmau='npm audit fix'
npmir='npm install  && react-native run-ios --simulator="iPhone 11 Pro"'
npmrun='open -a Simulator && npm start'
podi='cd ios && pod install && cd ..'
rclean='watchman watch-del-all && rm -rf node_modules && npm install && npm cache clean --force'
rd=rmdir
run-help=man
runserver='python manage.py runserver 0.0.0.0:8000'
which-command=whence


# vs code settings
{
    "gitlens.keymap": "chorded",
    "editor.wordWrap": "on",
    "workbench.editor.enablePreview": false,
    "workbench.editor.enablePreviewFromQuickOpen": false,
    "editor.fontSize": 19,
    "editor.copyWithSyntaxHighlighting":false,
    "editor.rulers": [
        79,
        120
    ],
    "editor.tabSize": 4,
    "python.linting.lintOnSave": true,
    "python.pythonPath": "/Users/apple/Installs/envs/vscode/bin/python",
    "python.linting.enabled": true,
    "python.linting.pylintEnabled": true,
    "python.linting.pylintPath": "/Users/apple/Installs/envs/vscode/bin/pylint",
    "python.formatting.provider": "autopep8",
    "python.formatting.autopep8Path": "/Users/apple/Installs/envs/vscode/bin/autopep8",
    "python.formatting.autopep8Args": [
        "--max-line-length",
        "120",
        "--experimental"
    ],
    "editor.suggestSelection": "first",
    "editor.formatOnSave": true,
    "python.languageServer": "Pylance",
    "javascript.format.semicolons": "insert",
    "[python]": {
        "editor.codeActionsOnSave": {
            "source.organizeImports": true
        }
    },
    "workbench.editorAssociations": {
        "*.ipynb": "jupyter-notebook"
    },
    "security.workspace.trust.untrustedFiles": "open",
    "html.format.enable": false,
    "python.defaultInterpreterPath": "/Users/apple/Installs/envs/vscode/bin/python",
    "security.workspace.trust.banner": "never",
    "security.workspace.trust.startupPrompt": "never",
    "telemetry.enableCrashReporter": false,
    "telemetry.enableTelemetry": false,
    "notebook.cellToolbarLocation": {
        "default": "right",
        "jupyter-notebook": "left"
    },
    "files.watcherExclude": {
        "**/.git/objects/**": true,
        "**/.git/subtree-cache/**": true,
        "**/node_modules/**": true,
        "**/env/**": true,
        "**/venv/**": true,
        "env-*": true
    },
    "search.exclude": {
        "**/node_modules": true,
        "**/bower_components": true,
        "**/env": true,
        "**/venv": true
    },
    "[typescriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "prettier.enable": true,
    "prettier.useTabs": true,
    "prettier.printWidth": 220,
    "workbench.colorTheme": "Popping and Locking Black Theme"
}
