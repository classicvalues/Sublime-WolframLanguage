
## 1.4.0 - 25 Oct, 2021

Fix 415574: unrecognized symbol followed by `[` should have scope `variable.function`

Also recognize `f @ x` syntax for function call, but do NOT recognize `a ~f~ b` or `a // f`


## 1.3.3 - 11 Oct, 2021

Treat mdpopups module as optional

If a kernel cannot be started, then do not also show the timeout dialog after 10 seconds, that is just extra noise.

`lsp_server_enabled` setting: Allow selectively disabling Wolfram Language LSP


## 1.3.2 - 27 Sep, 2021

Fixed problem with dialog saying `"Language Server kernel did not initialize properly after 10 seconds."`

The kernel actually did start correctly, but the timeout for the dialog was not being handled properly.


## 1.3.1 - 23 Sep, 2021

First release from official Wolfram Research GitHub repo

[https://github.com/WolframResearch/Sublime-WolframLanguage](https://github.com/WolframResearch/Sublime-WolframLanguage)

Forked and major rewrite from [https://github.com/ViktorQvarfordt/Sublime-WolframLanguage](https://github.com/ViktorQvarfordt/Sublime-WolframLanguage)


## 1.3.0 - 30 Aug, 2021

Now supporting Sublime 4


## 0.12 - 5 Aug, 2019

Start relying on the WolframLanguage Sublime package. There is no longer a sublime-wolfram package to install. Please read the README for changes.
