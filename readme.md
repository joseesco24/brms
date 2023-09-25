# Dummy Enterprises Process Management System

My first attempt to create an enterprise architecture that left all the business logic in charge to enterprise systems, the idea is to use a BPMS and a BRMS as the main systems, but the architecture is also going to integrate a ERP and maybe in the future some custom developments. All the architecture is going to be implemented in Docker for this exercise.

<br/>

## Docker Compose Project Commands

**Note:** Before running any of these commands be sure that your **CWD** is **dummy_enterprises_process_management_system** directory.

### Docker Compose Build Image Using Compose File

```bash
docker-compose -f compose.build.yaml build
```

### Docker Compose Start Project Using Compose File

```bash
docker-compose -f compose.project.yaml up
```

### Docker Compose Stop Project Using Compose File

```bash
docker-compose -f compose.project.yaml down
```

<br/>
