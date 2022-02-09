## Authors

-[Tyler Do](https://github.com/dotyler)

## Running on Node.js five-server

Development server with live reload capability. To install:

### Install five-server

```bash
npm -g i five-server
```

Update five-server (from time to time)

```bash
npm -g i five-server@latest
```

To run (from your local directory):

```bash
five-server . -p 8000
```

## Python server

If you have Python installed, it should be enough to run this from a command line (from your working directory):

### Python 2.x

```bash
python -m SimpleHTTPServer
```

### Python 3.x

```bash
python -m http.server
```

This will serve files from the current directory at localhost under port 8000, i.e in the address bar type:
http://localhost:8000/
