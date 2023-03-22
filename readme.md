# The GCP DevOps Course
These are notes from the GCP DevOps Course hosted on KodeKloud.

## Build guidelines

### Application mode
Step 1: Run
```
flask run
* Running on http://127.0.0.1:5000
```
Step 2: Observe
- Access application at http://127.0.0.1:5000/
### Container mode

Container mode (required Docker)
Step 1: Build

`$ docker build -t hello-py .`

Step 2: Run

`$ docker run -dt --name hello-python -p 5000:5000 hello-py`

Step 3: Observe

Access application at http://localhost:5000

![image](https://user-images.githubusercontent.com/124754423/226847161-5c95b3a1-036d-4167-b29a-abe669701692.png)


