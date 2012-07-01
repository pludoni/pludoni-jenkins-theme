# pludoni Jenkins Theme

This is a custom css-style for Jenkins CI-Server, build with compass/sass.

Features
* Link color: no :visited purple, subtle hover change
* Console output: Much improvement
  * dark background
  * good monospace font-stack
  * better readability (fontsize, line height)
* Font-Stack for headlines and body
* removes jenkins background picture (sorry!)

![Preview of Console](https://github.com/pludoni/pludoni-jenkins-theme/raw/master/images/preview1.png "Preview of Console")

![Preview of Font-Stack](https://github.com/pludoni/pludoni-jenkins-theme/raw/master/images/preview2.png "Preview of Font-Stack")

## Install

Install "Simple Theme Plugin" for Jenkins

```bash
cd /var/lib/jenkins/userContent
git clone git://github.com/zealot128/pludoni-jenkins-theme.git
```

put css in Jenkins Simple Theme Page:

```
http://SERVER/userContent/pludoni-jenkins-theme/stylesheets/style.css
```
