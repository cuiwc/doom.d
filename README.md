# Things to install in addition to Doom Emacs

## C/C++ auto completion 

``` sh
# Install llvm
$ brew install llvm

# Install irony server
M-x irony-install-server

# Create a .clang_complete file for source folders
cat >> .clang_complete <<EOF
-I...
-D...
EOF
```

## C/C++ navigation

``` sh
# Install cscope
$ brew install cscope

# Use cscope
C-c s ...
```

## Install Universal Ctags

``` sh
# Install Universal Ctags
# Refer to: https://github.com/universal-ctags/homebrew-universal-ctags
$ brew install --HEAD universal-ctags/universal-ctags/universal-ctags
```
