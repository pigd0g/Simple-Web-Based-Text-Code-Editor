# Simple Web Based Code Editor

Save content to a cookie by clicking the border. Warning clearing cache will lose the data.

Lightweight Nginx server

Docker Setup:

```
docker build -t code_editor .
docker run --name code_editor -p 8080 -d code_editor
```
