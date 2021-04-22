# CAOTIC
High Contrast and Adaptive Optics laboratory testbeds community website

Welcome to the community website for astronomical testbeds! We are currently working on getting our 
website migrated to highconaotools.github.io, the original website can be found here:  
https://sites.google.com/view/highcontrastlabs/

## Local setup - MacOS

### Initial setup

If you use conda, make sure you have deactivated all your environments (including `base`) by doing `$ conda deactivate`.

*On a Mac*:
1. Install homebrew following the instructions on this page (if you don't have sudo privileges, get in touch with your machine manager):  
https://osxdaily.com/2018/03/07/how-install-homebrew-mac-os/

2. Install the package manager rbenv (more on rbenv [here](https://github.com/rbenv/rbenv) ) 
`$ brew install rbenv`

3. Set up rbenv in your shell  
`$ rbenv init`

4. Load rbenv automatically by appending the following to `~/.bash_profile`:
`eval "$(rbenv init -)"`

5. Close and reopen your terminal for the changes to take effect

6. Install ruby (more about using rbenv on a Mac [here](https://medium.com/@norton.seanm/a-guide-to-using-rbenv-mac-4ca211b1c713))  
`$ rbenv install 2.7.2`

7. Set your local ruby version to use  
`$ rbenv local 2.7.2`

8. Install bundler and jekyll  
`$ gem install bundler jekyll jemoji`

[Jekyll installation on Mac](https://jekyllrb.com/docs/installation/macos/)  
[Jekyll general installation docs](https://jekyllrb.com/docs/installation/)


### Render the website locally

1. cd into the repository
2. check out the branch that you want to build locally
3. `$ jekyll serve --livereload`
4. copy-paste the server address that appears in the terminal into a browser window (e.g. `http://127.0.0.1:4000/`)
