1. create virtual env

```
python3 -m venv venv
```

2. activate virtual environment
```
source venv/bin/activate
```

3. install dependencies
```
pip install -r requirements.txt
```

4. open notebooks
```
jupyter notebook
```

5. start web server to serve http page to redirect to hosted checkout 
```
python3 -m http.server  8090
```
