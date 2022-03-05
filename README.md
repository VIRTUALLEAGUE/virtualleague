<!--![header](https://capsule-render.vercel.app/api?type=cylinder&color=ED4B1C&height=300&section=header&text=Guhyun%27s%20gitgub&fontSize=60)-->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=cylinder&color=ED4B1C&height=200&section=center&text=Guhyun%27s%20Github&fontSize=60">
 </p>
<p align="center">
 <!--<img src="https://img.shields.io/badge/solved.ac-G4-gold"/>-->
  <a href="https://www.acmicpc.net/user/usw20"><img src="https://img.shields.io/badge/solved.ac-G4-gold"></a>
</p>
<p align="center">
 <img src="https://img.shields.io/badge/Python-3766AB?style=flat-square&logo=Python&logoColor=white"/></a>
 <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=C&logoColor=white"/></a>
 <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/></a>
 <img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=MariaDB&logoColor=white"/>
 </p>
 <p align="center">
 <img src="https://img.shields.io/badge/Pycharm-07C85F?style=flat-square&logo=Pycharm&logoColor=white"/></a>
 <img src="https://img.shields.io/badge/Visual Studio-5C2D91?style=flat-square&logo=Visual Studio&logoColor=white"/></a>
 <img src="https://img.shields.io/badge/Eclipse IDE-2C2255?style=flat-square&logo=Eclipse IDE&logoColor=white"/></a>
 <img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat-square&logo=Visual Studio Code&logoColor=white"/>
 </p>
<p align="center">
 <img src="https://img.shields.io/badge/Blender-F5792A?style=flat-square&logo=Blender&logoColor=white"/></a>
 <img src="https://img.shields.io/badge/Unreal Engine-0E1128?style=flat-square&logo=Unreal engine&logoColor=white"/></a>
 <img src="https://img.shields.io/badge/SketchUp-005F9E?style=flat-square&logo=SketchUp&logoColor=white"/></a>
 <img src="https://img.shields.io/badge/After Effect-9999FF?style=flat-square&logo=Adobe After Effects&logoColor=white"/>
 </p>
 

 ## 🕵 Who am I? 🕵
 I graduated from Suwon University's Department of Information Security.<br>
 Recently, I turned from Game Producer to Developer And i have been studying.
 
 
## 🕴 Work Experience 🕴
2020 - 2021 / 텅빈스튜디오 / 창업자 & CEO
- [도전 K-스타트업 2021] 예하리그 [학생창업유망팀 300] 최종선발
- 부총리 겸 교육부 장관 인증서 수여
- 교육부, 과학기술정보통신부 공동주최 [전국민대상 모의투자대회], 626,000,000원 유치 성공
- AI R&D, 기획, Motion Capture, 3D, Cinematic, 투자유치, 사업 등 업무 수행
- 버추얼 프로덕션 개발 프로젝트 총괄
- 메타버스 게임 개발 프로젝트 총괄

## 🎖 Award 🎖

- 2020 한이음 ICT 공모전
  * 입선상 한국정보산업연합회 회장상
- 2019 제 5회 국회도서관 해커톤 : 개방형클라우드 플랫폼 Paas Ta 기반 서비스 개발 공모전
  * 금상 과학기술정보통신부 장관상

Markdown is a lightweight markup language based on the formatting conventions
that people naturally use in email.
As [John Gruber] writes on the [Markdown site][df1]

> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

This text you see here is *actually- written in Markdown! To get a feel
for Markdown's syntax, type some text into the left window and
watch the results in the right.

## Tech

Dillinger uses a number of open source projects to work properly:

- [AngularJS] - HTML enhanced for web apps!
- [Ace Editor] - awesome web-based text editor
- [markdown-it] - Markdown parser done right. Fast and easy to extend.
- [Twitter Bootstrap] - great UI boilerplate for modern web apps
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework [@tjholowaychuk]
- [Gulp] - the streaming build system
- [Breakdance](https://breakdance.github.io/breakdance/) - HTML
to Markdown converter
- [jQuery] - duh

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

## Installation

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```

## Plugins

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

#### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
