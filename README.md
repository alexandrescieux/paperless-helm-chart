# paperless

## Install

````bash
helm install paperless --create-namespace --namespace paperless .
````

## Update

````bash
helm upgrade paperless --install --namespace paperless .
````

## Delete

````bash
helm delete paperless --namespace paperless
````