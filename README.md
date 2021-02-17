# Clevertagger-Container
Docker script for "Clevertagger" and "SMORLemma". Both tools have been developed by [Rico Sennrich](https://github.com/rsennrich). Dockerfile based on work by [DoctorFuchs](https://github.com/DoctorFuchs).

Building:

```
docker build -t clever .
```

Running:

```
docker run clever
```

In your browser, navigate to /docs to access the OpenAPI GUI.

## Linguistic Todos

Clevertagger expects an array of tokenised sentences as input. Provide proper tokenisation.

## Dev Todos

1. Improve docker files.
2. Try to do without sending SMOR output to file.
3. Add proper input and output models.
