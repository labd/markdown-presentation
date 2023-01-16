# LabDigital Markdown presentation

Create presentations in Markdown with a LabDigital style.

## Quick start

Download a simple static file server and run this folder. E.g.

```bash
yarn global add http-server
http-server -c-1 .
```

The `-c-1` is to disable caching.

You can now view your presentation at http://localhost:8080

## Create your own presentation

Edit `my-presentation.md` to create your presentation using Markdown.

You can improve and add custom styles in `style.css`.

For more information on the presentation specific Markdown syntax and how styling the presentation works, look at the [Remark](https://github.com/gnab/remark/wiki) documentation.

Current supported syntax highlighting include

- js(x)/ts(x)
- (s)css
- python
- go
- bash
- html

If you want more, go to [prismjs.com](https://prismjs.com/download.html) and replace the prism.js and prism.css with your new download.

## Presenting

While viewing your presentation:

- Press "P" to go into presentation mode and
- Press "C" to create a presentation copy that you can display on another screen.

For more tips check the documentation of [Remark](https://github.com/gnab/remark/wiki)

## PDF export

Simply print the html file to pdf inside chrome.
