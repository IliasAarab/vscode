To install extensions:

```{bash}
cat vscode-extensions-list.txt | xargs -L 1 code --install-extension
```

To install [oh-my-bash](https://github.com/ohmybash):

 - export proxies
 - export requests_ca_bundle (InterceptionRootCA)
 - ```{bash}  sh -c "$(curl --insecure -fsSL https://raw.github.com/ohmybash/oh-my-bash/master/tools/install.sh)" ```
 - enter windows credentials when asked
