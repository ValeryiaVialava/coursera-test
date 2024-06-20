# coursera-test
**Download** 
- Sublime Text

- Git
	> how to check the installation?
	> iTerm: `git --version`

- Node.js
	> iTerm: `node --version`
	> `npm --version`
	> <b style="color:#638878">npm</b> — **n**ode **p**ackage **m**anager 
	> `echo $PATH` (opt/local/bin or usr/local/bin)

- Browser-sync

	> installation though <b style="color:#638878">npm</b> :
	> `sudo npm install -g browser-sync`
	> `sudo` — "superuser do" дает права суперпользователя (root)
	> `-g` — global
	> `browser-sync --version`



**creating a new project and a server**
1. `ls` — показать содержимое текущего каталога (list the contents of the current directory)
2. `mkdir test_site` — create a new folder (directory) for our new project (website)
3. Sublime Text  —> create a new file `index.html`—> save it inside the `test_site` folder
4. in the `index.html` file, use `ctrl + space` shortcut to insert (`cmd+V`) a quick page HTML template
5. iTerm: `cd test_site` — change the current working directory to `test_site`
	 `ls` — показать содержимое текущего каталога (list the contents of the current directory)
	 `browser-sync start --server --directory --files "*"` — watch for any type of files and if any of those files change, go ahead and refresh the browser
	 browser: `localhost:3000`

**basics of Git**

Git book: https://git-scm.com/book/en/v2

краткое руководство по GitHub Pages: https://docs.github.com/ru/pages/quickstart

https://valeryiavialava.github.io/coursera-test/
