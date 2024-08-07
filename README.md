# FlaskDemo
## STEPS
### 1. Created GitHub repository

```bash
https://github.com/DelphineAsir/FlaskDemo.git
```
### 2. Created conda environment after opening the repository

```bash
conda create --name flaskdemo
```

```bash
conda activate flaskdemo

```
### 3. Installed packages 

- Generate requirement.txt file using  %%writefile magic function  

```bash
%%writefile requirements.txt
aniso8601==9.0.1
argon2-cffi==21.3.0
argon2-cffi-bindings==21.2.0
.
.
.
```
```bash
pip3 install -r requirements.txt

```