# Notes App

This project aims to create a Notes app.

## About The Project

![Notes App screenshot](https://user-images.githubusercontent.com/69361901/197420938-d85f28c3-9ae6-48d6-bbd8-0682af489f8d.png)

The project features two components: Sidebar and Editor. The Markdown editor was created using the react-mde and showdown packages.

The following [styles](https://github.com/andrerpena/react-mde#styling) from React-mde were added:
```
import 'react-mde/lib/styles/css/react-mde-all.css';
```

To resolve the [Build fails on peer dependency](https://docs.netlify.com/configure-builds/troubleshooting-tips/#build-fails-on-peer-dependency-conflict) conflict when deploying with Netlify, the NPM_FLAGS environment variable was set to pass `--force` to the npm install command.

Live Site: Live Site: https://notes-app-by-alphfonti.netlify.app/

## Built with

- [React](https://reactjs.org/)
- [Showdown](https://showdownjs.com/)
- [NanoID](https://github.com/ai/nanoid)
- [react-mde](https://github.com/andrerpena/react-mde#readme)
- [SplitJS](https://split.js.org/)

## Acknowledgements

- [Bob Ziroll](https://github.com/bobziroll)
