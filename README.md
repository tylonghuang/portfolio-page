# About

This is a minimalistic portfolio webpage with a terminal-like aesthetic built with [Hugo](https://gohugo.io/). The live site can be found at [tylonghuang.com](https://www.tylonghuang.com).

![](/img/preview.png "Desktop View")

## Page Features

✔ Minimalist

✔ Responsive

✔ Performant

✔ Privacy-friendly

## Usage

In case you are interested in using this yourself or in developing this further, clone or fork this repo. To get the theme as a submodule, run:
```
$ git clone --recurse-submodules
$ cd portfolio-page
```
To update the theme, run:
```
$ git submodule update --recursive --remote
```
Once you have set everything up, you can run the following to test the page locally:
```
$ hugo server -t hugo-theme-shell -w -D
```
In case there is an error, make sure that you have the latest Hugo version. You can update Hugo with Chocolatey by running:
```
$ choco upgrade hugo-extended -y
```

## Credit

... goes to all the contributors of [hugo-theme-shell](https://github.com/Yukuro/hugo-theme-shell).
