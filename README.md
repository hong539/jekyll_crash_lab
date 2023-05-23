# jekyll_crash_lab

Try to using jekyll to make some static web pages and also crash.

## setup

* [My ruby setup](https://github.com/hong539/setup_dev_environment/tree/main/programing_languages/ruby)

## play with jekyll

* [jekyll/step-by-step](https://jekyllrb.com/docs/step-by-step/01-setup/)

```shell
git clone git@github.com:hong539/jekyll_crash_lab.git
cd jekyll_crash_lab/

which bundle
which jekyll

#Using gem install jekyll bundle
gem install jekyll bundler

#Add this to ~/.bashrc
#extea Gem setting
export PATH="$PATH:/home/hong/.local/share/gem/ruby/3.0.0/bin"

#And reload ~/.bashrc
source ~/.bashrc

#jekyll
jekyll build
jekyll build -s src/

#Does jekyll build and runs it on a local web server at http://localhost:4000, rebuilding the site any time you make a change.
jekyll serve
jekyll serve -s src/root/

#Clean the site (removes site output and metadata file) without building.
jekyll clean
```