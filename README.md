## Open Learning Resources by Wilyer Engineering 





### How to contribute to this project?
#### Install NodeJS and Git 

#### <a name="development"></a> Development

To get started with WilyerEngineering/learn  **development**, you need to install [NodeJS](https://nodejs.org/en/) and [Git](https://git-scm.com/).


- After Installation Make Sure following 3 Commands work as shown in the given image.

```bash
$ node --version
```
npm will install automatically when you install NodeJS
```bash
$ npm --version
```
```bash
$ git --version
```


![image](https://user-images.githubusercontent.com/33034184/92590998-bdc71080-f2ba-11ea-88cc-31798d3aa214.png)



 Then install `hexo-cli` globally:

```bash
$ npm install hexo-cli -g
```

Get the theme source and install the dependencies:

```bash
$ git clone https://github.com/WilyerEngineering/learn.git 

$ cd learn && npm install
```


If you want to update the visual aspects of your front-end, we suggest using our [user documentation](https://zalando-incubator.github.io/hexo-theme-doc) site as a playground for previewing your changes. First, [link](https://docs.npmjs.com/cli/link) the theme package globally with:

```bash
$ cd learn && npm link
```




Now [link](https://docs.npmjs.com/cli/link) the theme package as a dependency (this will use your local version):

```bash
$ npm link learn
```

Finally run the built-in server:

```bash
$ hexo s
```

Open your browser at http://localhost:4000, and hopefully you'll see the documentation site up and running.


**Great Now  http://localhost:4000/learn will be live on your local system.**

## Understand Development Pipline
There is a branch named `master` which is automatically created and updated as per the commits made into branch named `source`.

There is a branch named `dev` which is for development and updates so if you do some changes to the code make sure you make a pull request in dev branch so that your updates can be tested by the core team and merged to `source` branch after testing.





#### Wilyer Engineering's Open Sourced Learning Website is made possible by Hexo and hexo-theme-doc details of which can be found below.
#### Meta Data About the Template and Design
This project is a skeleton for a documentation website using [Hexo](https://hexo.io) and [hexo-theme-doc](https://github.com/zalando-incubator/hexo-theme-doc).   
You can use it to quickly bootstrap your documentation website.

The seed contains the required structure and files to use Hexo and the theme, plus dummy content to show the usage of the main features of the theme.

## Getting Started

To get started have a look to https://zalando-incubator.github.io/hexo-theme-doc/get-started.html

## More Informations

For more informations please visit the [user documentation website](https://zalando-incubator.github.io/hexo-theme-doc).

## License

The MIT License (MIT)

Copyright 2017, Zalando SE

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
