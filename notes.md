- we want our controller to deal with pods, look at pods
- kubebuilder init --domain my.domain --repo my.domain/operator-go-demo -> gives the boiler code 

- when we create a new resource we will create a new endpoint basically for kubernetes API
- since we are dealing with pods so pods belong to group=core, version=v1 bcoz its stable, kind=Pod
- kubebuilder create api --group core --version v1 --kind Pod -> to create new endpoint
