# Konfigürasyon

git config [--system | --global] [user.name | user.email | core.mail | merge.tool]

#################
# Yerel depo ekleme

git init 

.gitignore dosyası eklenir.
İstenilen dosya türleri git tarafından gözardı ettirilir.

git add -A
git commit -m "İlk commit"

##################
# Uzak depo ekleme
git init 
git add README.md
git commit -m "first"
git branch -M main 
git remote add [origin] https://github.com/username/project.git

# ya da
git clone https://kullanıcıadı:şifre@github.com/username/repository.git
#################

# Geçici kaydetme işlemi

git stash pop (siler)
git stash apply (yazar)
git stash drop [stash@1]
