# TODO

* error handling
* 404 error
* build whole system in go means cloudbuild should make the app 

# console deployment


`kubectl run woss-io --image=gcr.io/woss-private/woss-io --port=80`
`kubectl expose deployment woss-io --target-port=80  --type=NodePort`
`kubectl apply -f woss.io.yaml`

icons from https://simpleicons.org/