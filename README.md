
# Simple GO based web-server

Respond with a resource to get request for the following routes:

"/" => Return a static webpage rendered form an HTML template <br>
"/hello" => Return a static text message<br>
"/form.html" => Return the input of an HTML form<br>




## Run Locally

Clone the project

```bash
  git clone https://github.com/Viorel1989/Simple-web-Server.git
```

Go to the project directory

```bash
  cd Simple-web-Server
```

Run build

```bash
  go build
```

Start the server

```bash
  go run main.go
```


## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## Notice

If running the build command you encounter the following message :

> Error message "go: go.mod file not found in current directory or any parent directory; see 'go help modules'"

run the following command

```bash
  go env -w GO111MODULE=off
```

This will disable go modules and the build will run
