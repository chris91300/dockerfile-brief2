# frontend dockerfile

pour lancer le projet:

```bash
docker build -t frontend-dockerfile .
docker run --name frontend-test -p 4242:3000 frontend-dockerfile
```

puis il faut se rendre dans ton navigateur préféré sur localhost:4242
