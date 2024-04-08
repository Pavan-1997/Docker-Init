# Docker-Init

Initialize a project with the files necessary to run the project in a container.

Docker Desktop provides the docker init CLI command. Run docker init in your project directory to be walked through the creation of the following files with sensible defaults for your project:

- .dockerignore
- Dockerfile
- compose.yaml
- README.Docker.md

If any of the files already exist, a prompt appears and provides a warning as well as giving you the option to overwrite all the files. If docker-compose.yaml already exists instead of compose.yaml, docker init can overwrite it, using docker-compose.yaml as the name for the Compose file.

### Supported Languages:

- ASP.NET Core: Suitable for an ASP.NET Core application.
- Go: Suitable for a Go server application.
- Java: suitable for a Java application that uses Maven and packages as an uber jar.
- Node: Suitable for a Node server application.
- PHP with Apache: Suitable for a PHP web application.
- Python: Suitable for a Python server application.
- Rust: Suitable for a Rust server application.
- Other: General purpose starting point for containerizing your application.

## Initially running on the Local machine 

![image](https://github.com/Pavan-1997/Docker-Init/assets/32020205/2ee75ad2-8cb4-4862-aea9-2042ccecfcee)


```
pip3 install -r requirements.txt
```

```
python sample.py
```

![image](https://github.com/Pavan-1997/Docker-Init/assets/32020205/2bb21d67-1dad-4b18-bd52-d6bd204d1dd0)

![image](https://github.com/Pavan-1997/Docker-Init/assets/32020205/3858ac96-9551-4ee5-b28d-5e0af327503f)

---
## Using Docker Init 

```
docker init
```

![image](https://github.com/Pavan-1997/Docker-Init/assets/32020205/c90454fb-73b4-4697-a4da-e3a0520fd575)

![image](https://github.com/Pavan-1997/Docker-Init/assets/32020205/27e49a8b-2e01-4520-b3b8-e1de9e28b102)

![image](https://github.com/Pavan-1997/Docker-Init/assets/32020205/b0980901-810f-4a0e-81ab-681df3519bc7)

![image](https://github.com/Pavan-1997/Docker-Init/assets/32020205/ea128010-0b19-4fc3-b282-d5fcc31f855c)

![image](https://github.com/Pavan-1997/Docker-Init/assets/32020205/9e0423ea-8e16-4d18-94c7-15863a57635b)
